# git commands

git --version
git config --global user.name 'sangavi167'
git config --global user.email 'sangavideena2004@gmail.com'
git config user.name #will give username
git config user.email #will give emailid

# connecting all files to main branch

git config --global init.defaultBranch main
git init #this will create a empty repo

git status #this will tell whether the file is commit or not

# this process is for adding single file
git add filename #this will add the file
git commit -m 'give some message' #this will take the ss
git log

# this process is for adding whole file
git add .
git commit -m 'initial commit'

# To checkout the privous changes

git log
git checkout id
git checkout main # to comeback

# if you want to change the previous file and want same as current file

git checkout id
git checkout -f main
git status #to check on which branch

# To connect local repo to global repo

git remote add origin https://github.com/sangavi167/git.git
git push -u origin main

