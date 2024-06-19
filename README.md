[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15296994&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

System Requirements
Before you start, ensure your PC meets the minimum system requirements for Windows 11:
Processor, RAM, Storage, System Firmware, TPM, Graphics Card, Display, Internet Connection.
Downloading Windows 11
1.	Visit the Official Microsoft Website:
2.	Get Windows 11: Click on "Download now" under the "Install Windows 11" section.
3.	Windows Installation Assistant: Run the Windows 11 Installation Assistant if you are upgrading from Windows 10. while opening the downloaded file, it gives a Prompt to change the  Follow the on-screen instructions to complete the installation.
Creating Installation Media (Optional)
If you prefer to create a bootable USB drive or DVD:
1.	Download the Media Creation Tool: On the Windows 11 download page, download the Media Creation Tool.
2.	Run the Media Creation Tool: Follow the prompts to create a bootable USB drive or DVD. Select the "Create installation media" option.
3.	Select Language and Edition: Choose your preferred language, edition, and architecture (64-bit).
4.	Create Installation Media: Insert a USB drive (8 GB or larger) and let the tool create the installation media.
Installing Windows 11
1.	Insert Installation Media: Plug in the USB drive or insert the DVD into the PC you want to upgrade.
2.	Restart Your PC: Restart your PC and boot from the USB drive or DVD. You might need to change the boot order in the BIOS/UEFI settings.
3.	Follow Installation Prompts:
Select your language, time, and keyboard preferences. Click Next and then Install Now.
4.	Choose Installation Type: Select Custom: Install Windows only (advanced) for a clean installation or Upgrade to keep your files and apps.
5.	Partition Your Drive: Select the partition where you want to install Windows 11. For a clean installation, format the partition.
6.	Complete Installation: Follow the on-screen instructions to complete the installation. Your PC will restart several times.
7.	Set Up Windows 11: Once Windows 11 is installed, go through the initial setup process, including choosing your region, and keyboard layout, and signing in with a Microsoft account.
After Installation
•	Update Windows: Go to settings > Update & Security > Windows Update and click Check for updates to ensure you have the latest features and security updates.
•	Install Drivers: Make sure all your drivers are up to date, especially graphics, network, and audio drivers.
•	Restore Data: Restore your data and reinstall your applications.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3.1.	Click on the above link
Download the Installer: Click on the appropriate download link for Windows.
Installing Visual Studio Code https://gyazo.com/ee2f162067562e34eb54263c51e21f98
1.	Run the Installer: Locate the downloaded VSCodeSetup.exe file and double-click it to start the installation process.
2.	Follow the Setup Wizard:
o	Accept the license agreement and click Next.
o	Choose the installation location and click Next.
o	Select additional tasks. It’s recommended to:
	Add "Open with Code" action to the Windows Explorer file context menu.
	Add "Open with Code" action to the Windows Explorer directory context menu.
	Register Code as an editor for supported file types.
	Add to PATH (useful for command line).
3.	Install:
o	Click Install to begin the installation.
Initial Setup of Visual Studio Code
1.	Launch Visual Studio Code:
o	Open VS Code from the Start menu or desktop shortcut.
•	Install Extensions: Click on the Extensions icon on the sidebar  Extensions Marketplace:Explore and install more extensions from the Extensions Marketplace to enhance your development environment.https://gyazo.com/fcf3c326469c2a06e345760ca49d165f
2.	Install any necessary extensions for your programming languages and workflow. Popular extensions include Python: For Python development.
3.	Configure Settings: Go to File > Preferences > Settings to customize VS Code to your preferences. You can also directly edit the settings.json file for more advanced configuration.
4.	Open a Folder or Workspace: Click File > Open Folder to open your project folder or File > Add Folder to Workspace to add it to an existing workspace.
5.	Start Coding:
o	Create a new file by clicking File > New File or open existing files from your project folder.


Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
Go to the Git for Windows download page and download the latest version.
Open the downloaded file and follow the setup instructions.
Choose the default options unless you have specific requirements.
Set your username
Set your email
Verify your settings
Create a GitHub Account
1.	Sign up for GitHub: Go to the above link and create a new account.
: Initialize a Git Repository   Navigate to your project directory:
1.	Initialize a new Git repository git init
2.	Add files to the repository; git add.
3.	Make your first commit: git commit -m "Initial commit"
Step 5: Connect to GitHub
1.	Create a new repository on GitHub: Go to GitHub and click on the New button to create a new repository.
2.	Give your repository a name, add a description (optional), and choose public or private.
3.	Do not initialize the repository with a README, .gitignore, or license as you already have a local repository.
4.	Add the remote repository URL to your local repository:
git remote add origin
5.	Push your local repository to GitHub:
git push -u origin master
Now, your project is initialized as a Git repository, and your first commit has been made and pushed to GitHub. You can start collaborating and managing your project with Git and GitHub

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
1.	Visit the Official Python Website
2.	Click on the download link for the latest version of Python. For most users, the latest stable release is recommended.
3.	Locate the downloaded file and run the installer. Ensure you check the box that says "Add Python to PATH" before clicking "Install Now".
Step 2: Verify the Installation; Open Command Prompt or PowerShell (Windows) 
Type the following command to verify the installation:
python --version
1.	Check Pip Installation:
o	Pip is the package installer for Python. It should be installed automatically with Python.
o	Verify by typing: pip --version
 Install Necessary Tools and Libraries
1.	Update pip
2.	python -m pip install --upgrade pip
3.	Install Virtual Environment 
4.	pip install virtualenv
5.	Create a Virtual Environment:
o	Navigate to your project directory and create a virtual environment:
cd path/to/your/project
python -m venv 
6.	Activate the Virtual Environment:
venv\Scripts\activate
7.	Install Required Packages: Use pip to install any libraries or frameworks your project needs. For example: pip install Django
Step 4: Verify Your Setup
1.	Create a Simple Python Script: Create a file named test.py 
2.	Run the Script: Execute the script using Python: python test.py
Additional Tools
Depending on your project requirements, you may need to install other tools or IDEs for a better development experience:
1.	Install IDE (e.g Visual Studio Code): For Visual Studio Code, refer to the previous instructions on installing VS Code.
2.	Set Up Python Interpreter in IDE: Configure your IDE to use the Python interpreter from your virtual environment 
1.	Open Visual Studio Code.
2.	Install Python Extension:
o	Go to the Extensions view by clicking the square icon in the sidebar or pressing Ctrl+Shift+X.
o	Search for "Python" and install the extension by Microsoft.
3.	Select Python Interpreter:
o	Press Ctrl+Shift+P to open the Command Palette.
o	Type Python: Select Interpreter and select the Python interpreter from your virtual environment.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Check if pip is installed: Open your Command Prompt; pip --version
Configure Virtual Environments 
Using virtual environments helps isolate your project’s dependencies from the system-wide Python environment.
1.	Install virtualenv; pip install virtualenv
2.	Create a Virtual Environment: Navigate to your project directory and create a virtual environment: 
3.	cd path/to/your/project
python -m venv venv
4.	Activate the Virtual Environment: On Windows:
venv\Scripts\activate

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
1.	Visit the MySQL Download Page:
2.	Choose the Installer: Select the "Windows (x86, 32-bit), MSI Installer" or the appropriate version for your system. Click on "Download".
3.	Skip Sign Up: click on "No thanks, just start my download" to proceed without signing up.
Step 2: Install MySQL
1.	Run the Installer: Locate the downloaded mysql-installer-community-5.7.x.x.msi file and double-click it to start the installation process.
2.	Choose Setup Type: Select the setup type. For most users, the "Developer Default" or "Server only" setup type is sufficient. If you need specific components, choose "Custom".
3.	Install Required Components: The installer will check for the required components and prompt you to install any missing dependencies.
4.	Install MySQL: Click "Execute" to download and install the selected components. This process may take a few minutes.
Step 3: Configure MySQL Server
1.	Configuration Type: Choose "Standalone MySQL Server / Classic MySQL Replication".
2.	Connectivity: Configure the connection settings. The default port is 3306. You can leave it as is unless you have specific requirements.
3.	Authentication Method: Choose the authentication method. The recommended option is "Use Strong Password Encryption for Authentication 
4.	Create a Root Password: Set a strong password for the root user. Make sure to remember this password as it is required for administrative access.
5.	Windows Service:
o	Configure MySQL to run as a Windows service. This allows MySQL to start automatically with your system. Leave the default service name as "MySQL".
6.	Apply Configuration: Click "Execute" to apply the configuration settings. The installer will configure MySQL and start the MySQL service.
Step 4: Verify MySQL Installation
1.	Open MySQL Command Line Client: Launch the MySQL Command Line Client from the Start menu.
2.	Log In to MySQL: Enter the root password you set during the configuration process.
3.	Check MySQL Version: To verify the installation, run the following command:
sql
SELECT VERSION();
o	This should display the installed MySQL version.
Step 5: Install MySQL Workbench 
1.	Download MySQL Workbench; you can download MySQL Workbench from the MySQL Workbench download page.
2.	Install MySQL Workbench: Run the installer and follow the on-screen instructions.
3.	Connect to MySQL Server: Open MySQL Workbench and create a new connection to your MySQL server using the root account credentials.
Step 6: Create a Database
1.	Log In to MySQL:Open the MySQL Command Line Client or MySQL Workbench and log in with your root credentials.
2.	Create a New Database: Run the following SQL command to create a new database:
sql
CREATE DATABASE my_database;
3.	Verify Database Creation:
o	List all databases to ensure your new database was created: SHOW DATABASES;

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
1.	Download VirtualBox: Go to the VirtualBox download page and download the installer for Windows
2.	Install VirtualBox: Run the installer and follow the on-screen instructions.
Step 2: Create a Virtual Machine
1.	Open VirtualBox: Launch VirtualBox.
2.	Create a New VM: Click "New" to create a new virtual machine.
Follow the prompts to configure your VM:
	Name: Choose a name for your VM.
	Type: Linux (if you are using a Linux-based VM).
	Version: Select the appropriate version (e.g., Windows 64-bit).
3.	Allocate Resources:
o	Allocate memory (RAM) and create a virtual hard disk. The default settings are usually sufficient for development purposes.
4.	Install an Operating System:
o	Download an ISO file of the operating system you want to Start the VM and select the ISO file to begin the installation process.
o	Follow the prompts to complete the OS installation.
Step 3: Set Up Your Development Environment in the VM
1.	Install Development Tools:
o	Open the terminal in your VM and install the necessary tools. For example, to set up a Python development environment: sudo apt update
sudo apt install python3 python3-pip python3-venv
2.	Clone Your Project:
o	If your project is hosted on GitHub, clone it to the VM: git clone https://github.com/yourusername/your-repo.git
cd your-repo
3.	Set Up a Virtual Environment; Create and activate a virtual environment: python3 -m venv venv
source venv/bin/activate
4.	Install Dependencies:
o	Install the required Python packages: pip install -r requirements.txt

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Visual Studio Code Extensions
Step 1: Open the Extensions View
1.	Open VS Code.
2.	Access the Extensions View:
o	Click on the Extensions icon in the Activity Bar on the side of the window.
o	Alternatively, press Ctrl+Shift+X.
Step 2: Search and Install Extensions
Here are some essential and highly recommended extensions for various functionalities:
1.	Python Development:nPython: Official extension by Microsoft for Python development. It provides IntelliSense (Pylance), linting, debugging, and other features. ms-python.python
2.	Code Formatting: Prettier - Code formatter: An opinionated code formatter that supports many languages. It ensures a consistent code style. esbenp.prettier-vscode
3.	Linting: ESLint: Integrates ESLint JavaScript into VS Code, helping you find and fix problems in your JavaScript code. dbaeumer.vscode-eslint
4.	Version Control Integrate GitLens: Enhances Git capabilities, showing detailed git blame information, inline changes, and more eamodio.gitlens
5.	Docker: Docker: Provides Docker support, enabling you to build, manage, and deploy containerized applications from within VS Code. ms-azuretools.vscode-docker
6.	Database Management:
o	SQLTools: A lightweight SQL client for various databases (MySQL, PostgreSQL, SQLite, etc.) with an intuitive UI. mtxr.sqltools
7.	Snippet Management: Code Snippets: Collections of useful code snippets for various languages and frameworks.
	For example, JavaScript (ES6) code snippets: xabikos.javascriptsnippets
8.	Themes and Icons: Material Icon Theme: Adds a set of icons to the File Explorer for better visual identification. pkief.material-icon-theme
o	One Dark Pro: A popular theme inspired by the Atom editor. zhuangtongfa.material-theme

9.	Markdown Support: Markdown All in One: Enhances Markdown editing experience with features like auto preview, table of contents, and more.yzhang.markdown-all-in-one
10.	Remote Development:
o	Remote - WSL: Develop in a Linux environment using Windows Subsystem for Linux. ms-vscode-remote.remote-wsl
o	Remote - Containers: Develop inside a Docker container, with full isolation from your local environment.
ms-vscode-remote.remote-containers
Step 3: Configure Installed Extensions
1.	Access Extension Settings: After installing an extension, you can configure its settings by clicking on the gear icon next to the extension in the Extensions view and selecting "Extension Settings".
2.	Global Settings: Go to File > Preferences > Settings or press Ctrl+, to open the global settings. Here you can configure settings for installed extensions.
Step 4: Use Extensions in Your Workflow
1.	Activate Extensions: Some extensions require you to reload VS Code or open a specific type of file to activate their features.
2.	Explore Commands: Many extensions add their own commands to the Command Palette. Press Ctrl+Shift+P to open the Command Palette and type the extension name to see available commands.
Example: Setting Up Python Environment in VS Code
1.	Install the Python Extension: Search for "Python" in the Extensions view and install the extension by Microsoft.
2.	Select Python Interpreter: Press Ctrl+Shift+P, type Python: Select Interpreter, and choose the appropriate Python interpreter from the list.
3.	Enable Linting and Formatting:
o	Open File > Preferences > Settings.
o	Search for "Python Linting" and ensure it is enabled.
o	Search for "Python Formatting Provider" and select black or autopep8 (ensure the corresponding package is installed in your environment).
4.	Set Up Debugging:
o	Create a .vscode folder in your project directory.
o	Create a launch.json file with the following configuration for Python

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
