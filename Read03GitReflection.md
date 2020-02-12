[Home](https://bproorda.github.io/learning.journal/)

# Read: 03 - Revisions and the Cloud #

- **Git** 
    - Version control system: maintains "snapshots" of each version of a file
      - Allows you to revert to earlier version as needed
    - Multiple users have access to same code
    - Helps to preven loss of data

- **States in Git**
    - Files in Git travel through states as files are modified
      - use 'git status' in a git file to get status update
      - *Committed* data is securely located in local database
      - *Modified* file has been changed but NOT saved to local database
      - *Staged* Flagged a file’s changed version to be committed in the next     snapshot
- **Setting up Git**
    - Setting Identity
        > git config --global user.name "Jane Smith"

        > git config --global user.email "example@email.com"
    - Settings Check
        >  git config --list
    - Help
        >git help command
- **Setting up Git Repo**
    - Importing 
      1. Switch to project's folder
        > cd test (cd = change directory)
      2. Use git init command
        > git init
      3. perform initial commit
        > git add *.c

        > git add LICENSE

        > git commit -m 'any message here'
    - Cloning
       1. to create a copy in current dir
        > git clone url
       2. to create a copy in another dir
        > git clone url folder
- **Git-Flow** 
    1. Add
      > git add filename
    2. Commit
      > git commit -m “made change x,y,z”
    3. Push
      > git push origin master
