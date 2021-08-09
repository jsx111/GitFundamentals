# git commit
The command `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up into what is called a commit.
Commits come with commit messages that are required for each commit. You add a message to a commit by using the `-m` flag followed by a message in quotes.
A commit message_can_be anything, but best practice dictates that you should use that message to indicate changes included in that commit.
For example, if we have an app we're working on where we built te ability to register new accounts, then you might have some variation of the following:
```
git add .
git commit -m "added account registering"
```
Then when viewing the history of a git repository, you can pinpoint where this function was added.
## Resources
-[Git Commit Documentation](https://git-scm.com/docs/git-commit)
[Back to home](../README.md)
