# GIT COMMANDS
### Create Repo
echo "# test" >> README.md <br/>
git init <br/>
git add README.md <br/>
git commit -m "first commit" <br/>
git remote add origin https://github.com/siripuramjagadishraj1/GitHub_Tricks.git <br/>
git push -u origin master <br/>

### Working with Repo
git clone https://github.com/siripuramjagadishraj1/GitHub_Tricks.git (Then edit files) <br/>
git status <br/>
git add editedFile.txt <br/>
git status <br/>
git commit -m "First edit" <br/>
git status <br/>
git push origin master <br/>
git push origin master:development //Creates development branch <br/>
git branch -a  //shows all branches <br/>
git checkout branchname //switch to branch name <br/>
git checkout -b newbranch //creates and swithches to new branchname <br/>

### User name and Password handling <br/>
git config --global --unset credential.helper   //<b>reset Credentials</b> <br/>
git config credential.helper store              //<b>git pull and give credentials will be saved for ever</b> <br/>
git config --global user.name "enteruser name" <br/>
git config --global user.email  "enter mail" <br/>
git config --global github.user  "enter password" <br/>
git config --global credential.helper wincred <br/>

### Intellij Short cuts
sout
ctrl+shiftt+f10
ctrl+o
Plugin:
	Presentation Assistant
	Ace Jump
shift shift
ctrl+shift+n
shift+ctrl+f
cmd+12
ctrl+o
call heiriarchy= ctrl+alt+H
ctrl+f7
shift+12 reset layout
alt+ins
ctrl+shift+f12

### Other Used Commands
git stash && git checkout dev && git pull upstream dev && git checkout <branch> && git rebase dev && git stash pop
git reset --soft HEAD~1
git log -1
git commit --amend -m "message"
git cherry-pic <commit-id>
creating a release branch
