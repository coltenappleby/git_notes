### .gitignore Files

What if we don't git track some files
1. The file: <br>
 `project/gitignore`
2. List of rules of what files to ignore
3. Changes made to these files will be ignored by git

What kinds of files would you want to ignore?
* Log files that change often
* temporary files
* files that contain API keys
* zip files
* compiled source codes
* databases -- they change often
* user uploaded assests

How to use:
* regular expressions
    * all logs <br>
    `logs/*.txt`
* negative expressions
    * all PHP files <br>
    `*.php`
    * do not ignore: <br>
    `!index.php`
* all files in a directory <br>
    `assests/videos/`
* Comments <br>
    `#`
* blank lines will be skipped

** Good examples of git ignore files can be found on github! **
`github.com/github/gitignore`

### what the file would look like
How do you read this:
`log/*.log.[0-9]`
any file that ends in .log with the numbers 0-9 at the end in the log directory
