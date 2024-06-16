[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15251736&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11.click download now then ok on microsoft
     2.Before installing please refer to the PC HEALTH CHECK to confirm your device meets the minimum system requirements for windows 11
     3.Download it and check the requirements
     4.Create windows 11 installation media 
     5.Take a language choose which media to use;
     USB flash drive
     ISO file 
     6.Connect USB Copy Windows Setup to the USB flash drive.

Use File Explorer to copy and paste the entire contents of the Windows product DVD or ISO to the USB flash drive.
7.Install Windows to the new PC.
8.Connect the USB flash drive to a new PC.
9.Turn on the PC and press the key that opens the boot-device selection menu for the computer, such as the Esc/F10/F12 keys. Select the option that boots the PC from the USB flash drive.
Windows Setup starts.
 9. Follow the instructions to install Windows.
10.Remove the USB flash drive. 

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/DownloadDownloadownload Visual Studio:Screenshot 2024-06-15 124758.png
Visit the Visual Studio website and click on "Download Visual Studio."
Follow the on-screen instructions to download the installer.
. Run the Installer:
Run the downloaded installer.Screenshot 2024-06-15 125829.png
Choose the "Visual Studio" workload during installation, which includes the necessary components for general development.Screenshot 2024-06-15 125921.png
. Select Workloads and Components:
In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Development" or "Web Development."
Modify Installation (Optional):
If needed, you can customize the installation by clicking on the "Individual components" tab in the installer and selecting or deselecting specific components.
Install:
Click the "Install" button to start the installation process.
This may take some time, as it involves downloading and installing the selected components.
Launch Visual Studio:
Once the installation is complete, launch Visual Studio.
Sign in with your Microsoft account or create one if prompted.
Choose Development Environment:
On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.
Start Coding:
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.comFill out the form with your username, email address, and a strong password.
Follow any additional prompts to verify your email address and complete your profile setup.
   1.In the upper-right corner of any page, select , then click New repository.

Screenshot of a GitHub dropdown menu showing options to create new items. The menu item "New repository" is outlined in dark orange.
Type a short, memorable name for your repository. For example, "hello-world".

Screenshot of the first step in creating a GitHub repository. The "Repository name" field contains the text "hello-world" and is outlined in dark orange.
Optionally, add a description of your repository. For example, "My first repository on GitHub."

Choose a repository visibility. For more information, see "About repositories."

Select Initialize this repository with a README.

Click Create repository.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.to download the latest release ofPython. In this process, we will install Python 3.8.6 on ourWindows operating system. When we click on the above link, it will bring us the following page.

Step - 1: Select the Python's version to download.![alt text](<Screenshot 2024-06-15 152818.png>)Screenshot 2024-06-15 153249.png

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
to download the latest release ofPython. In this process, we will install Python 3.8.6 on ourWindows operating system. When we click on the above link, it will bring us the following page.

Step - 1: Select the Python's version to download.![alt text](<Screenshot 2024-06-15 152818.png>)Screenshot 2024-06-15 153249.png
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.comto download the latest release ofPython. In this process, we will install Python 3.8.6 on ourWindows operating system. When we click on the above link, it will bring us the following page./downloads/windows/installer/5.7.html
Select the appropriate version:
MySQL Community Server: The free and open-source edition, suitable for most use cases.
Version: Choose a stable version (e.g., 8.0.37 LTS for long-term support).
Download the installer:
For MySQL 8.0 and earlier: Download the "MySQL Installer" (MSI file) if you prefer a wizard-based installation.
For MySQL 8.1 and later: Download the appropriate MSI or ZIP archive based on your preference. The MSI installer offers a simpler process, while the ZIP archive provides more granular control.
Installing MySQL:

Run the downloaded installer:
For MySQL Installer (up to version 8.0): Double-click the MSI file and follow the on-screen instructions. The installer will guide you through configuration options like setting the root password, choosing the installation type (typical, full, custom), and starting the MySQL service.
For MSI installers (MySQL 8.1 and later): Double-click the MSI file. The installation process is generally straightforward, but you may be presented with configuration options during installation.
For ZIP archives: Extract the contents of the ZIP archive to a desired location on your system. You'll need to configure MySQL manually using tools like the MySQL Shell or MySQL Workbench (these may be included in the archive). Refer to the MySQL documentation for detailed manual configuration steps.
   

7. Set Up Development Environments and Virtualization (Optional):Benefits of Virtualization:

Project Isolation: Each project can have its own dependencies and configurations, preventing conflicts between projects.
Consistent Environments: Virtual environments ensure consistency across different development machines, reducing the "works on my machine" problem.
Reproducibility: Makes it easier to share and replicate development environments with other team members.
Efficiency: Allows for quick setup and teardown of development environments.
1. Docker:

Docker excels at creating lightweight, self-contained containers that package an application with all its dependencies. This makes Docker ideal for microservices architectures and deploying applications.

Getting Started with Docker:

Install Docker: Download and install Docker Desktop for your operating system from https://www.docker.com/products/docker-desktop/.
Create a Dockerfile: This file defines the instructions for building your Docker image, specifying the base image, dependencies, and application code. You can find many Dockerfile examples online.
Build the Docker image: Use the docker build command to build the image based on your Dockerfile.
Run the container: Use the docker run command to start a container from your image. This creates an isolated environment with your application and dependencies.
2. Virtual Machines (VMs):

VMs provide a more complete environment emulation, allowing you to run a full operating system within a virtual machine instance on your host machine. This is useful for situations where you need a specific operating system or non-containerized software for development.

Popular VM Software:

VirtualBox: Free and open-source, user-friendly for beginners (https://www.virtualbox.org/wiki/Downloads).
VMware Workstation Player: Free for non-commercial use, offers more advanced features than VirtualBox (https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html.html.html).
Getting Started with VMs:

Install the VM software.
Download an operating system image: You can find free and paid operating system images online.
Create a virtual machine: Use the VM software to create a new virtual machine, allocating resources like CPU, memory, and storage.
Install the guest operating system: Install the downloaded operating system image within the virtual machine.
Install development tools: Once your virtual machine is up and running, you can install your preferred development tools and configure your development environment.
Choosing Between Docker and VMs:

Use Docker for: Microservices architectures, isolating application dependencies, and quick deployments.
Use VMs for: Development requiring a specific operating system or non-containerized software, testing across different operating systems.
Additional Tips:

Version control your Dockerfiles and VM configurations: This allows you to easily replicate your development environments across machines and versions.
Consider using container orchestration tools like Docker Compose: These tools simplify managing multiple Docker containers and their dependencies.

   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.Visual Studio Code (VS Code): This free and open-source editor boasts a vast marketplace with extensions for nearly every programming language, framework, and development task. Some popular extensions include:

Language-specific extensions: Python (Pylance), Java (Java Extension Pack), C/C++ (C/C++ by Microsoft)
Linters: ESLint (JavaScript), Stylelint (CSS)
Formatters: Prettier (multi-language), Beautify (various languages)
Version control: GitLens, GitHub Pull Requests
Productivity: Bracket Pair Colorizer, Code Runner
Sublime Text: While not as extensive as VS Code, Sublime Text offers a good selection of packages through Package Control. Some notable options include:

Language-specific packages: Anaconda (Python), Sublime Text C/C++
Linters: SublimeLinter (works with various linters), ESLint
Formatters: AlignTab, Babel
Version control: GitGutter, Sublime Merge
Productivity: Emmet (generating HTML/CSS), ColorPicker
Atom: Similar to Sublime Text, Atom offers a vibrant package ecosystem. Here are some popular packages:

Language-specific packages: language-python, language-java
Linters: Linter, ESLint
Formatters: Beautify, Atom-Beautify
Version control: Git Plus, Atom GitHub
Productivity: autocomplete-plus (autocompletion), multi-cursor (multiple cursors)
IntelliJ IDEA (paid): This powerful IDE comes bundled with many features, but extensions can further enhance it. Some useful extensions include:

Language-specific plugins: Python (PyCharm), Kotlin
Linters: CodeNarc (Java), SpotBugs (Java)
Formatters: Code Formatter (various languages)
Version control: Git Integration
Productivity: Rainbow Brackets, Key Promoter (learning keyboard shortcuts)
Finding the Perfect Extensions:

Search within your editor/IDE's marketplace or extension store.
Read reviews and ratings from other developers.
Consider your programming language and primary development tasks.
Start with a few essential extensions and gradually add more as needed.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.This document outlines the steps taken to set up my development environment, including software installations, configurations, customizations, and any troubleshooting encountered.

Target Operating System: [Insert your operating system (e.g., Windows 10, macOS Monterey, Ubuntu 22.04)]

Date: [Insert current date]

1. Text Editor/IDE:

Software: [Name of text editor or IDE (e.g., Visual Studio Code, IntelliJ IDEA, Sublime Text)]
Version: [Version number]
Installation: Downloaded the installer from the official website ([link to website]) and followed the on-screen instructions.
Configurations:
Installed essential extensions for the chosen programming language(s) (e.g., Python, Java). ([Optional:] List specific extensions)
Customized the user interface theme and keyboard shortcuts for better ergonomics.
Troubleshooting: (If any) Briefly describe any issues faced during installation or configuration and how they were resolved.
2. Version Control System (VCS):

Software: [Name of VCS (e.g., Git)]
Version: [Version number (if applicable)]
Installation:
Windows: Downloaded and installed Git Bash from https://www.git-scm.com/download/win.
macOS/Linux: Used the built-in package manager (e.g., apt-get install git on Ubuntu)
Configurations:
Set up global username and email for Git commits (git config --global user.name "Your Name" && git config --global user.email "your_email@example.com")
Troubleshooting: (If any) Briefly describe any issues faced during installation or configuration and how they were resolved.
3. Additional Tools (if applicable):

Node.js & npm (for JavaScript development):
Downloaded and installed the latest LTS version from the official website (https://nodejs.org/en).
Python package manager (e.g., pip):
Installed with Python or managed through virtual environments for project isolation.
Database Management Tools (e.g., MySQL Workbench):
Downloaded and installed from the official website (if not included with the database server).
Web Server (e.g., Apache, Nginx):
Installed and configured using the system's package manager or downloaded from the official website.
4. Customizations and Optimizations:

Terminal: Configured the terminal emulator (e.g., Terminal app on macOS) for better readability and functionality. (Optional: Briefly describe customizations)
System-wide: Adjusted system settings related to developer experience, such as keyboard shortcuts or file associations. (Optional: Briefly describe customizations)
5. Troubleshooting:

Describe any significant issues encountered during the setup process and the steps taken to resolve them.
Include details about error messages, solutions attempted, and references to helpful resources (e.g., online forums, documentation). 

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
