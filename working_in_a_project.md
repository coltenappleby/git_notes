# Working on a Project

### Seeing and comparing changes
See what files have changed since the last commit
```
git status
```

See what has changed:
```
git diff
git diff --color-words
```
### Adding and commit
To skip 'git add .'
- will stage and commit every change
- will not stage new files
```
git commit -a -m "message"
git commit -am "message"
```
these are the same


### Viewing old Commits
Seeing the log of old commits
```
git log
```
To see the actual commit
```
git show Sha-1
git show 96c7e6a
git show 96c7e6a --color-words
```

### Comparing Commits
