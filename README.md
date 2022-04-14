# Git-Commands
This repo contains the git commands

what is git? <br> 
what is github? <br>
where is the entire history is stored?<br>
stage and commit the versions?<br>
untracked --->   staged area  --->   commit area<br>
add github url to the local machine<br>
branching and merging<br>
what is upstream url?<br>
why we should use the same branch for multiple features?<br>
what is forced push?<br>
How to maintain the main branch of the upstream and my own fork main branch us always maintained?<br>
Merge conflicts<br>
squashing the commits (rebase)<br>
git fetch vs git pull<br>

# Some git commands

01> git init<br>
02> git status<br>
03> git add . (or) git add names.txt<br>
04> git commit -m "message"<br>
05> git config --global user.name "name of useer"<br>
06> git config --global user.email "email of user"<br>
07> git rm --cached names.txt<br>
08> git restore --staged names.txt <br>
09> git log<br>
10> rm -rf names.txt<br>
11> git reset <commit_id><br>
12> git stash (back stage)  |  git stash pop  |  git stash clear<br>
<br>
<br>
13> git remote add <alias> <url><br>
14> git remote -v ( show all url's )<br>
15> git push <to which url> <branch_name><br>
16> git branch <branch_name><br>
17> git checkout <branch_name><br>
18> git merge <branch_name> - be in the main branch<br>
19> git push origin <branch_name> -f<br>
20> git fetch -all --prune<br>
21> git reset --hard upsteam/main<br>
22> git pull upstream main<br>
23> git rebase -i <commit_id><br>
24> git diff<br>
25> git show <commit_id><br>
