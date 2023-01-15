# What Are the Differences Between `git push`, `git pull`, and `git fetch`?

The `git push` command is different from the `git pull` and `git fetch` commands. `git push` sends changes to a remote repository, updating the remote branch with the commits from your local branch.

`git pull` and `git fetch` are similar commands that get changes from a remote repository. However, there are some differences between the two:

## Difference Between `git pull` and `git fetch`

- `git fetch` gets changes from a remote repository, and adds the changes into a tracking branch. But, it does not merge those changes into your local branch.
- `git pull` gets changes from the remote repository, adds the changes into a tracking branch, and then merges them into your local branch. You use this command when you want to use one command to update your local branch with the latest changes from the remote repository. `git pull` combines the functionality of git fetch and git merge.
You might use `git fetch` instead of git pull if you want to review the changes before you merge them. Or you might use git fetch if you want to make sure you understand the changes before you merge them.

## In summary:

- `git push` sends changes to a remote repository.
- `git fetch` gets changes from a remote repository and adds them to a tracking branch. But it doesn't merge them into the local branch. To make the changes to your local branch, you must make a `git merge` command.
- `git pull` gets changes from a remote repository, adds them to a tracking branch, and merges them into the local branch.
