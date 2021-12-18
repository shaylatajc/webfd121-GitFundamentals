# git commit

The command `git commit` will take all the tracked changes (Items added with [git add](./ADD.md)) and package them up in what is called a commit. 

Commits come with commit messages that are reguired for each commit. You add a message to a commit command using the `-m` flag followed by a message in quotes.
A commit message _can_ be anything, but best practice is to use the message to highlight the changes included in the commit.

For example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:
```
git add .
git commit -m "Added register Functionality"
```
Then when viewing the git repository, you can pinpoint where the registation functionality was added. 

## Resource
 - [Git Commit Documentation](https://git-scm/docs/git-commit)
 
 ---

 [Back to home](../README.md)
 