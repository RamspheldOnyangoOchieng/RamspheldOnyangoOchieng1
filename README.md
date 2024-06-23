# RamspheldOnyangoOchieng1
1
Download and Create Windows 11 Installation Media
1.	Visit the Official Windows 11 Download Page:
o	Open your web browser and go to the Windows 11 Download Page.
2.	Select "Download Now" Under "Create Windows 11 Installation Media":
o	On the download page, scroll down to the "Create Windows 11 Installation Media" section.
o	Click the "Download now" button. This will download the "Media Creation Tool".
3.	Run the Media Creation Tool:
o	Once the Media Creation Tool has been downloaded, locate the file (usually in your Downloads folder) and double-click it to run it.
o	You might be prompted by User Account Control (UAC) to allow the app to make changes to your device. Click "Yes" to proceed.
4.	Accept the License Terms:
o	Read the license terms and click "Accept" to continue.
5.	Choose "Create Installation Media":
o	On the next screen, select the "Create installation media (USB flash drive, DVD, or ISO file) for another PC" option and click "Next".
6.	Select Language, Edition, and Architecture:
o	The tool will automatically select the recommended options for your PC. If you need to change these, uncheck the "Use the recommended options for this PC" box and select the appropriate Language, Edition, and Architecture (64-bit or 32-bit). Click "Next" when you're ready.
7.	Choose the Media Type:
o	Select "USB flash drive" if you want to create a bootable USB drive. Ensure you have a USB drive with at least 8GB of space.
o	Select "ISO file" if you want to download an ISO file that you can burn to a DVD later. Click "Next".
8.	Follow the On-Screen Instructions:
o	If you chose "USB flash drive", select your USB drive from the list and click "Next". The tool will download Windows 11 and create the installation media on your USB drive.
o	If you chose "ISO file", select the location where you want to save the ISO file and click "Save". Once the download is complete, you can use software like Windows Disc Image Burner or third-party tools like Rufus to burn the ISO to a DVD.
9.	Complete the Process:
o	Once the tool has finished creating the installation media, click "Finish".
Using the Installation Media to Install Windows 11
1.	Insert the USB Drive or DVD into the Target PC:
o	Insert the USB flash drive into a USB port on the target PC or insert the DVD into the DVD drive.
2.	Restart the PC and Boot from the Installation Media:
o	Restart the PC and press the appropriate key to enter the BIOS/UEFI setup (commonly F2, F12, Delete, or Esc) to change the boot order.
o	Set the USB drive or DVD as the primary boot device. Save the changes and exit the BIOS/UEFI setup.
3.	Install Windows 11:
o	The PC should now boot from the installation media. Follow the on-screen instructions to install Windows 11.
o	Select your language, time, and keyboard preferences and click "Next".
o	Click "Install now".
o	Enter your product key if prompted, or click "I don’t have a product key" to enter it later.
o	Accept the license terms and click "Next".
o	Choose the type of installation (Upgrade or Custom). Choose "Custom: Install Windows only (advanced)" for a fresh install.
o	Select the drive where you want to install Windows 11 and click "Next". The installation process will begin


2. Install a Text Editor or Integrated Development Environment (IDE)
Action: Download and Install Visual Studio Code
•	Visit the Visual Studio Code Download Page.
•	Choose the appropriate installer for Windows and download it.
•	Run the installer and follow the on-screen instructions to complete the installation.
•	After installation download all the relevant extensions to the VS IDE.

Using Virtual Machines with VirtualBox
Action: Download and Install VirtualBox
1.	Visit the VirtualBox Download Page:
o	Go to the VirtualBox download page.
2.	Download VirtualBox:
o	Choose the appropriate installer for your operating system (Windows, macOS, or Linux).
o	Additionally, download the VirtualBox Extension Pack.
3.	Run the Installer:
o	Locate the downloaded installer file and double-click to run it.
o	Follow the installation instructions.
o	After installing VirtualBox, install the Extension Pack by double-clicking the downloaded file and following the prompts.
4.	Create a New Virtual Machine:
o	Open VirtualBox and click "New".
o	Enter a name for your virtual machine (e.g., DevEnvironment).
o	Choose the type and version of the operating system you plan to install (e.g., Linux, Ubuntu).
o	Allocate memory (RAM) to the virtual machine (at least 2GB recommended).
o	Create a virtual hard disk (use the default VDI format and dynamically allocated storage).
5.	Install an Operating System:
o	Select the newly created virtual machine and click "Start".
o	You will be prompted to select a startup disk. Choose the ISO file of the operating system you want to install (e.g., Ubuntu ISO file).
o	Follow the installation instructions for the operating system.
6.	Install Guest Additions:
o	Once the operating system is installed and running, go to the VirtualBox menu and select "Devices" > "Insert Guest Additions CD image".
o	Follow the prompts within the virtual machine to install Guest Additions, which provides better integration and performance.
7.	Set Up Your Development Environment:
o	Install necessary development tools and dependencies inside the virtual machine.
o	Set up any required software, such as text editors, IDEs, version control systems, and databases.



