#### To revert a specific file from a previous commit in Git
`git restore --source=<commit> <path/to/file>`

>Returning to an Old Revision - Dangerous command
```
$ git reset --hard <commit>
$ git reset --soft <commit>
```

>To revert to a previous commit, ignoring any changes: where HEAD is the last commit in your current branch

```
git reset --hard HEAD
```