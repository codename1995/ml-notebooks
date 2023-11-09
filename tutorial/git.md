# Git Basics: A Simple Manual

## Introduction

Git is a version control system that helps you manage your code and collaborate with others. This manual will cover some basic Git commands to get you started.

## Table of Contents

1. **Setting Up Git**
   - Install Git on your computer. You can download it from [here](https://git-scm.com/downloads) and follow the installation instructions.

2. **Configuring Git**
   - After installation, set your name and email using the following commands:
     ```
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     ```

3. **Creating a New Repository**

   - **Local Repository**: To start a new project with Git, create a new directory and navigate into it. Then run:
     ```
     git init
     ```
    > This step is better to be done on GitHub.
   
   - **Clone Repository**: To work on an existing project, clone it from a remote repository using:
     ```
     git clone <remote_url>
     ```
     
   - **Switching Branches**: Create and switch to a new branch with:
     ```
     git checkout -b <branch_name>
     ```

4. **Basic Commands**


   - **Adding Files**: Stage changes for commit using:
     ```
     git add <filename>
     ```

   - **Committing Changes**: Save staged changes to your local repository with:
     ```
     git commit -m "Your commit message"
     ```
    Use `-a` to tell the command to automatically stage files that have been modified and deleted. So, you don't need to use `git add` anymore. For new files, `git add` should be used.
     ```
     git commit -am "Your commit message"
     ```

5. **Collaboration**

   - **Pushing Changes**: Upload your local commits to a remote repository using:
     ```
     git push origin <branch_name>
     ```

   - **Pulling Changes**: Retrieve and merge changes from the remote repository with:
     ```
     git pull origin <branch_name>
     ```
    
6. **View Commands**

   - **Checking Status**: To see which files are staged or modified, use:
     ```
     git status
     ```

   - **Viewing Commit History**: See a list of past commits using:
     ```
     git log
     ```


## Conclusion

This manual covers the fundamental Git commands you'll need to get started. Remember, practice makes perfect! As you become more comfortable with Git, you can explore additional features and commands to enhance your workflow. Happy coding!

> Desclaimer: This manual gnerated by ChatGPT. I modified a bit.

![Alt text](../assets/image.png)