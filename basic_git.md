#  Basic Git

## Initialize

once you are in the directory that you want to start tracking do <br>
``` 
git init 
```
Once git has been initilized there is a .git directory in your project directory <br>


Once you have made changes to the directory you must stage the changes
to do so: <br>
``` 
git add . 
```
The period is telling git that you are refering to the current directory <br>

Now we want to actually track them and here is some information about it
```
git commit -m "heres some changes"
```

### commit best practice
- one-line - less than 50 chars
- optionally a bonus blank line and then a more complete description
- keep each line less than 72 characters
- present tense
- label for the change of the commit
- bullet points - use '*' or '-'

### View a commit log
Type: 
``` 
git log 
``` 
Will return something like this:
```
a2ca5ea added history and information (coltenappleby, 29 minutes ago)
807ac5f Initial commit (Colten Appleby, 6 days ago) 
```
<pre>
807ac5f Initial commit (Colten Appleby, 6 days ago) 
[-----] [------------] [--------------------------]      
  [1]         [2]                  [3] 
</pre>
1. unique commit identifier
2. comment
3. user and time

Try:
```
git log help
```


