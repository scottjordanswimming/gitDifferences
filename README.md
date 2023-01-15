# What Are the Differences Between `git fetch`, `git pull`, and `git push`?

The `git push` command is different from the `git pull` and `git fetch` commands. `git push` sends changes to a remote repository, updating the remote branch with the commits from your local branch.

`git pull` and `git fetch` are similar commands that get changes from a remote repository.

## git fetch

- You use `git fetch` to get changes from a remote repository and add them to a tracking branch, but it does not merge the changes into your local branch.
- To make the changes to your local branch, you must use the `git merge` command after you use `git fetch`.

## git pull

- You use `git pull` to get changes from a remote repository and merge them into your local branch.
- It combines the functionality of `git fetch` and `git merge`.

## git push

- You use `git push` to send changes from your local branch to a remote repository.
- It updates the remote branch with the commits from your local branch.

## In summary:

- `git fetch` gets changes from a remote repository and adds them to a tracking branch. But it doesn't merge them into the local branch. To make the changes to your local branch, you must make a `git merge` command.
- `git pull` gets changes from a remote repository, adds them to a tracking branch, and merges them into the local branch.
- `git push` sends changes to a remote repository.
