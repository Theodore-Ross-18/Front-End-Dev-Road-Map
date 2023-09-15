# **GIT**

> A Crash Course by Brad Traversy

## What is GIT?

### Version Control System (VCS) for tracking changes in computer files

- ### Distributed version control

- ### Coordinates work between multiple developers

- ### Who made what changes and when

- ### Revert back at any time

- ### Local & remote repos

## Concepts of Git

- ### Keeps track of code history

- ### Takes "snapshots" of your files

- ### You decide when to take a snapshot by making a "commit"

- ### You can visit any snapshot at any time

- ### You can stage files before committing

## Basic Commands

- ### `$ git init` - Initialize Local Git Repository

- ### `$ git add <file>` - Add Files(s) To Index

- ### `$ git status` - Check Status of Working Tree

- ### `$ git commit` - Commit Changes in Index

- ### `$ git push` - Push to Remote Repository

- ### `$ git pull` - Pull Latest from Remote Repository

- ### `$ git clone` - Clone Repository into a New Directory

## Installing GIT

- ### Windows - http://git-scm.com/download/win

- ### Mac - http://git-scm.com/download/mac

- ### Linux (Debian) - `$ sudo apt-get install git`

- ### Linux (Fedora) - `$ sudo yum install git`

## Git Bash

- ### Bash & CMD (Check Version): `git --version`

> Creating a project locally

- ### Inside the desktop create a folder: `<folder>` & Open the folder through Git Bash (Right-Click)

- ### Inside the folder create a file through Git Bash: `touch <filename>.<extension>` :

    - ### `touch index.html`
    - ### `touch app.js`
    - ### `touch style.css`
    - ### `touch log.txt`

- ### Inside the Code Editor (VS Code or Atom): `Add the folder as a project`

    -  ### Edit the files to make some changes

- ### Initialize a folder as a Git repository: `git init`

    - ### This prompt will create a `.git` folder in the directory

## Applying Git Commands (Git Bash)

> Do this first

- ### User: `git config --global user.name 'your name'`

- ### Email: `git config --global user.email 'your email'`

## Adding a file to a git repository

- ### Add: `git add <filename>.<extension>`
    > Example: `git add index.html`

- ### Check Staging Area: `git status`
    > This will provide the information on what file is ready for changes to commit inside the staging area and what files are untracked.

    - ### To unstage a certain file: `git rm --cached <filename>.<extension>`
        > Example: `git rm --cached index.html`

- ### Another Ways to add a file to staging area:

    - ### Add Specific Files: `git add *.<file extension>`
        > Example: `git add *.html` - This will add all files that has an html extension to the staging area.

    - ### Add All Files: `git add .`
        > This will add all files inside the folder to the staging area.

## Commit








