[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15251356&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
*Ensure that your system meets the minimum requirements:
-Processor: 1 gigahertz (GHz) or faster with 2 or more cores on a compatible 64-bit processor or System on a Chip (SoC).
-RAM: 4 gigabytes (GB) or more.
-Storage: 64 GB or larger storage device.
-TPM: Trusted Platform Module (TPM) version 2.0.
-Graphics Card: DirectX 12 compatible graphics / WDDM 2.x.
-Display: >9” with HD Resolution (720p).
-Internet connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

3. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   *To install Visual Studio Code (VS Code), follow these steps:
-Step 1: Download VS Code
Go to the official Visual Studio Code website: Visual Studio Code Download.
Choose the appropriate download option based on your operating system (Windows, macOS, or Linux).
Click on the download button to start downloading the installer.
-Step 2: Install VS Code
Once the download is complete, follow these instructions to install VS Code:

Windows: Double-click on the downloaded .exe file to launch the installer. Follow the prompts in the installer to complete the installation.

macOS: Open the downloaded .dmg file. Drag and drop Visual Studio Code.app to the Applications folder. You can then launch VS Code from the Applications folder.

Linux: Depending on your distribution, you might install VS Code using apt, yum, or pacman. Detailed instructions for various Linux distributions can be found on the Visual Studio Code documentation page.

-Step 3: Set Up Visual Studio Code
Open Visual Studio Code after installation.
Explore the various features and settings of VS Code.
Install extensions for languages and frameworks you will be working with. You can do this by going to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X), searching for extensions, and clicking Install.
-Step 4: Configure VS Code (Optional)
Customize your settings (File > Preferences > Settings) to match your preferences and workflow.
Familiarize yourself with key shortcuts and functionalities to enhance your productivity.
5. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   *Step 1: Install Git
Windows:

Download the Git installer from Git for Windows.
Run the installer and follow the prompts. Ensure you select options like adding Git to the PATH during installation.
macOS:

Git should already be installed on macOS. Open a terminal and type git --version to check if Git is installed. If not, you will be prompted to install it.
Linux:

Use your distribution's package manager to install Git. For Debian/Ubuntu, run:
sql
Copy code
sudo apt-get update
sudo apt-get install git
For Fedora, run:
Copy code
sudo dnf install git
Step 2: Configure Git
Open a terminal or command prompt.
Set your username and email address for Git (replace Your Name and your.email@example.com with your details):
arduino
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Step 3: Create a GitHub Account
Go to GitHub and sign up for an account if you don't have one.
Step 4: Initialize a Git Repository
Create a new directory for your project:

perl
Copy code
mkdir my-project
cd my-project
Initialize a Git repository:

csharp
Copy code
git init
Step 5: Make Your First Commit
Create some files or add existing files to your project directory.

Add the files to the staging area:

csharp
Copy code
git add .
Replace . with specific file names or paths if you want to add only certain files.

Commit the changes:

sql
Copy code
git commit -m "Initial commit"
Replace "Initial commit" with a meaningful commit message describing your changes.

Step 6: Connect Git Repository to GitHub
Go to GitHub and create a new repository (optionally with a README.md file).

Follow the instructions on GitHub to add your local repository to the remote repository on GitHub. For example:

less
Copy code
git remote add origin https://github.com/yourusername/repository-name.git
git branch -M main
git push -u origin main
Replace yourusername with your GitHub username and repository-name with the name of your repository.

6. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
*Step 1: Download Python
Go to the official Python website: Python Downloads.
Download the latest stable version of Python by clicking on the "Download Python x.x.x" button. Choose the appropriate installer for your operating system (Windows, macOS, or Linux).
Step 2: Install Python
Windows:
Run the downloaded installer (e.g., python-3.x.x.exe).
Make sure to check the box "Add Python x.x to PATH" during the installation process.
Click "Install Now" and follow the prompts to complete the installation.
macOS:
Open the downloaded .pkg file.
Follow the installer instructions. Ensure that you have administrative privileges to install software on your system.
Linux:
Open a terminal.
Use the package manager specific to your Linux distribution to install Python. For example, on Ubuntu, you can use:
sql
Copy code
sudo apt update
sudo apt install python3
Replace python3 with python depending on your distribution's naming conventions.
Step 3: Verify Installation
Open a command prompt or terminal.
Check if Python is installed correctly by typing:
css
Copy code
python --version
or
css
Copy code
python3 --version
This command should display the version of Python installed.
Step 4: Install Additional Tools (Optional)
Depending on your project requirements, you may need to install additional tools such as package managers (pip for Python), IDEs (like PyCharm, which includes its own interpreter), or libraries using pip.

