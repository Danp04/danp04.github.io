---
layout: default
title: GitHub basics
nav_order: 4
has_children: false
---

GitHub basics

# How to start working with Git?
## Definitions
### What is Git?
Git is an open source version control system which tracks all the changes you made in your projects. Git has a remote repository which is stored on a server and a local repository which is stored on a private computer.


### What is GitHub?
GitHub is a website and Internet service which allow to store your projects on a server - in your own repository, make changes, and collaborate with others.


### What is GitHub Desktop Client?
It is a software which you can use it to manage your Git repositories locally on your computer without using the command line on Internet browser.

# Installation
To start working with GitHub, perform the following actions:
1. Create your account on GitHub: [Create Account](https://github.com/) and verify your e-mail address.
2. Install GitHub Desktop Client on your computer: [GitHub Desktop Client](https://desktop.github.com/).


# Authentication
After you install GitHub Desktop, you can synchronize it with your own account on GitHub and configure it. If you selected two-factor authentication for GitHub you can generate your authentication code either from mobile message or an e-mail and verify your account.
Further information you can find here: [docs](https://docs.github.com/en/github/authenticating-to-github/about-authentication-to-github).


# How to create a new repository on GitHub Desktop?
1. Open GitHub Desktop on your computer. 
2. On a "Let's get started!" panel select **Create a New Repository on your hard drive**.
3. Name your repository and set its location on your computer. 

>It is recommended to use the shortest path, for example C: Git, as the repository is to be created inside the folder you selected for your local path. 

4. Select:

* **Initialize this repository with a README**.
* **None** in the **Git Ignore** and **License** menu.

5. As you fill in the blanks, select Create Repository.


# How to publish your repository to GitHub?
As you create your first repository on GitHub Desktop, keep in mind that it only exists on your computer. In order to publish it to the server (GitHub), perform the following actions:

1. In the menu bar of GitHub Desktop select **Publish repository**. **Name** and **Description** are the same as you wrote while creating the new repository.
2. For the needs of the project and our studies, mark **keep this code private**.
3. Select **Publish Repository**.
4. You can open your files in the repository on GitHub directly from GitHub Desktop.

# Managing access to your repository

In order to invite a collaborator to your repository:

1. Select **Settings** and **Manage access**.
2. Invite your Vistula educators typing the user’s name account: martab0, db4rr.
3. Wait for acceptance.

# The Git’s important commands

In the table below you can find useful commands being used on GitHub and GitHub Desktop. Familiarize with them to properly manage your workflow, add content, or make changes.


| Action | Command |GitHub Desktop Client
| --| ----------- |----------------------
| Create a project|git init [project]|File > New repository|
| Add a project to the remote server|git remote add origin [url]|Publish your repository to GitHub|
| Retrieve the project from the server|git clone [url]|File > Clone a repository|
| Add a file|git add [file]|Create or copy file|
| Delete the file|git rm [file]|Delete file|
| Save changes|get stash|Automatic|
| Approve changes|git commit -m"[description]"|Commit to [branch name]|
| Upload changes to the server|git push|Push origin|
| Retrieve changes from the server|git pull |Fetch origin+ Pull origin|
| Current status|git status|Changes/History/Current branch|
| No tracking via git|Add to .gitignore|Add to .gitignore|