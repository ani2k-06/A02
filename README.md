# A02
Part 1: Directions on Using WebStorm

Step 1:
Download WebStorm from the official JetBrains website: https://www.jetbrains.com/webstorm/download/
Select either option according to your operation system
Press download, then open the application once it has finished downloading. Go through the steps in the installation popup. 

Step 2: Create a New Project
Open WebStorm application. 
Go to File > New > Project from the main menu
Specify the location of the project 
Press Create

Step 3: Set Up Git Integration in WebStorm
Install Git from https://git-scm.com/ 
Press the download option, then select either option according to your operating system
Open the project that you want to put under Git.
Press ⌃ CtrlV to open the VCS Operations Popup and select Enable Version Control Integration.
Choose Git as the version control system and click OK.
Select always add

Step 4: Initialize a Git Repository

Open the directory that you want to put under Git. 
In the main menu, go to VCS | Create Git Repository.
In the open dialog, specify the directory where a new Git repository will be created.

Step 5: Create a New Repository on GitHub
Select in the upper-right corner of any page, then click New Repository.
Type a name for your repository. ...
Choose a repository visibility public/private
Select Initialize this repository with a README.
Click Create repository.

Step 6: Connect WebStorm Project to GitHub
In WebStorm, go to VCS > Git > Push to connect your local repository to your GitHub repository.
Click Define Remote and add the URL for your repository: https://github.com/#enteryourusername/#yourrepsoitoryname.

Step 7: Pushing Code to GitHub
Make changes to your project 
Go to VCS > Git > Commit to stage your changes.
Write a clear commit message like Task: Create Repository.
Click Commit and then go to Push to push the changes to GitHub.

Part 2: Glossary of Terms
**Branch**: A branch is a separate line of development in Git, allowing you to work on different project versions simultaneously.

**Clone**: To clone means to create a copy of a Git repository from a remote source to your local machine.

**Commit**: A commit is a snapshot of your changes in Git. It saves the current state of your project in the repository.

**Fetch**: Fetch retrieves the latest changes from the remote repository but does not apply them to your local code.

**GIT**: Git is a distributed version control system that tracks source code changes during software development.

**GitHub**: GitHub is a web-based platform that hosts Git repositories and facilitates collaboration on code.


**Merge**: Merging integrates changes from different branches into one branch.

**Merge Conflict**: A merge conflict occurs when Git cannot automatically merge code changes because of conflicting edits in the same part of a file.

**Push**: Pushing means sending your local commits to the remote repository on GitHub.

**Pull**: means fetching and merging changes from a remote repository to your local project.

**Remote**: A remote refers to the repository hosted on GitHub or another server.

**Repository**: A repository is where Git stores all a project's files and version history.

https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html
https://git-scm.com/
https://github.com/
https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html#put-existing-project-under-Git
https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories

