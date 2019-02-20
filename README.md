# git-tutorial

>Git Add commands:
```
$ git add .
$ git add --all
$ git add file_name
```

>Returning to an Old Revision - Dangerous command
```
$ git reset --hard <commit>
$ git reset --soft <commit>
```

>To revert to a previous commit, ignoring any changes: where HEAD is the last commit in your current branch

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
$ git checkout <branch_name>
$ git checkout <commit>
```

```
$ git clean -f
```


```
$ git branch
$ git branch <branch_name>
$ git branch -d <branch_name>
```

> Blockquotes are very handy in email to emulate reply text.
=======
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

Show git URL:
```
git config --get remote.origin.url
```

Set New git URL:
```
git remote set-url origin {git_url}
```
