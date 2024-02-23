# Git
 "Master Git basics effortlessly! Dive into essential commands like add, commit, and push with our beginner-friendly GitHub tutorial. Start your coding journey today! 🚀💻 #GitBasics #GitHubTutorial"

 ### Note : copy the below commands, replacing `<placeholders>` with the actual values you need.

### Basic Commands

Initialize a new Git repository.  ( Naye Git repository ko shuru karta hai.)
 
```
    git init
```

Clone a repository from a URL. ( Repository ko URL se clone karta hai.)
```
    git clone <repository>
```
Add a file to the staging area. (File ko staging area mein add karta hai. )
```
git add <file>
```
Current directory mein sabhi files ko staging area mein add karta hai.
```
git add .
```
Commit changes to the repository with a message. (Changes ko repository mein commit karta hai ek descriptive message ke saath.)
```
git commit -m "message" 
```
Show the status of the working directory and staging area. (Working directory aur staging area ka status dikhata hai.)
```
git status
```
Show the differences between the working directory and staging area. (Working directory aur staging area ke beech ke differences dikhata hai.)

```
git diff
```
 Staging area aur last commit ke beech ke differences dikhata hai.
```
git diff --staged
``` 
Display the commit history. (Commit ka itihaas dikhata hai.)
```
git log
``` 
List all local branches.(Sabhi local branches ko list karta hai.)
```
git branch
``` 
Switch to the specified branch. (Diye gaye branch mein switch karta hai.)
```
git checkout <branch_name> 
``` 
Merge the specified branch into the current branch.(Diye gaye branch ko current branch mein merge karta hai.)
```
git merge <branch_name>
```

### Intermediate Commands

Add a remote repository. (Remote repository ko add karta hai.)
```
git remote add <name> <url>
``` 
Push changes to a remote repository.(Changes ko remote repository mein push karta hai.)
```
git push <remote_name> <branch_name>
``` 
Fetch changes from a remote repository and merge them. (Remote repository se changes fetch karta hai aur unhe current branch mein merge karta hai.)
```
git pull <remote_name> <branch_name>
``` 
Fetch changes from a remote repository.
```
git fetch <remote_name>
``` 
Unstage the specified file.
```
git reset <file>
``` 
Reset the index and working directory to the last committed state.
```
git reset --hard
``` 
Remove a file from the working directory and staging area.
```
git rm <file>
``` 
Create a lightweight tag at the current commit.
```
git tag <tag_name>
``` 
Create an annotated tag at the current commit.
```
git tag -a <tag_name> -m "message"
``` 
Stash changes in the working directory for later use.
```
git stash
``` 

### Advanced Commands

Reapply commits on top of another base tip.
```
git rebase
``` 
Apply the changes introduced by an existing commit.

```
git cherry-pick <commit>
``` 
Use binary search to find the commit that introduced a bug.

```
git bisect
``` 
Manage Git repositories as submodules within a parent Git repository.

```
git submodule
``` 
Rewrite branches to remove or modify commit history.

```
git filter-branch
``` 
Record changes to the tip of branches over time.

```
git reflog
``` 
List all remote repositories along with their URLs.

```
git remote -v
``` 
Display a text-based graphical representation of the commit history.

```
git log --graph
``` 
Amend the last commit with new changes or an updated commit message.

```
git commit --amend
```
Merge changes from one branch into another with a single commit.

```
git merge --squash
``` 