Install pip (Python Package Installer):
Download get-pip.py script:

sql
Copy code
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
Install pip:

arduino
Copy code
python get-pip.py
(or python3 get-pip.py if necessary)

Step 5: Set Up Python Environment (Optional)
Consider using virtual environments to manage dependencies and project-specific Python environments:

Copy code
python -m venv myenv
This creates a virtual environment named myenv in the current directory.

Activate the virtual environment:

Windows:
Copy code
myenv\Scripts\activate
macOS/Linux:
bash
Copy code
source myenv/bin/activate
Step 6: Start Coding!

8. Install Package Managers:
   If applicable, install package managers like pip (Python).
   *Step 1: Install Python (if not already installed)
Before installing pip, ensure Python is installed on your system. You can follow the instructions provided earlier to download and install Python from python.org.

Step 2: Verify Python Installation
Open a terminal or command prompt and check if Python is installed correctly by typing:

css
Copy code
python --version
or

css
Copy code
python3 --version
This command should display the version of Python installed. If Python is recognized, proceed to install pip.

Step 3: Install pip
Windows:

If you installed Python using the official installer and selected "Add Python x.x to PATH" during installation, pip should already be installed and accessible from the command prompt or PowerShell.
macOS and Linux:

Open a terminal.

Download the get-pip.py script using curl:

sql
Copy code
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
Alternatively, you can use wget if curl is not available:

arduino
Copy code
wget https://bootstrap.pypa.io/get-pip.py
Install pip by running the script with Python:

arduino
Copy code
python get-pip.py
or

arduino
Copy code
python3 get-pip.py
Step 4: Verify pip Installation
After installation, verify pip by checking its version:

css
Copy code
pip --version
or

css
Copy code
pip3 --version
This command should display the version of pip installed on your system.

Step 5: Using pip to Install Packages

10. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
*Step 1: Download MySQL Installer
Go to the MySQL Community Downloads page: MySQL Community Downloads.
Scroll down to find the "MySQL Installer for Windows" section.
Click on the "Download" button for the MySQL Installer appropriate for your Windows architecture (usually 64-bit).
Step 2: Run MySQL Installer
Once the installer is downloaded, double-click to run it. You may need administrative privileges to install software on your system.

In the installer window, choose "Setup Type". For most users, "Developer Default" is recommended as it installs commonly used products and tools.

Click "Next" to proceed.

Step 3: Select MySQL Products to Install
In the "Select Products and Features" window, select the products you want to install. Typically, you'll want to install at least the MySQL Server.

Select the version you want to install (e.g., MySQL Server 5.7).

Click "Next" to proceed.

Step 4: Configure MySQL Server
In the "Installation" window, click "Execute" to begin the installation process.

Follow the prompts to configure MySQL Server. You may need to set a root password during the installation.

Choose the configuration type. For most cases, "Standalone MySQL Server / Classic MySQL Replication" is suitable.

Click "Next" to proceed through the configuration steps.

Step 5: Finish Installation
Once the installation and configuration are complete, click "Finish" to exit the installer.
Step 6: Verify MySQL Installation
Open a command prompt and navigate to MySQL's bin directory (e.g., C:\Program Files\MySQL\MySQL Server 5.7\bin).

Run the following command to connect to MySQL:

css
Copy code
mysql -u root -p
Enter the root password you set during installation.

If MySQL connects successfully, you'll see the MySQL prompt (mysql>), indicating that MySQL Server is installed and running.

