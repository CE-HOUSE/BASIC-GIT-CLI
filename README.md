# GIT CLI
---
The Git CLI that you'll want to understand before working with your team is contained in this repository

##### Concept of GIT

![[Pasted image 20230226210130.png]]


##### Initial git on your workspace
```bash
git init
```

##### Add file to staging area
```bash
git add {yourfile} 
```
use **.**  to add all file  

##### Push file to local repo
```bash
git commit -m "{some message for team your team about this action}"
```

##### Create branch 
```bash
git branch -M {name of your branch}
```

##### Add Remote
```bash
git remote add {name of remote} "{GitHub URL}"
```

##### Push local repo to Remote [GitHub]
```bash
git push {name of remote} {name of branch}
```

##### Switch Specific Brach
```bash
git checkout {name of branch}
```

##### Switch To After Branch 
```bash
git checkout -
```

##### Switch & Create Branch
```bash
git checkout -b {name of branch}
```

##### Pull Code From Remote 
```bash
git pull
```

##### Merge Code [Very Dangerous Please Carefully, Need Expert Guy To See You]
```bash 
git merge {name of branch}
```
checkout to branch that you want to merge code  such as I want to merge branch **dev** to **main**, I must checkout to **dev** before merge. 

##### Log
```bash
git log
```

##### Rebase to Old Version
```bash
git rebase {commit_id}
```
**comit_id** you can find it from **Log**

######  see you again, promise I will write again when I come back
---
##### ***<div align="right">&diams; Created By BXDMAN &diams;</div>
