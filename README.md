## Create a new repository on GitHub

1. Go to https://github.com and log in to your account.

2. Click the "New" button in the top right corner of the page.

3. Enter a name for the new repository (e.g., "new-project") and select the options you want.

4. Click the "Create repository" button at the bottom of the page.

## Create a development branch

1. After you have cloned the repository to your computer, navigate to the project directory using the `cd new-project` command.

2. Create a new branch named `development` using the `git checkout -b development` command.

3. You are now in the "development" branch and can start working on new features.

## How to work with the project

1. Before you start working on a new feature, make sure you are in the "development" branch using the `git branch` command. If you are not in this branch, switch to it using the `git checkout development` command.

2. Once you have finalized your new feature, add your changes using the `git add .` command and make a commit describing your changes using the `git commit -m "Description of your commit"` command.

3. You can then submit your changes to GitHub using the `git push origin development` command.

4. After that, you can create a pull request to merge your `development` branch with your `main` branch.

These are the basic steps for working with the project.
