# Rebase Lab

## Step 1: Create a New Branch

Create a new branch `feature/new-feature` from the `main` branch using `git checkout -b feature/new-feature`. Make some changes to `file1.txt` and commit them.

## Step 2: Rebase the Branch

Switch back to the `main` branch using `git checkout main`. Then, use `git rebase feature/new-feature` to rebase the `feature/new-feature` branch onto `main`. If there are any conflicts, resolve them and use `git rebase --continue` to continue the rebase process.

## Step 3: Verify the Rebase

Use `git log` to verify that the rebase has been successful and all changes from `feature/new-feature` are now part of the `main` branch.

## Step 4: Push the Rebased Changes

Push the rebased changes to the remote repository using `git push origin main`.

## Step 5: Delete the Rebased Branch

Delete the `feature/new-feature` branch using `git branch -d feature/new-feature`.

## Bonus: Rebase with --interactive

Use `git rebase -i feature/new-feature` to rebase the branch interactively. This allows you to reorder, squash, or delete commits before rebasing.

Remember to push your changes to the remote repository after each step to keep your local and remote repositories in sync.

