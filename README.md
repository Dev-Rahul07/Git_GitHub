git - version controln/software
github -kind of cloud drive to store the code.
for configer the git cmd - git config --global user.name username
                           git config --global use.email "email id"


u - untrack file..
git add - all file is going to staaging area.
A - Added

git status - for cheking the status 
git commit -m"message"

changing Branch -
git branch -M main

git remote add origin url of repo


git remote -v
all origin

main - local branch

pushing code on github - 
git push -u origin main


to get code from github to my local we use git pull cmd

git pull origin main(from origin to main)




basacilly in a company there is a one main baranch and every dev creating there branch and complate there story and marge to main branch..


creating new brance - 
git branch devA(branch name)
its exct replica of main  branch


git checkout Dev1 ->Going to Dev1 Branch


Merge -  alway done from main branch
git  merge Dev1

how delte branch
git branch -d branchname