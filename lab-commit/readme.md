# Commit Lab

## Step 1: Create a Commit Without a Message

Try creating a commit without specifying a message using `git commit`. Observe how the CLI switches to an interactive window for entering a message.

## Step 2: Add a File to a Commit

Create a new file `file3.txt` and add some content to it. Then, use `git add` to stage the file. Now, use `git commit --amend` to add the file to the previous commit. Verify that the file is now part of the previous commit.

## Step 3: Debug Commits

Create a new commit with some changes to `file1.txt`. Then, use `git diff` to compare the current commit with the previous one. Observe the differences between the two commits.

## Step 4: Push Commits

Push all your commits to the remote repository. Verify that all your commits are now visible on the remote repository.

## Step 5: Explore Commit History

Use `git log` to explore the commit history of your project. Observe the commit messages, dates, and authors.

## Step 6: Roll Back a Commit (Bonus)

Use `git reset` to roll back to a previous commit. Verify that the changes from the rolled-back commit are no longer visible in your project. This step is a bonus and is not required for the lab.

Remember to push your changes to the remote repository after each step to keep your local and remote repositories in sync.

