# Git & Command basic

## Basic Computer Commands
1. <code>touch</code> : is a command which is use to create make file. <code>touch index.html</code> means you're going to create index.html file.

2. <code>touch file1 file2 file3</code> : is a command which is same like number 1. But this way you can create multiple file at a time.

3. <code>ls</code> : means list. Use for check all file list in the current directory.

4. <code>ls -la</code> : is use for check details of the current directory files. It show the file creation dates, root directory and more.

5. <code>mkdir</code> : means make directory. This is use for create directory/folder.

6. You can run multiple command at once, like <code>mkdir code && cd code && npm init -y && code .</code> In here we run multiple command at once with the help of && (and). The operation here is: create a code directory and then move into that directory and then create a npm inital empty project file and then open this directory into vscode editor. 

## Git Commands

### Basic Git
1. <code>git --version</code> : Check git version. 

2. <code>git --help</code> : Here you can found basic git commanand for daily needs. If you need any help from git related issue, you can also press this command.

3. <code>git help -a</code> : This command will show all available commands for helping purpose.

4. <code>git help --help</code> : This command show all of the available options you can use.

5. <code>git init</code> : means git initialization. By this git command we can initialize git environment in our working directory.


### Wokring with code
1. <code>git status</code> : is use for check git status, means if there any changes happened, you can get a status of git operation.

2. <code>git add .</code> : command is use for adding file for next the git operation and make ready for git commit.

3. <code>git commit</code> : is a git operation which is use for commiting the file into the git, means it is now ready for push into remote repository. Git commit will show VIM edit. To exit this editor you need to press # & then `:wq` , WQ means without quote. If you submit message with git commit then the next command will apply.

4. <code>git commit -m "message"</code> : is same as 3  but in here you can pass your desired message the this operation.

5. <code>git remote add origin {remote link}</code> : is a git command in where we add remote repository link in the command.

6. <code>git remote set-url origin {remote link}</code> : is a git command which is use for set remote origin link if current link is unavailable or deleted.

7. <code>git merge</code> : This command is user for merge.

8. <code>git pull</code> : This command is user for pull from remote repo.

9. <code>git fetch</code> : The git fetch command will downloads commits, files, and refs from a remote repository into local repo

10. <code>git log</code> : This command will show recent git commit history.

11. <code>git log --stat</code> : This command will show git commit where how many and much files changes.

14. <code>git commit --amend -m "message"</code> : `amend` is use for uncommit most recent git commit. 

15. <code>git rm {file name}</code> : Use for remove a file. After this you need to git commit & push to remote repo. 

16. <code>git rm .</code> : This command will remove or delete all the file from current branch. After this need to commit and push the file(s). After then the file will be tracked and you can switch or move from one branch to another. Commit is important for switching the branch. 

### Branch
<p>Without content or file branching is not effective. That means you have to have file and commited. Then the branching will work. The default branch name for local git-scm is <b>master</b>. But If you want to push your master branch data into <b>GitHub</b> then you need to change local branch name as main.

<p>You can also rename GitHub branch name. For that you need to go setting option of the current repo. Then there have branch section, where the branch name can be editable. But remember there should have one deafult branch, which by default the first one (if you the change the branch name though). If you changed branch name then Github will instruct or guide you how you can change your local env for continuous push pull.

1. <code>git branch</code> : is a git branch command which check how many branch have in the current directory & currently which branches you have in.

2. <code>git branch {branch name}</code> : is a git branch command which will create a branch in the current director

3. <code>git branch -m {branch name}</code> : is a git branch command which will merge existing current branch name to your provided name. -m means mearge.

4. <code>git checkout {branch name}</code> : is a git branch command which will change branch and will move into provided branch name if it created and exit.

5. <code>git branch -d {branch name}</code> or <code>git branch --delete {branch name}</code> : is a git branch command which will delete branch but can not delete current branch name. You can use <code>-d</code> or <code>--delete</code> as your wish.

6. <code>git switch {branch name}</code> : is a git branch command which is use for switch or move from one branch to another. In locally every branch can be have separate project. By switching you can move or switch from one branch to another by this command.

7. <code>git push origin HEAD</code> : Is a git push command if you create a new branch but do not have Remote (origin) exist yet. This command will push and create a branch as same as local name. 


### Remote Branch
1. <code>git config --get remote.origin.url</code> : Show remote repository URL.

2. <code>git remote show origin</code> : Show remote repo branches. 

3. <code>git branch -vv</code> : Show upstream branches.

5. <code>git branch -v</code> : show branch and recent commit.

4. <code>git push origin HEAD</code> : Use to push to the branch of the same name on the remote.

5. <code>git clone --single-branch -b {branch name} {remote link}</code> : Use to clone single specific branch from remote repo. 

## Effective Git Commit Message, check: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

* For new Feature: `"🚀 FEAT: Add new functionality."`
* For fixing: `"🛠️ FIX: Fixing things."`
* Style Update: `"💄 STYLE: Update the styles."`
* Refactoring the code: `"🔧 REFACTOR: Refactor the code to improve readability."`
* For test message: `🧪 TEST: new test for this functionality.`
* For update dependency: `"🧹 CHORE: Update dependencies in package.json."`
* Optimize Images: `"🏎️ PERF: Optimize image loading for faster performance."`
* Fixing issue for pipeline: `"🚦 CI: Fix issue with test pipeline on things."`
* Build the code: `"🏗️ BUILD: Add new script for building the production version of the app."`