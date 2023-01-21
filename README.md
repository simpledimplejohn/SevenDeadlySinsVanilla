# Basic Nodejs front end
I am writing this documentation for myself to get practice setting up a nodejs front end.  Something I can have in case I step away from this platform for a while.

## github setup

echo "# SevenDeadlySinsVanilla" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:simpledimplejohn/SevenDeadlySinsVanilla.git
git push -u origin main

# Node.js Setup
- How to do a basic Node.js front end setup with all of the files
## Setting up node.js
- make sure you have homebrew installed and working (brew -v)
- make sure you have npm installed (npm -v)
- make sure you have nvm installed (node version manager) (nvm -v) check that you have the correct version of node.js
- Navagate to the folder you want to install this in
    - run npm init
    - once you have your basic files run
    - run `npm install`

## Setup the git repo
- add your basic `gitingnore file` in the root directory named `.gitignore`
    ```
    node_modules/
    .DS_Store
    dist/
    coverage/
    .env
    ```
- 

# MISS NOTES 

## Notes on using github

- `git log --oneline` to get out `control z`
- reset to previous commit and delete current commit (not pushed)
    `--hard HEAD^`
- previous commit to new branch
    `git checkout -b old-state 4879e01` old-state is the new branch, then commit id
- Fix previous commit message not pushed
    `git commit --amend -m "amended message"`
- Create New Branch copy data over
    `git checkout -b new-branch-name`


- Merge to main
    `git checkout main`
    `git pull origin main`
    `git merge oldBranch`
    `git push origin main`

## CRON NOTES
- Running a cron job on your local mac machine
    `crontab -1` lists
    `crontab -e` edit
    `mail` will list all new cron alerts using the `echo` command
        - `mail` `d 1-11567` to delete mail 1 through 11567
        - `q` to quit

## VI editor notes
- starts in command mode--you can do the following here
    - in   `command mode` you can do the following
        - `i` insert mode before cursor
        - `o` insert mode starts a new line
        - `:wq` quit with saving
        - `q!` quit with saving
- `i` to go into insert mode `exp key` to go back to command mode
    - in `insert mode` you can do the following:
        - `ESC` to get out

