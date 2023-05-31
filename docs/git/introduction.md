# Git Introduction
Git is a distributed version control system that **tracks changes** in any set of computer files, usually used for coordinating work among programmers collaboratively developing source code during software development.


Some feature of git includes:
- Revert some files to a previous state.
- Revert an entire project back to a previous state.
- See a log of project changes.
- Compare changes between two project states.
- See who modified or introduced something within a single file. (e.g. a feature, or a bug etc.)
- And Many more!

Some terms that are important when we want to learn git:
- **Repository**: A collection of files, usually representing **a project**.
- **Commit**: The act of **registering** a set of changes as a single changeset.
- **Local**: The place where your current code resides (your computer)
- **Remote**: The place where your code can be used by other people (server)
- **Push**: Move local changes to a remote server.
- **Pull**: Retrieve remote changes from a remote server.
- **Branch**: a pointer to a snapshot of your changes at a given time (different timeline)

Git has certain command that can be executed to move or make changes to a file

Initialize a new git repository
```
git init <directory>
```
Add files to **staging area**
```
git add <file_name>
```
Register changes to repository with message
```
git commit -m "<message>"
```
Show the current status of your work on current branch
```
git status
```
Create new branch & change branch
```
git checkout -b <new_branch_name>
```
Push changes from local repo to remote repo
```
git push origin <remote_branch>
```
Pull changes from remote repo to local repo
```
git pull origin <remote_branch>
```

<br>

When we have new changes in our local repo and we wanted to make changes available in remote repo, the flow goes like this:

Change file -> Add file to Staging -> Commit and give message -> Push to remote

## Commit Message Convention
Commit message sometimes is standardized by team or by company. It can come with many different forms. But if you just learn to use git, you can use this template:

```
type: message
```

Type can be change to:
- feat (if the commit tells you about new feature)
- fix (if something is being fix)
- chore (if you have a really small changes that is not affecting any core functionality)
- refactor (if the code is being change for improvement)
- test (if you write only test code)

## Git Exercise

If you havent setup SSH, you can clone using HTTPS.

- Clone project `git-exercise` in the `shared-projects` subgroup using `Clone with HTTPS`
- In your terminal (Powershell), change directory to binar folder
- type `git clone <url>`
- Enter your email and password
- Fill `biodata.txt` with your Name, City, and Favorite Food
- Add `biodata.txt` to staging are using `git add biodata.txt`
- Commit your changes to your local repository using `git commit -m "feat: add my data to biodata"`
- Push your changes to remote repository using `git push origin <firstname_lastname_branch>`
- Open your browser, and open gitlab
- Switch branch, to see your changes in remote server

### Git Best Practices
Some best practice you can follow:
- Develop in feature branch, do not commit/push on master!
- Using flow of branching strategies (eg gitflow)

Commit best practices:
- Submit frequently in small steps and in one functionality/feature
- Do not submit incomplete changes
- Test changes before submitting
- Detailed commit message

