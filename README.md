git version
git config --global user.name " "
git config --global user.email " "
git config --list
//to remove
git config --global --unset user.name " "
git config --global --unset user.email " "

//create folder
mkdir folder_name
cd folder_name
//initialise
git init
//create file
vim new1.py

git add new1.py
git commit -m "message"

//check branch
git status 
or git branch

//create branch
git branch new_branch

//change branch
git branch branchname
or git branch -m main

//remote origin
git remote add origin "link of repo"
git remote remove origin





