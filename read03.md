[Back to Homepage](https://alysondorfman.github.io/reading-notes/)

# Read: 03 - Revisions and the Cloud


## Version Control:
Version control, also known as source control or revision control, is a system or methodology used in software development to manage and track changes to files and code over time. It enables multiple collaborators to work on a project simultaneously, keep a history of changes, and facilitates the ability to revert to previous versions if needed. Version control systems (VCS) help maintain code integrity, improve collaboration, and streamline the development process.

## Cloning in Git:
In Git, cloning refers to the process of creating a copy of a remote Git repository on your local machine. When you clone a Git repository, you download all the files, commit history, and branches from the remote repository to your local system. This allows you to work on the project locally, make changes, and synchronize those changes with the remote repository. 

The command to clone a Git repository is typically:
git clone <repository_url>


## Command to track and stage files:
To track and stage files in Git, you typically use the following commands:
To track a new file:

**git add <filename>**

To stage all changes in the working directory:

**git add .**

The git add command stages the changes you want to include in the next commit. Staging is a crucial step before committing because it allows you to select which changes to include in the commit.

## Command to take a snapshot of your changed files:
To take a snapshot (create a commit) of your changed files in Git, you use the following command:

**git commit -m "Your commit message here"**
This command saves the staged changes as a new commit with a descriptive message that explains the purpose of the commit. Commits are like snapshots of your code at a specific point in time and form a history of changes.

## Command to send your changed files to GitHub:
To send (push) your changed files to a GitHub repository, you typically use the git push command. First, ensure that you have configured your Git repository to point to the correct remote repository (GitHub repository) using the git remote add command if it's not already configured. Then, you can push your changes using:

**git push <remote_name> <branch_name>**

For example, if you want to push your changes to the "main" branch of a remote repository named "origin" (which is the default name for the remote created when you clone a repository from GitHub):

**git push origin main**

This command will upload your committed changes to the specified branch on GitHub, making them available to collaborators and updating the remote repository.
