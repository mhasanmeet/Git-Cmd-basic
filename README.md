# Git & Command basic

## Basic Computer Commands
1. <code>touch</code> : is a command which is use to create make file. <code>touch index.html</code> means you're going to create index.html file</p>

2. `touch file1 file2 file3`
<p><code>touch file1 file2 file3</code> is a command which is same like number 1. But this way you can create multiple file at a time. </p>

3. <code>ls</code>
<p><code>ls</code> means list. Use for check all file list in the current directory</p>

4. <code>ls -la</code>
<p><code>ls -la</code> is use for check details of the current directory files. It show the file creation dates, root directory and more</p>

5. <code>mkdir</code>
<p><code>mkdir</code> means make directory. This is use for create directory/folder</p>

## Essentials Git Commands
1. <code>git init</code>
<p><code>git init</code> means git initialization. By this git command we can initialize git environment in our working directory</p>

2. <code>git status</code>
<p><code>git status</code> is use for check git status, means if there any changes happened, you can get a status of git operation</p>

3. <code>git add .</code>
<p><code>git add .</code> command is use for adding file for next the git operation and make ready for git commit</p>

4. <code>git commit</code>
<p><code>git commit</code> is a git operation which is use for commiting the file into the git, means it is now ready for push into remote repository. Git commit will show VIM edit. To exit this editor you need to press # & then `:wq`. WQ means without quote. If you submit message with git commit then the next command will apply</p>

5. <code>git commit -m "message"</code>
<p><code>git commit -m "message"</code> is same as 4  but in here you can pass your desired message the this operation.</p>

6. <code>`git remote add origin <remote link> `</code>
<p> <code>git remote add origin link</code> is a git command in where we add remote repository link in the command</p>

7. <code>`git remote set-url origin  <remote link> `</code>
<p> <code>git remote add origin link</code> is a git command which is use for set remote origin link if current link is unavailable or deleted</p>

8. <code>git merge</code>
<p><code></code></p>

9. <code>git pull</code>
<p><code></code></p>

10. <code>git fetch</code>
<p><code></code></p>

11. <code>git fetch -v</code>
<p><code></code></p>

12. <code>git log</code>
<p><code></code></p>

13. <code>git log</code>
<p><code></code></p>

14. <code>git commit --amend -m "message"</code>
<p><code></code></p>

15. <code>git log --stat</code>
<p><code></code></p>


## Branch
<p>Without content or file branching is not effective. That means you have to have file and commited. Then the branching will work. The default branch name for local git-scm is <b>master</b>. But If you want to push your master branch data into <b>GitHub</b> then you need to change local branch name as main.</p> 

<p>You can also rename GitHub branch name. For that you need to go setting option of the current repo. Then there have branch section, where the branch name can be editable. But remember there should have one deafult branch, which bydefault the first one (if you the change the branch name though).</p>

1. <code>git branch</code>
<p><code>git branch</code> is a git branch command which check how many branch have in the current directory & currently which branches you have in</p>

2. <code>`git branch <branch name>`</code>
<p><code>git branch <branch name></code>is a git branch command which will create a branch in the current director</p>

3. <code>git branch -M/-m <branch name></code>
<p><code>git branch -M/-m <branch name></code> is a git branch command which will merge existing current branch name to your provided name. -M or -m means mearge.</p>

4. <code>git checkout <branch name></code>
<p><code>git checkout <branch name></code> is a git branch command which will change branch and will move into provided branch name if it created and exit</p>

5. <code>`git branch -d <branch name>`</code>
<p><code>git branch -d <branch name></code>is a git branch command which will delete branch but can not delete current brancg name.</p>

6. <code>git switch <branch name></code>
<p><code>git switch <branch name></code> is a git branch command which is use for switch or move from one branch to another. In locally every branch can be have separate project. By switching you can move or switch from one branch to another by this command.</p>

--------------------
<code></code>
<p><code></code></p>
