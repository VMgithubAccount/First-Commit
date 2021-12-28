# First-Commit
This is intended to help practice git commands such as branch, pull and commit.

# Close My First Issue

Practice the workflow by closing your first issue, step by step 💪.

## Step 1. Join our GitHub organisation

`/join-github-org your-github-username`


## Step 2. Fork this repository

Fork this repository by clicking on the fork button on the upper right hand corner of this page.


## Step 3. Clone your forked repository
Now clone the forked repository to your machine.

Go to your GitHub account, open the forked repository, click on the green code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied" (don't include the qoutation marks in the command)
```
This will create a repository in your system

For example:

```
git clone https://github.com/<your-github-username>/close-my-first-issue.git
```

Here you're copying the contents of the close-my-first-issue repository on GitHub to your computer.

(If you don't have git on your machine, please refer to the Odin Project git section.)

## Step 4. Create and checkout a local branch

Change to the repository directory on your computer (if you are not already there):

```
cd close-my-first-issue
```

Now create a branch using the `git checkout` command:

```
git checkout -b new-branch-name
```

For example:

```
git checkout -b add-<your-github-username>
```

## Step 5. Add, stage and commit local changes

Now create a file in your editor, add `## introduce yourself (name)` to the file and then save it.

Upon executing the command `git status`, you'll see there are changes.

Stage those changes with the `git add` command:

```
git add profiles/<your-github-username>.md
```

And commit those changes using the `git commit` command:

```
git commit -m "add <your-github-username>"
```

## Step 6. Push local commits to remote branch

Push your changes using the command `git push`:

```
git push origin add-<your-github-username>
```

## Step 7. Open a pull request



If you go to your repository on GitHub, you'll see a `Compare & pull request` button.

Click on that button to start creating a pull request.


Then organizers will then be notified of your pull request and either approve and merge your updates, or request changes.

