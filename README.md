# PLPBasicGitAssignment

1. Repository Setup
Log in to your GitHub account:
Open your web browser and go to GitHub.
Enter your username and password to log in to your GitHub account.
Create a new repository:
Click on the "+" icon in the top right corner of the page, next to your profile picture.
Select "New repository" from the dropdown menu.
Set up the new repository:
In the "Repository name" field, enter 'PLPBasicGitAssignment'.
Choose the visibility of the repository: either Public or Private.
Check the box that says 'Initialize this repository with a README'
Click on the Create repository button at the bottom of the page.

2. Local Setup
Open File Explorer.
Navigate to the location where you want to create the new folder.
Right-click in the directory and select New -> Folder.
Name the folder PLPBasicGitAssignment.
Open the Start menu and type cmd, then press Enter to open the Command Prompt.
Navigate to the folder you created using the cd command:
"cd C:\Users\YourUsername\Documents\PLPBasicGitAssignment"


3. Initialize Git Repository: git init
After running git init, you should see a message like this: Initialized empty Git repository in /path/to/your/PLPBasicGitAssignment/.git/


4. Connecting to GitHub:
Copy the GitHub Repository URL:
Go to your GitHub account and navigate to the PLPBasicGitAssignment repository you created.
Click on the Code button and copy the repository URL. It will look something like https://github.com/YourUsername/PLPBasicGitAssignment.git.
Add the Remote Repository:
git remote add origin https://github.com/YourUsername/PLPBasicGitAssignment.git
Confirmation
To verify that the remote repository has been added correctly, you can use the git remote -v command to list the current remotes:
Confirmation
git remote -v
You should see output similar to:
origin  https://github.com/YourUsername/PLPBasicGitAssignment.git (fetch)
origin  https://github.com/YourUsername/PLPBasicGitAssignment.git (push)


5. Making Changes
Open File Explorer.
Navigate to your PLPBasicGitAssignment folder.
Right-click inside the folder, select New, and then Text Document.
Name the file hello.txt.
Open hello.txt by double-clicking it. It should open in Notepad.
Type the message: Hello, Git!
Save the file (File -> Save) and close Notepad
Add the File to the Staging Area:
Add your hello.txt file to the staging area:

6. Committing Changes:
git add hello.txt
Commit the Changes:
Commit your changes with a message:
git commit -m "Add hello.txt with a greeting message"

7. Push the Changes to GitHub:
Push the committed changes to your GitHub repository:

8. git push -u origin main

7. Confirmation
After running git push -u origin main, you should see output indicating that the changes have been pushed to GitHub. You can confirm by visiting your GitHub repository page. The hello.txt file with the message "Hello, Git!" should be visible in the repository



