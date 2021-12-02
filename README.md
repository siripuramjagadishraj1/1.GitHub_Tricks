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
sout <br/>
ctrl+shiftt+f10 <br/>
ctrl+o <br/>
Plugin: <br/>
	Presentation Assistant <br/>
	Ace Jump <br/>
shift shift <br/>
ctrl+shift+n <br/>
shift+ctrl+f <br/>
cmd+12 <br/>
ctrl+o <br/>
call heiriarchy= ctrl+alt+H <br/>
ctrl+f7 <br/>
shift+12 reset layout <br/>
alt+ins <br/>
ctrl+shift+f12 <br/>

### Other Used Commands
git stash && git checkout dev && git pull upstream dev && git checkout <branch> && git rebase dev && git stash pop <br/>
git reset --soft HEAD~1 <br/>
git log -1 <br/>
git commit --amend -m "message" <br/>
git cherry-pic <commit-id> <br/>
creating a release branch <br/>