1. Install Git
Action: Download and Install Git
•	Download Git: Visit the Git official download page.
•	Run the Installer: Locate the downloaded installer (usually in your Downloads folder) and double-click it to run.
•	Follow the Installation Instructions:
o	Click "Next" on the welcome screen.
o	Select the destination location and click "Next".
o	Choose components to install (default options are usually fine) and click "Next".
o	Select the start menu folder and click "Next".
o	Adjust the PATH environment (recommended: "Git from the command line and also from 3rd-party software") and click "Next".
o	Choose the SSH executable (use the bundled OpenSSH) and click "Next".
o	Select HTTPS transport backend (use the OpenSSL library) and click "Next".
o	Configure line ending conversions (recommended: "Checkout Windows-style, commit Unix-style line endings") and click "Next".
o	Select the terminal emulator (use MinTTY, the default terminal of MSYS2) and click "Next".
o	Configure extra options (default options are usually fine) and click "Next" to install.
o	Click "Finish" after installation is complete.
2. Configure Git
Action: Set Up Your Git Configuration
•	Open Git Bash: After installation, open Git Bash from the Start Menu.
•	Set Your Username:
git config --global user.name "ramspheldonyango"
•	Set Your Email:
git config --global user.email "ramspheldonyango@gmail.com"
•	Verify Configuration:
git config --list
This command will display your configuration settings.
3. Create a GitHub Account
Action: Sign Up for GitHub
•	Visit GitHub: Go to the GitHub website.
•	Sign Up: Click "Sign up" and follow the instructions to create a new account.
4. Initialize a Git Repository
Action: Set Up a Local Git Repository
•	Navigate to Your Project Directory: Open Git Bash and navigate to your project directory:
cd /a/maycohort/PLP
Initialize a New Git Repository:
git init
•	Add Your Project Files:
git add .
•	Make Your First Commit:
git commit -m "Initial commit"
5. Connect to GitHub
Action: Create a Remote Repository and Push Your Code
•	Create a New Repository on GitHub:
o	Log in to GitHub.
o	Click the "+" icon in the top-right corner and select "New repository".
o	Name your repository, add a description, choose visibility (public or private), and click "Create repository".
•	Add the Remote Repository:
git remote add origin https://github.com/ramspheldonyango/RamspheldOnyangoOchieng1
Push Your Code to GitHub:
git push -u origin master



