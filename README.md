# A03

## Installing WebStorm
1. Create a student account using https://www.jetbrains.com/shop/eform/students
2. Download WebStorm from https://www.jetbrains.com/webstorm/download/#section=windows

## Create a GitHub Account
1. Go to https://github.com/join
2. Create an account

## Install Git
1. Download Git from https://git-scm.com/downloads
2. Run the installer

## Connect WebStorm to Git and GitHub
1. Open WebStorm
2. Create an empty project
3. Hit Control-Alt-S
4. Go to Version Control > Git
5. If it has auto-detected Git, click Test to make sure it works
6. If it has not auto-detected Git, find the executable for Git in C:\Program Files\Git\cmd\git.exe
7. Under Version Control > GitHub, add your account

## Create a New File in Your Project
1. Right click the project folder
2. Click New > HTML File
3. Enter a name and select HTML5 File
4. Modify the page title to your liking

## Enable Version Control on Your Project
1. Click VCS > Enable Version Control Integration...
2. Make sure the box says Git and hit OK

## First Commit and Push
1. Right click on the index.html file in the project explorer (the file should be red if you correctly set up version control)
2. Got to Git > Add (the file should turn green and pop up with a green highlight in the bottom right)
3. Hit Control+K or click the green check mark near the bottom left to open the commit dialogue.
4. Enter a commit message (Ex: "Added Hello World index.html")
5. Create a new repository on GitHub by navigating to https://github.com/ and clicking the green "New" button next to Repositories
6. Name it and create the repository WITHOUT a readme or .gitignore
7. Hit the clone or download button
8. Copy the .git link presented
9. Hit Control+Shift+K to open the Push dialogue
10. Click "define remote" on the dialogue that pops up
11. (Optional) change the name of the remote
12. Paste the .git link in the URL box
13. Hit OK
14. Click Push

##Definitions
Git - Local version control system

Github - Online storage and viewer for Git repositories (online version control)

Repository - Tracks all changes made to files in your project, building a history over time

Clone - Creating a copy of a repository

Commit - Confirming changes to a branch in a repository, bundles changes together

Push - Take changes from your local (on your computer) repository and upload them to a remote host (GitHub in our case)

Pull - Download changes and history from a remote host (GitHub in our case) and updates your local repository

Branch - Separate version of the same project, can edit it freely of modifying the master/other branches. Can be merged into other branches later.

Merge - Take a branch and combine its changes and history with another branch

Merge Conflict - When there are differences in a file's changes when attempting to merge two branches a merge conflict happens. This must be resolved before the merge can complete.

Fetch - Git gathers any commits from the target branch that do not exist in your current branch and stores them in your local repository. However, it does not merge them with your current branch.

Remote - Remote repositories are versions of your project that are hosted on the Internet or network somewhere. Usually this will be origin when using GitHub by default. 
