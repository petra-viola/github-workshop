# github-workshop
let´s practice github basics for beginners!

This README will introduce you to using basic commands for interacting with Git.

You can look at the bottom of this file, if you have not yet done basic git configuration.

## Setup:

You will need a GitHub profile and a computer with Git and your preferred coding environment.

## Useful commands
`git status `- what is happening
`git clone <url>`- clone an existing repository
`git init` - turn any directory into a repository
`git add <path>`- add changes to staging area
`git commit`- commit staged changes
`git commit -m "My commit message"`
`git push `- push commits to remote repo
`git pull`- pull commits from remote repo
`git checkout –b <branch name>` Create a new branch
`git branch -a –v` - inspect all existing branches
`git log`- view log of changes
`touch filename` to create a file
`mkdir directoryname` to create a directory

## Tasks

1. Clone this repository to your local machine.
2. Use `git status
3. What does `git log` look like?
4. Create a new branch for a feature.
4. What does the output from `git status` look like now?
3. Create a file `touch abc.txt`
5. `add` the file to the staging area
6. How does `git status` look now?
7. `commit` the file to the repository
8. How does `git status` look now?
9. Change the content of the file you created earlier
10. What does `git status` look like now?
11. `add` the file change
12. What does `git status` look like now?
13. Change the file again
14. Make a `commit`
15. What does the `status` look like now? The `log`?
16. Add and commit the newest change

Between each step look at the output of `git status`.

Steps:
Clone the repository to your local machine.
Create a new branch for a feature.
Make changes, commit, and push to the branch.
Open a pull request to merge changes.
Review, discuss, and resolve conflicts if any.
Merge the feature branch into the main branch.

## Git Initial Configuration
1. `git config --global user.name "John Doe"`
1. `git config --global user.email "johndoe@example.com`