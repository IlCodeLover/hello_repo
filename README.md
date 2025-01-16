```bash
mkdir hello_repo
cd hello_repo
git init # with master branch
git branch -m main # rename "master" to "main" (as default on remote)
touch README.md # create file
vim README.md # edit file
echo "print("Hi!") >> hello.py
git add .
git commit -m "initial commit"
<Go to github account, create a new repo with same name as on local machine>
# Map the remote to local repo
# git remote add <local repo> <remote repo's url>
# A default alias or name for the remote repository is 'origin'
git remote add origin url

# Push the code to the remote repository's main branch
git push -u origin main


```