Step 7: Optional - Install MySQL Workbench
MySQL Workbench is a visual tool for database architects, developers, and DBAs. If you also want to install MySQL Workbench:

In the MySQL Installer, select "MySQL Workbench" under "Applications".

Follow the prompts to complete the installation of MySQL Workbench.

12. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
*Step 1: Install Docker
Windows:

Download Docker Desktop for Windows from Docker Hub.
Double-click the installer and follow the prompts to install Docker Desktop.
macOS:

Download Docker Desktop for Mac from Docker Hub.
Double-click the .dmg file and drag the Docker icon to your Applications folder.
Linux:

Follow the installation instructions for Docker Engine on Docker Docs.
Step 2: Verify Docker Installation
Open a terminal or command prompt.
Check if Docker is installed and running:
css
Copy code
docker --version
docker info
Step 3: Create a Dockerfile (Optional but recommended)
Create a Dockerfile in your project directory to define the environment for your application. Here's a basic example for a Python application:

dockerfile
Copy code
# Use an official Python runtime as a parent image
FROM python:3.9

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME World

# Run app.py when the container launches
CMD ["python", "app.py"]
Step 4: Build and Run Docker Container
Build the Docker image from your Dockerfile:

perl
Copy code
docker build -t my-python-app .
Run the Docker container:

arduino
Copy code
docker run -p 4000:80 my-python-app
This command runs the container and maps port 80 of the container to port 4000 on your host machine.

Step 5: Docker Compose (Optional)
For more complex applications with multiple services, use Docker Compose to define and run multi-container Docker applications. Create a docker-compose.yml file in your project directory:

yaml
Copy code
version: '3'
services:
  web:
    build: .
    ports:
      - "4000:80"
Run the application using Docker Compose:

Copy code
docker-compose up
Step 6: Additional Docker Commands
List running containers:

Copy code
docker ps
Stop a running container:

arduino
Copy code
docker stop <container_id>
Remove a container:

bash
Copy code
docker rm <container_id>
Step 7: Virtual Machines (Optional)
If you prefer using virtual machines (VMs) for isolation, tools like VirtualBox, VMware, or Hyper-V (Windows) can be used. Install the VM software, create a VM with your preferred operating system, and configure it as needed.

By using Docker or virtual machines, you can maintain consistent development environments, easily share configurations with team members, and avoid dependency conflicts across different machines. These tools are particularly useful for projects involving multiple dependencies or requiring specific environment setups.

14. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

15. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.
    *Installing Operating System (if necessary)
Selecting Development Tools and IDEs
Installing Required Software

Python Installation

Downloading Python from python.org
Installing Python on Windows, macOS, and Linux
Verifying Python Installation
Git Installation

Downloading Git from git-scm.com
Installing Git on Windows, macOS, and Linux
Configuring Git (setting up username and email)
Creating a GitHub Account and configuring Git with GitHub
MySQL Installation

Downloading MySQL from dev.mysql.com
Installing MySQL on Windows (using MySQL Installer)
Configuring MySQL Server (setting up root password, choosing configuration type)
Verifying MySQL Installation
Visual Studio Code Installation

Downloading Visual Studio Code from code.visualstudio.com
Installing Visual Studio Code on Windows, macOS, and Linux
Configuring Visual Studio Code (optional extensions, settings customization)
Docker Installation (Optional)

Downloading Docker Desktop from docker.com
Installing Docker on Windows, macOS, and Linux
Verifying Docker Installation
Creating Dockerfiles and running Docker containers
Configuring Development Environment

Setting up Virtual Environments (using venv for Python projects)
Integrating Git with Visual Studio Code (optional: configuring SSH keys)
Setting up MySQL Workbench (if using MySQL)
Customizations and Additional Tools

Installing and Configuring Additional Python Packages using pip
Using Docker Compose for multi-container applications (if applicable)
Integrating Other Tools and Plugins into Visual Studio Code (e.g., linters, debuggers)
Troubleshooting and Common Issues

Resolving Python version conflicts
Handling Git errors and authentication issues
MySQL connection problems and troubleshooting tips
Docker container startup failures and debugging techniques

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
