###DELETE A BRANCH FROM COMMANDLINE : 

```git push origin --delete BRANCHNAME```

### CREATE EMPTY BRANCH :

```git checkout --orphan BRANCHNAME```

### EMPTY ALL FILES IN A BRANCH :

```rm -rf * 
git status
git add . 
git commit -m "Message"```
