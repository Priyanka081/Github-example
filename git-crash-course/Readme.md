## Git hidden folder
There is a hidden folder called '.git' which tells you that our project is a git repo
if we want to create a git repo a new projt we can create the folder and then initialize that repo using `git init`
```
mkdir /workspaces/tmp/new-projt
cd /workspaces/tmp/new-projt
git init
touch Readme.md
code Readme.md
git status 
git add Readme.md

# Make changes to Readme.md
git commit -m "add readme file"




## cloning
we can clone three ways: HTTPS, SSH, Github CLI
since we are using codespaces we'll a create a temporary directory in our workspace
```sh
mkdir /workspaces/tmp
cd /workspaces/tmp
```

### HTTPS
```sh
git clone https://github.com/Priyanka081/Github-example.git
cd Github-example
```


## commits
when we want to commit code we can write a git commit which will open up the commit edit message in the editor of choice

```
git commit
```

set the global editor
```
git config -- global core.editor emacs
```

make a commit and commit message without opening the editor
```sh
git commit -m "add another question mark"
```
## Branches
list of branch 
```sh
git branch
```
create new branch 
```sh
git branch branch-name
```
checkout 
```
git checkout dev
```g
## Remotes


## Stashing


## Merging
## ADD
```git add Readme.md
git add. 
```
## Reset
reset allows you  to staged changes to be unstaged
this is useful when you to revert all files not to be not commited

```
git add.
git reset
```
 git reset will revert a git add.

 ## status
 git status will show you what files will or will not to be committed
 ```
 git status
 ```
 ## git config file
 It stores your global configuration for git such as email, name, editor and more
 showing the contents of our .gitconfig file
 ```sh
 git config --list
 ```
 When you first install Git on a machine You are supposed to set up your name and email.
 ```sh
 git config --global user.name "Your Name Here"
 git config --global user.email your@email.example
```
## Log
git log will show recent git commits to the git tree

## Push

when we want to Push a repo to our remote origin
```
git push
```

