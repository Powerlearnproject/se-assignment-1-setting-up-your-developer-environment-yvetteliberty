[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281843&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

**STEPS TO DOWNLOAD AND INSTALL WINDOWS 11 OPERATING SYSTEM**
a. First I  Check if your computer meets the minimum system requirements for Windows 11. These requirements include a compatible processor, at least 4GB of RAM, and sufficient storage space.

b. i Make sure the current operating system is up to date with the latest updates and patches.

c. Then I use the official Microsoft website to dowdload the windows 11 operating system.

d. Look for the option to download Windows 11. It was   prominently displayed on  under a specific section related to operating systems.

e.  Click on the "Download" button and follow The instructions provided by Microsoft.

f. Once I completed these steps, a download  begin in the background, and i was  able to monitor its progress through  download manager.

g. After downloading is complete, locate the downloaded file (usually in  Downloads folder) and double-click on it to start installing Windows 11.

h. Followed  installation prompts that appear on screen, including accepting license terms and choosing installation options such as language preferences and partitioning choices.

i. Finally, allow some time for Windows 11 installation process completes depending on the computer speed.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

**STEP TO DOWNLOAD AND INSTALL VISUAL STUDIO CODE(IDE)**
The text Editor (Visual Studio code)

To download and install Visual Studio Code, I followed these steps:

a. Go to the official Visual Studio Code website at https://code.visualstudio.com.

b. Click on the "Download for Windows" button .

c. The waitfor  the download to complete, locate the installation file in the  Download folder.

d. Double-click on the installation file to start the installation process.
e.  prompted with security warnings during installation; to  click "Yes" or "Allow" to proceed.

f.I  Choose  desired setup type (User Installer vs System Installer). The User Installer installs Visual Studio Code only for your user account, while the System Installer installs it for all users on your computer (requires administrative privileges).

G. Select a  default location suggested by the installer.

H.  I Choose  to add context menu options (such as opening folders with VS Code) and create desktop shortcuts during installation.

I. Click on "Next" to begin installing Visual Studio Code .

J. Once installed, launch Visual Studio Code by double-clicking its icon on The desktop / search for it in  Start Menu/Start Screen/.

Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

**STEPS INSTALLING GIT AND GITHUB ACCOUNT**

a.visit the https://github.com to create an account with Github.
b. Creat an account by sign in  with my gmail address.
c. Open  web browser and go to the official Git website at https://git-scm.com/.

d.  I Look for the download link on the homepage and click on it.

e . I was  directed to a page where I can select operating system (Windows) and download the appropriate installer.

f. Once the installer has finished downloading, locate it in the  downloads folder .

g. Double-click on the installer file to begin the installation process.

h. Follow the instructions in the installation wizard, such as choosing an installation location and selecting components to install.

i. i Make sure to check "Git Bash Here" option during installation.

J. Once the installation is complete,  I open a terminal or command prompt and type `git --version`(2.45.2) to verify that Git has been successfully installed.
K.configure my username with :git config --global user.name ,and email address,change directory ,creat directory by using "mk dir etc.


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

 install Python on Windows 11, I,followed the following  instructions:
   
  I Opened a web browser and go to the official Python website at https://www.python.org/downloads/windows/.
   - Click on the "Download" button for the latest version of Python for Windows.
a. **Download Python Installer:**
b. **Run the Installer:**

 Once the installer is downloaded, locate the file (e.g., `python-3.9.7-amd64.exe`) in my Downloads folder .
then  Double-click on the installer file to run it.

c. **Configure Installation:**
   
 In the installation window, i ensure that I check the box that says "Add Python 3.to PATH" before clicking "Install Now."
     This  add Python to my system PATH environment variable so that it can be run from any command prompt.

d. **Installation Progress:**

    The installer  begin installing Python on the computer.
    You may see a User Account Control dialog asking if you want to allow this app to make changes to your device; i click "Yes". 

e. **Completing Installation:**

    Once the installation was complete:
    I click on “Close” to exit the installer.
     To verify that Python has been installed correctly,I  open Command Prompt and type `python --version` ,Then I

f. Check if pip (Python package installer) is installed by running the following command:
```
pip --version and the pip was installed with version (pip 24.0)
```

 Once pip is installed, run the following command to install numpy:
```
pip install numpy
pip install numpy
```
h.Wait for the installation process to complete.

i. Open Python IDLE.

j. In the IDLE shell, enter `import numpy` and press Enter.



5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   **To install package managers in Python, you can follow these step-by-step instructions:**

1. **Open Command Prompt:**

   Open the Command Prompt on  Windows 11 computer.  pressing the "Windows" key, typing "Command Prompt," and selecting the Command Prompt app from the search results.

2. **Check Python Installation:**

   Before installing a package manager, i verify that Python is installed correctly by typing `python --version` in the command prompt and pressing Enter. You should see a version number displayed, indicating that Python is installed.

3. **Install pip:**

   Pip is the default package manager for Python, and it comes pre-installed with most Python distributions. To check if pip is already installed or to upgrade it to the latest version,i  run this command:

   ```
   python -m ensurepip --upgrade
   ```

4. **Verify pip Installation:**

   After running the previous command successfully, i verify that pip is installed correctly by typing `pip --version` in the command prompt and pressing Enter.  version number displayed, indicating that pip is installed.

5. **Install Other Package Managers (Optional):**
   
     To use alternative package managers like conda or easy_install alongside pip, you can install them using pip itself.
    
     To install conda (Anaconda), run this command:
    
      python -m pip install conda
      
    To install easy_install (Setuptools), run this command:
    
      python -m pip install setuptools
      

6. **Verify Other Package Managers Installation (Optional):**

    After installing other package managers using pip as explained above:
    
    For conda: Type `conda --version` in the command prompt and press Enter.
  
    For easy_install: Type `easy_install --version` in the command prompt and press Enter.
  
       These commands will display version numbers if conda or easy_install are installed correctly.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

  **STEP-BY -STEP WAY OF DOWNLOADING MYSQL.**
  
a. visit the official site which https://dev.mysql.com/downloads.Open the preferred web browser and navigate to the official MySQL website. Now, Simple click on second download button.


b. Go to the Downloads Section
On the MySQL homepage, Click on the ” No thanks, just start my download” link to proceed MySql downloading.

c.Run the Installer
After MySQL downloading MySQL.exe file ,    go to  Downloads folder, find the file, and double-click to run the installer.
d.Choose Setup Type
The installer will instruct  to choose the setup type. For most users, the “Developer Default” but i choose the server only  Click “Next” to proceed.
e. Check Requirements
f.MySQL Downloading
 in the download section, click “Execute” to start downloading the components . Wait a few minutes until all items show tick marks, indicating completion, before moving forward.
 g. MySqL Installation
 the downloaded components was installed. Click “Execute” to start the installation process. MySQL was installed on the  Windows system. I click Next to proceed.
 h. Navigate to Few Configuration Pages
Proceed to “Product Configuration” > “Type and Networking” > “Authentication Method” Pages by clicking the “Next” button.
i.Create MySQL Accounts
Create a password for the MySQL root user. Ensure it’s strong and memorable. Click “Next” to proceed.

j.Connect To Server
Enter the root password, click Check.  it says “Connection succeed,” you’ve successfully connected to the server.

k.Complete Installation
the installation was complete, click “Finish.” .

**Done**















7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

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
