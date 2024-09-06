<<<<<<< HEAD
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

Weird line here

# What have I done?
What?

Command to create a branch:
```
git branch <branch_name>
```


Command to change the context to a branch:
```
git checkout <branch_name>
```
**Note**: this is used also for going to the master (main) branch.

Command to checkout to a point in the past
```
git checkout <commit_id>
```

Command to create a tag for the current commit:
```
git tag <tag_name>
```
**Note**: when pushing, you must remember to use the *--tags* option in ```git push``` to push the tags to GitHub.