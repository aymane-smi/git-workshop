# Push Lab

## Step 1: Push to the Remote Repository

Push all your commits to the remote repository. Verify that all your commits are now visible on the remote repository.

## Step 2: Push to a Specific Branch

Create a new branch `feature/new-feature` and switch to it. Make some changes to `file1.txt` and commit them. Then, push the changes to the remote repository, specifying the branch name.

## Step 3: Push with the `-u` Option

Use `git push -u origin main` to set the upstream tracking information for the branch. Verify that you can now use `git push` and `git pull` without specifying the origin or branch name.

## Step 4: Push to Multiple Origins

Add a new origin `test` to your repository. Push your changes to both `origin` and `test` origins. Verify that your changes are now visible on both remote repositories.

## Step 5: Tag and Push

Create a new tag `v1.0.0` and push it to the remote repository. Verify that the tag is now visible on the remote repository.

## Advanced Steps

### Step 6: Push with Force

Make some changes to `file1.txt` and commit them. Then, use `git push --force` to overwrite the remote branch with your local changes. Verify that the remote branch has been updated.

### Step 7: Push to a Remote Branch with a Different Name

Create a new branch `feature/new-feature` and switch to it. Make some changes to `file1.txt` and commit them. Then, use `git push origin feature/new-feature:main` to push the changes to the remote repository, but with a different branch name. Verify that the changes are now visible on the remote repository.

## Bonus: Forgotten Things

### Bonus Step 1: Push One Commit Only

Use `git push origin <commit_hash>:<branch_name>` to push a single commit to the remote repository. Verify that only the specified commit is pushed.

### Bonus Step 2: Push Tags

Create a new tag `v1.1.0` and push it to the remote repository. Verify that the new tag is now visible on the remote repository.

### Bonus Step 3: Push to a New Repository

Create a new repository on GitHub or GitLab and link it to your local repository. Push your changes to the new repository. Verify that your changes are now visible on the new remote repository.

Remember to push your changes to the remote repository after each step to keep your local and remote repositories in sync.

