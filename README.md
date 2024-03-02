
# Git Guide for Students: Managing Projects with Git

## Introduction
This guide will assist you in using Git for project management. It covers creating new branches, switching between them, and syncing changes with a remote repository. 

If you ever have any questions, feel free to ask a Sensei!

### Prerequisites
- Git should be installed on your machine.
- Access to the remote Git repository (e.g., GitHub, GitLab).

## Basic Git Operations

### Setting Up Your Local Environment

#### 1. Creating a Temporary Directory
Create a directory for your project.

**Windows:**
```cmd
mkdir C:\path\to\your\project
cd C:\path\to\your\project
```

#### 2. Initializing a Git Repository
```bash
git init
```
- `git init`: Initializes a new Git repository in the current directory.

#### 3. Linking to the Remote Repository
```bash
git remote add origin your-remote-repository-url
```
- `git remote add`: Adds a new remote to your local repository.
- `origin`: A conventional name for your main remote repository.
- `your-remote-repository-url`: The URL of the remote repository.

## Working on an Existing Project (e.g., Project1)

#### 1. Switching to an Existing Branch
```bash
git checkout -b project1 origin/project1
```
- `git checkout -b`: Creates and checks out a new branch.
- `project1` (first occurrence): The name of the new branch you are creating locally.
- `origin/project1`: The remote branch that the new local branch will track.

#### 2. Pulling Changes from the Remote Branch
```bash
git pull origin project1
```
- `git pull`: Fetches from and integrates with the remote branch.
- `origin`: The remote repository.
- `project1`: The remote branch to pull from.

## Starting a New Project (e.g., Project2)

### Creating and Pushing a New Branch

#### 1. Creating a New Branch Locally
```bash
git checkout -b project2
```
- `git checkout -b`: Creates and checks out a new branch.
- `project2`: The name of the new local branch.

#### 2. Pushing the New Branch to the Remote Repository
```bash
git push -u origin project2
```
- `git push`: Sends your local branch commits to the remote repository.
- `-u`: Sets the upstream for your branch, linking it to the remote.
- `origin`: The remote repository.
- `project2`: The local branch name.

### Working with the New Branch

#### 1. Making and Committing Changes
- Make changes to your project.
- Stage and commit those changes:

  ```bash
  git add .
  git commit -m "Your commit message"
  ```
  - `git add .`: Adds all new and modified files to the staging area.
  - `git commit -m`: Records changes to the repository, `-m` followed by a commit message in quotes.

#### 2. Pushing Changes to the Remote
- Push your commits to the remote branch:

  ```bash
  git push origin project2
  ```
  - `git push`: Updates the remote branch with local commits.
  - `origin`: The remote repository name.
  - `project2`: The branch name.

---

common issue 
if github says cannot resolve hostname github.com, use this command
```bash
git config --global --unset https.proxy
```
