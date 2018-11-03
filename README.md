# WELCOME TO GITHUB!! 

## This project to help you make a pull request (PR)

## Instructions-
(adding pictures soon)

If you don't have git on your machine, [install it](https://git-scm.com/downloads).

### Step 1

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

### Step 2


Now clone the forked repo to your machine. Go to your GitHub account, open the forked repo, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal/git bash and run the following git command:

```
git clone "https://github.com/Viz38/First-Pull-Request.git"
```

### Step 3

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```
Now create a branch using the `git checkout` command:
```
git checkout branch-name 
```

For example:
```
git checkout newbranch
```

### Step 4

Now open `Members.md` file in a text editor, save the file.

```
git add Contributors.md
```
Now commit those changes using the `git commit` command:
```
git commit -m "your commit message"
```

### Step 5

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

### Step 6

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

Now submit the pull request.

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Congrats you just created a PR
