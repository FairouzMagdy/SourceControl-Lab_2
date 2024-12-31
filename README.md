# Readme.md

## Remove a Branch Locally:

* To delete a branch on your local machine:

      git branch -d branch_name
* If the branch has unmerged changes:

      git branch -D branch_name

## Remove a Branch Remotely:

     git push origin --delete branch_name

## List Tags Locally
    git tag
## Delete a Tag Locally
    git tag -d tag_name

## Delete a Tag Remotely:
    git push origin --delete tag_name

## What is Git Rebase?
Git rebase is a command that integrates changes from one branch into another by moving or combining commits. It helps create a cleaner and linear commit history compared to merging.

Example:
Assume you are on the dev branch and want to rebase it into the main branch:

    git checkout dev
    git rebase main

## What is a Pull Request?

A pull request is a request to merge changes from one branch (e.g., dev) into another branch (e.g., main). It allows for code review, collaboration, and discussion before integrating the changes into the main project. Pull requests are created using platforms like GitHub.
## Image

![Cat](cat.jpg)
