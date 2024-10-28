# Merge Lab

## Step 1: Create a New Branch

Create a new branch `feature/new-feature` from the `main` branch using `git checkout -b feature/new-feature`. Make some changes to `file1.txt` and commit them.

## Step 2: Merge the Branch

Switch back to the `main` branch using `git checkout main`. Then, use `git merge feature/new-feature` to merge the `feature/new-feature` branch into `main`. If there are any conflicts, resolve them and use `git merge --continue` to continue the merge process.

## Step 3: Verify the Merge

Use `git log` to verify that the merge has been successful and all changes from `feature/new-feature` are now part of the `main` branch.

## Step 4: Push the Merged Changes

Push the merged changes to the remote repository using `git push origin main`.

## Step 5: Delete the Merged Branch

Delete the `feature/new-feature` branch using `git branch -d feature/new-feature`.

## Bonus: Merge with --no-commit

Use `git merge --no-commit feature/new-feature` to merge the branch without automatically committing the merge. This allows you to review the merge before committing it.

## Bonus: Merge with --squash

Use `git merge --squash feature/new-feature` to merge the branch and squash all the commits into a single commit. This can be useful for simplifying the commit history.

Remember to push your changes to the remote repository after each step to keep your local and remote repositories in sync.
