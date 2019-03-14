# WELCOME TO GITHUB!! 

## This project to help you make a pull request (PR)

## Instructions-

If you don't have git on your machine, [install it](https://git-scm.com/downloads).

### Optional Step

Configure Git Bash
```
 git config --global user.email "<your email>"
 git config --global user.user "<github username>"
```
Use you email and username as given on your github account

### Step 1

Fork <a href="https://github.com/Viz38/First-Pull-Request" target="_blank">THIS</a> repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.
![fork](https://raw.githubusercontent.com/Viz38/First-Pull-Request/master/Assets/Fork.bmp)

### Step 2


Now clone the forked repo to your machine. Go to your GitHub account, open the forked repo, click on the clone button and then click the *copy to clipboard* icon.
![clone](https://raw.githubusercontent.com/Viz38/First-Pull-Request/master/Assets/Clone.bmp)

### Step 3

Open a terminal/git bash and run the following git command:

```
git clone "https://github.com/Viz38/First-Pull-Request.git"
```

### Step 4

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```
Now create a branch using the `git branch` command and change to new branch using `git checkout` command:
```
git branch branch-name 
git checkout branch-name
```

For example:
```
git branch newbranch
git checkout newbranch
```

### Step 5

Now open `Members.md` file in a text editor, Add yourself as given.

```
vi Memberrs.md
```
Save and exit by pressing [ESC] key and type in `:wq`

### Step 6

Add the changes you've made to git by hitting the following command
```
git add Memvers.md
```

Now commit those changes using the `git commit` command:
```
git commit -m "your commit message"
```

### Step 7

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

### Step 8

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.
![C&P](https://raw.githubusercontent.com/Viz38/First-Pull-Request/master/Assets/Pull.bmp)

### Step 9

Now submit the pull request.
![CPR](https://raw.githubusercontent.com/Viz38/First-Pull-Request/master/Assets/Create%20PR.bmp)

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

[Click Here](https://github.com/glugpace) for more projects. 🌟🌟 

## Congrats you just created a PR
