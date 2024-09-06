# Commands from Git

## Basic routine for commiting

This is the basic routine for making a commit. You must add together files that you want to commit together.

```
git add <name_of_file>
git commit -m "meaningful_message"
```

**Note**: if you do not use the -m option, git will ask you to write a message. Otherwise, you will not be able to commit the changes.

Command to check the status of files/directories in the project:

```
git status
```

Adding a random line.



Command to show the log of the commits made.

```
git log
```

**Note**: if you want to restrain the number of commits listed, use the -n option. If you want to abbreviate the identifier of the commit, use the --abbrev-commit option.



Commands to show the differences between two commits.

```
git diff <commit_id1> <commit_id2>
```

or

```
git show <commit_id1> <commit_id2>
```

Command to create the conection between the local repository and the remote repository 
```
git remote add origin git@github.com:<username>/<remote_repository>.git
```

Command to push the changes to the remote repository
```
git push
```
**Note**: if it is the first time you push, it is necessary to use ```git push --set-upstream origin master```

```
git clone
```

```
git pull
```



Weird line here