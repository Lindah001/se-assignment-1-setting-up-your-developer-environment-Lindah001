[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15275735&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   My laptop doesnt meet the requirements to install windows 11 so  I installed windows 10

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   After visiting their website,I choosed the VS code compartible with windows and downloaded it
   ![alt text](<Screenshot (7).png>)
   I then ran the download installer,followed installation instructions and choosed installation location, later on I selected additional tasks ie creating a desktop icon 
   ![alt text](<Screenshot (11).png>)
   Launch and install recommendated extension like liveserver,python
   ![alt text](<Screenshot (12).png>)
   Currently am using it.
   ![alt text](<Screenshot (3)-1.png>)

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   Download git from their website
   ![alt text](<Screenshot (13)-1.png>)
   I then ran the installer and followed the instructions
   ![alt text](<Screenshot (5).png>)
   first commit
   https://github.com/Lindah001/assignment123.git

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  ![alt text](<Screenshot (6).png>)
  Visit python official website and download python.
  Double-click the executable file.
  Select Customize installation and proceed.
  Click on the Add Path check box, it will set the Python path automatically.
  Install.
  Run python -m pip --version.

5. Install Package Managers:

   If applicable, install package managers like pip (Python).
   Download "get -pip.py" script
   Install pip using script.
   Navigate the directory where the file is found
   Run python get -pip.pyto run
   Verify pip installation by pip --version
   Use pip

6. Configure a Database (MySQL):

   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   Download MySQL installer.
   Run the installer,double click to run.
   Set up MySQL installer.
   Choose custom as set up type then click next
   Next is product and features,choose MySQL server
   Set up a password you can remember
   Complete the installation by clicking finish.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

   I opted for docker,here are the steps.
   Install docker by going to docker official website
   Create a docker file to define the environment your application needs.
   Build a docker image,navigate to the directory containing docker file and run.
   Start a container based on the image and run using the command
               docker run -p 3000:3000 lin.nodejs -app 
   The command maps port 3000 of my local machine to that of the container.            

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
    
    Open visual studio,on your left hand side you will find extension.
    A search bar wil be available,search for the extension you need and click on install.
    Extensions include dart,live server,pip manager,python
    ![alt text](<Screenshot (14).png>)

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    Challenges:
    My laptop never meet the requirments to install windows 11
    Installing docker was kind off tricky but I watched on youtube and finally managed.
    

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
