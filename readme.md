# Git Basics
* Git started with Git
```
git init -- initialize git tracking
```

* What's going on?
```

git status -- get current status of repo
git branch
```

* Stage 1 file or all files
``` 
git add readme.md
git add -A
```

* Commit
```
git commit -m "Initial commit"
```

* Add origin
```
git remote add origin 'url'
```

* Push to github
```
git push origin master
```



## Branches

Display all branches
```
git branch
```

Create new branch
```
git checkout -b newbranch
```

merging
```
git merge dev
```

## Summary

Common commands once set up
```
git add -A
git commit -m "message"
git push origin master
git checkout -b newbranch
git merge newbranch
```

More advanced
```
git log
git reset -- hard <commit>
```