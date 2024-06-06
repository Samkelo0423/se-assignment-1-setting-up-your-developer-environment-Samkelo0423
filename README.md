[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15231676&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment
### Assignment: Setting Up My Developer Environment

#### Objective:
This assignment aims to familiarize me with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. By completing this assignment, I will gain the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

---

### Tasks:

#### 1. Select Your Operating System (OS)
- **Task:** Choose an OS that suits my preferences and project requirements.
- **Action:** Download and Install Windows 11.
  - [Windows 11 Download](https://www.microsoft.com/software-download/windows11)

**Steps:**
1. I visited the provided link and downloaded the Windows 11 installation media.
2. I followed the instructions to create a bootable USB drive.
3. I booted from the USB drive and followed the on-screen instructions to install Windows 11.

#### 2. Install a Text Editor or Integrated Development Environment (IDE)
- **Task:** Install a text editor or IDE suitable for my programming languages and workflow.
- **Action:** Download and Install Visual Studio Code.
  - [Visual Studio Code Download](https://code.visualstudio.com/Download)

**Steps:**
1. I visited the Visual Studio Code website and downloaded the installer for Windows.
2. I ran the installer and followed the prompts to complete the installation.
3. I launched Visual Studio Code and customized it according to my preferences.

#### 3. Set Up Version Control System
- **Task:** Install Git, configure it, create a GitHub account, initialize a Git repository, and make my first commit.
  - [Git Download](https://git-scm.com/)
  - [GitHub](https://github.com)

**Steps:**
1. I downloaded and installed Git from the official Git website.
2. I opened Git Bash and configured Git with my user name and email:
   ```bash
   git config --global user.name "My Name"
   git config --global user.email "my.email@example.com"
   ```
3. I created a GitHub account.
4. I initialized a Git repository for my project:
   ```bash
   git init my-project
   cd my-project
   echo "# My Project" >> README.md
   git add README.md
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/myusername/my-project.git
   git push -u origin main
   ```

#### 4. Install Necessary Programming Languages and Runtimes
- **Task:** Install Python.
  - [Python Download](https://www.python.org)

**Steps:**
1. I visited the Python website and downloaded the latest installer.
2. I ran the installer and ensured I checked the option to add Python to PATH.
3. I verified the installation by opening Command Prompt and running:
   ```bash
   python --version
   ```

#### 5. Install Package Managers
- **Task:** Install pip for Python.

**Steps:**
1. Pip should be installed with Python by default. I verified it by running:
   ```bash
   pip --version
   ```

#### 6. Configure a Database (MySQL)
- **Task:** Download and install MySQL.
  - [MySQL Download](https://dev.mysql.com/downloads/windows/installer/5.7.html)

**Steps:**
1. I visited the MySQL download page and downloaded the installer.
2. I ran the installer and followed the setup wizard to install MySQL.
3. I configured MySQL according to my project needs.

#### 7. Set Up Development Environments and Virtualization (Optional)
- **Task:** Use virtualization tools like Docker or virtual machines.
  - [Docker Download](https://www.docker.com/products/docker-desktop)

**Steps:**
1. I visited the Docker website and downloaded Docker Desktop.
2. I installed Docker Desktop and followed the setup instructions.
3. I verified the installation by running:
   ```bash
   docker --version
   ```

#### 8. Explore Extensions and Plugins
- **Task:** Enhance Visual Studio Code with extensions.

**Steps:**
1. I opened Visual Studio Code.
2. I went to the Extensions view by clicking the Extensions icon in the Activity Bar.
3. I searched for and installed useful extensions such as:
   - Python
   - GitLens
   - Prettier - Code formatter
   - ESLint

