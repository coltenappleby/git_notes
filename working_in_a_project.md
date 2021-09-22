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
these do the same thing


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
Create a new file that shows the difference between these two commits
```
git diff Sha1(commitA)...Sha1(commitB)
git diff a3cfc00...96c7e6a
git diff a3cfc00...96c7e6a --color-words
```

### Multi-Line commit messages
Type only the below:
```
git commit -a
```
You will get: <br>
`Aborting commit due to empty commit message.` <br>
Now a new file will open and you can type a longer more detailed commit message.

First line should be the regular commit. Then skip a line. Then write more detailed information

Then close the editor.

To not see all the information when doing `git log` do
```
git log --oneline
```


### commit best practice
- one-line - less than 50 chars
- optionally a bonus blank line and then a more complete description
- keep each line less than 72 characters
- present tense
- label for the change of the commit
- bullet points - use '*' or '-'
