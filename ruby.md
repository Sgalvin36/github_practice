#Making changes to GitHub

1. make directory on local
2. create git and commit to git
3. in Github, create repository without a readme file
4. following page gives instructions for assigning the repository to the git on the local
5. `git remote add origin git@github.com:USERNAME/REPO_NAME.git`
6. basically `origin` is the variable and the git@github... is the data of the variable
7. `git branch -M main` : names the central branch
8. `git push -u origin main` : sends current version of git on local to cloud repository

## Common issue
1. `git remote -v` :shows status of current origin connection
2. if you need to remove the connection: `git remote remove origin`
3. check connection to see it severed
4. create a new empty repository on Github and use the command `git remote add origin [insert SSH code here]`
5. Run final two commands to establish main branch and push work. `git branch -M main` `git push -u origin main`