1. Install Python
Action: Download and Install Python
•	Visit the Official Python Website: Go to the Python download page.
•	Download the Installer:
o	Click the "Download Python 3.1.2" button 
o	Save the installer to your computer.
•	Run the Installer:
o	Locate the downloaded installer file and double-click to run it.
o	Ensure you check the option "Add Python to PATH" at the bottom of the first installation screen. This will make Python available in your command prompt.
o	Click "Install Now" to proceed with the default installation settings.
•	Verify Installation:
o	Open a command prompt (you can search for "cmd" in the Start Menu).
o	Type the following command and press Enter:
python --version
o	You should see the version number of Python you installed.
2. Install Pip (Python's Package Manager)
Action: Verify and Install Pip
•	Verify Pip Installation:
o	Pip is included by default with Python installation from version 3.4 onwards. Verify its installation by running:
pip --version
o	If pip is installed, this command will display the version number.
•	Install Pip Manually (if not installed):
o	If pip is not installed, download get-pip.py from here.
o	Run the downloaded script:
python get-pip.py
o	Verify the installation again:
pip --version
3. Install Additional Programming Languages (Optional)
If your project requires other programming languages, follow similar steps for each:
Action: Download and Install Java (example)
•	Visit the Official Java Website: Go to the Java SE Downloads page.
•	Download the Installer: Choose the appropriate installer for your operating system.
•	Run the Installer: Follow the installation instructions.
•	Verify Installation:
o	Open a command prompt.
o	Type the following command and press Enter:
java -version
o	You should see the version number of Java you installed.
Action: Download and Install Node.js (example)
•	Visit the Official Node.js Website: Go to the Node.js download page.
•	Download the Installer: Choose the LTS (Long Term Support) version for stability.
•	Run the Installer: Follow the installation instructions.
•	Verify Installation:
o	Open a command prompt.
o	Type the following commands and press Enter:
node --version
npm --version
o	You should see the version numbers of Node.js and npm (Node's package manager).
4. Configure Your Development Environment
Action: Set Up Virtual Environments (Python example)
•	Install Virtualenv:
pip install virtualenv
•	Create a Virtual Environment:
o	Navigate to your project directory:
cd path/to/your/project
o	Create a virtual environment:
python -m venv venv
•	Activate the Virtual Environment:
o	On Windows:
.\venv\Scripts\activate
5. Install Required Packages and Dependencies
Action: Use Pip to Install Packages (Python example)
•	Create a requirements.txt File:
o	List your project dependencies in a file named requirements.txt in your project directory.
•	Install Packages from requirements.txt:
pip install -r requirements.txt



1. Download MySQL Installer
Action: Download the MySQL Installer
•	Visit the MySQL Download Page: Go to the MySQL download page.
•	Download the Installer: Choose the "MySQL Installer MSI" (usually the recommended option). Click "Download" next to the installer you want.
2. Install MySQL
Action: Run the MySQL Installer
•	Locate and Run the Installer: Once the download is complete, locate the installer file (usually in your Downloads folder) and double-click it to run.
•	Choose Setup Type:
o	You will be presented with several setup types. Choose "Developer Default" to install the MySQL server, MySQL Workbench, and other developer tools.
o	Click "Next" to proceed.
•	Check Requirements: The installer will check for any missing requirements. If any are missing, click "Execute" to install them.
•	Choose Installation Path: You can typically use the default installation path unless you have a specific reason to change it.
•	Install: Click "Execute" to begin the installation process for the selected products.
•	Complete Installation: Once the installation is complete, click "Next".
3. Configure MySQL Server
Action: Configure MySQL Server
•	Select Product Configuration: You will be prompted to configure MySQL Server. Click "Next".
•	High Availability: Choose "Standalone MySQL Server / Classic MySQL Replication" and click "Next".
•	Type and Networking:
o	Choose "Development Computer" for the Config Type.
o	Ensure the port number is set to 3306 (default).
o	Click "Next".
•	Authentication Method: Choose the recommended authentication method ("Use Strong Password Encryption for Authentication") and click "Next".
•	Set Root Password:
o	Enter and confirm a strong password for the MySQL root user.
o	Optionally, you can add additional MySQL user accounts at this stage. Click "Add User" and fill in the details if needed.
o	Click "Next".
•	Windows Service:
o	Ensure "Configure MySQL Server as a Windows Service" is checked.
o	Set the Service Name (default is fine).
o	Optionally, you can have the MySQL Server start at system startup.
o	Click "Next".
•	Apply Configuration: Click "Execute" to apply the configuration settings. Once the configuration is complete, click "Finish".
4. Verify MySQL Installation
Action: Verify MySQL Server
•	Open MySQL Workbench: The MySQL Workbench should have been installed alongside the MySQL Server. Open MySQL Workbench from the Start Menu.
•	Connect to MySQL Server:
o	Click on the "Local instance MySQL" connection (or the connection you created during setup).
o	Enter the root password you set during the installation process.
o	Click "OK" to connect.
•	Verify Connection: Once connected, you should see the MySQL Workbench dashboard. Here you can manage your databases, run SQL queries, and perform other database-related tasks.
5. Create a Database
Action: Create a New Database
•	Open MySQL Workbench: If not already open, launch MySQL Workbench.
•	Connect to MySQL Server: Connect to your MySQL server instance using the root account.
•	Create a Database:
o	Click on the "Schemas" tab on the left-hand side.
o	Right-click in the Schemas pane and select "Create Schema...".
o	Enter a name for your database (e.g., mydatabase).
o	Click "Apply".
o	Review the SQL statement that will be executed and click "Apply" again.
o	Click "Finish" to complete the creation of the database.

