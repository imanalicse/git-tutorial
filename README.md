# git-tutorial

Git Add commands:
```
$ git add .
$ git add --all
$ git add file_name
```

Returning to an Old Revision - Dangerous command
```
$ git reset --hard <commit>
$ git reset --soft <commit>
```

To revert to a previous commit, ignoring any changes: where HEAD is the last commit in your current branch

```
git reset --hard HEAD
```


```
$ git push
$ git push --all
$ git push -f
```

```
$ git checkout .
$ git checkout file_name
$ git checkout revistion_number
```

```
$ git clean -f
```

> Blockquotes are very handy in email to emulate reply text.

Branch commands:

Show all git branches
```
$ git branch -a
```
Add new branch:
```
$ git branch {branch_name}
$ git checkout {branch_name}
```
Get new branch:
```
$ git fetch
```