# Git-Commands
This repo contains the git commands

what is git?
what is github?
where is the entire history is stored?
stage and commit the versions?
untracked --->   staged area  --->   commit area
add github url to the local machine
branching and merging
what is upstream url?
why we should use the same branch for multiple features?
what is forced push?
How to maintain the main branch of the upstream and my own fork main branch us always maintained?
Merge conflicts
squashing the commits (rebase)
git fetch vs git pull

# Some git commands

01> git init
02> git status
03> git add . (or) git add names.txt
04> git commit -m "message"
05> git config --global user.name "name of useer"
06> git config --global user.email "email of user"
07> git rm --cached names.txt
08> git restore --staged names.txt 
09> git log
10> rm -rf names.txt
11> git reset <commit_id>
12> git stash (back stage)  |  git stash pop  |  git stash clear
13> git remote add <alias> <url>
14> git remote -v ( show all url's )
15> git push <to which url> <branch_name>
16> git branch <branch_name>
17> git checkout <branch_name>
18> git merge <branch_name> - be in the main branch
19> git push origin <branch_name> -f
20> git fetch -all --prune
21> git reset --hard upsteam/main
22> git pull upstream main
23> git rebase -i <commit_id>
24> git diff
25> git show <commit_id>
