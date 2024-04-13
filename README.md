
# Unity Project Setup and Management Guide With GitHub Desktop 🚀

## Table of Contents

- [Unity Project Setup and Management Guide With GitHub Desktop](#unity-project-setup-and-management-guide-with-github-desktop)
- [Table of Contents](#table-of-contents)
- [Essential Credentials 🗝️](#essential-credentials-🗝️)
  - [Unity/GitHub Account Access](#unitygithub-account-access)
- [Preparing for Students 🎒](#preparing-for-students-🎒)
  - [GitHub Desktop](#github-desktop)
  - [Unity](#unity)
- [Handling Student Sessions 📚](#handling-student-sessions-📚)
  - [Student Arrival](#student-arrival)
  - [Starting a New Project 🌟](#🌟-starting-a-new-project)
  - [Saving the Project to GitHub 💾](#💾-saving-the-project-to-github)
  - [Continuing an Existing Project 🔁](#🔁-continuing-an-existing-project)

## Essential Credentials 🗝️

### Unity/GitHub Account Access
- **Username:** `CodeNinjasDripping`
- **Password:** `Code_Ninjas!2024`

## Preparing for Students 🎒

### GitHub Desktop
- Ensure GitHub Desktop is installed on the machine. If not, download it [here](https://central.github.com/deployments/desktop/desktop/latest/win32).
- Sign into GitHub Desktop with the center GitHub account. You must also be signed into GitHub.com for authentication.

### Unity
1. **Unity Hub Check:** Ensure both Unity Hub and the Unity environment are installed. Search for `unity` to verify.
2. **Download and Install (if needed):** If Unity is not installed, download it from the [Unity Download Page](https://unity.com/download).
3. **Account Sign-In:** Use the [provided credentials](#unitygithub-account-access). Allow students to use their own accounts if available.

## Handling Student Sessions 📚

### Student Arrival
Determine the student's goal:
- 🆕 Starting a New Project
- 🔄 Continuing an Existing Project


---

### 🌟 Starting a New Project

#### 🛠️ Step 1: Creating a Local Repository
1. **Open GitHub Desktop:** Assuming you're already signed in, navigate to `File > New Repository`.
2. **Repository Details:**
   - **Name:** Format the repository name as `firstname_lastname_project_name`.
   - **Description:** Leave this field empty to keep things neat.
   - **Local Path:** Set the path to your desktop, e.g., `C:\Users\logan\Desktop`.
   - **Initialize Options:** No README, .gitignore, or License. Keep it simple!

#### 🚀 Step 2: Publishing to GitHub
1. **Publish Repository:** Click the 'Publish Repository' button in GitHub Desktop.
2. **Remote Repository Settings:**
   - **Repository Name:** Should match the local repository name.
   - **Privacy:** Make sure the repository is public—uncheck any options for privacy.

#### 🎮 Step 3: Setting Up the Project
1. **Create a Unity Project:** Fire up Unity and establish a new project in the directory you set on your desktop.
   - **Project Name:** Stick to the `firstname_lastname_project_name` convention.

### 💾 Saving the Project to GitHub

1. **Prepare to Save:** ⏰ About 10 minutes before wrapping up, ensure students save their Unity project and close the application.
2. **Commit Changes:**
   - **Check Repository:** Make sure you're in the correct repository on GitHub Desktop.
   - **Summary & Description:** Fill in the 'Summary' with the **current date** and let students detail their progress in the 'Description'.
   - **Commit to Main:** Hit that 'Commit to main' button and push the changes online.

### 🔁 Continuing an Existing Project
1. **Access GitHub Desktop:** Assuming you're already logged in, navigate to `File > Clone Repository`.
2. **Select the Project:**
   - Choose the repository named `firstname_lastname_project_name`.
   - **Local Path:** Ensure the location is set to `C:\Users\logan\Desktop`.
   - **Clone:** Hit the 'Clone' button.
3. **Initialize Git LFS:** If prompted, activate Git LFS by clicking the blue button. This is crucial for handling large files!
4. **Open Unity Hub:** Select `Add->Add Remote Project`, browse to the cloned repository directory, and open the project.
5. **Work and Save:** Let students work on their project. As they wrap up (⏰ 10 minutes before the session ends), remind them to [save their changes to GitHub](#💾-saving-the-project-to-github).

---

