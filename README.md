# `git fetch`, `git pull`, and `git push`: A Comparison

## git fetch

- Use `git fetch` to get changes from a remote repository and add them to a [tracking branch](https://stackoverflow.com/questions/4693588/what-is-a-tracking-branch).
- To make the changes to your local branch, you must use the [`git merge` command](https://www.atlassian.com/git/tutorials/using-branches/git-merge).
- Syntax: `git fetch <remote> <branch>`

## git pull

- Use `git pull` to get changes from a [remote repository](https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories) and merge them into your local branch.
- It combines the functionality of `git fetch` and `git merge`.
- Syntax: `git pull <remote> <branch>`

## git push

- Use `git push` to send changes from your local branch to a remote repository.
- It updates the remote branch with the commits from your local branch.
- Syntax: `git push <remote> <branch>`

## When to use each command

- Use `git fetch` when you want to review the changes before you merge them into your local branch.
- Use `git pull` when you want to update your local branch with the latest changes from the remote repository.
- Use `git push` when you want to send your changes to a remote repository.
