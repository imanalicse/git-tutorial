# git-tutorial

>Git Add commands:
```
$ git add .
$ git add --all
$ git add file_name
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

Show git URL:
```
git config --get remote.origin.url
```

Set New git URL:
```
git remote set-url origin {git_url}
```

> Remove untracked file from git
```
git clean -f
```
* To remove directories, run:  ```git clean -fd```
* To remove ignored files, run: ```git clean -fX```
* To remove ignored and non-ignored files, `git clean -fx`

__revert all local uncommitted changes__
git checkout .

>Git revert for a single file
```
git checkout HEAD -- fileName.ext

git checkout @ -- myfile.ext
```
Note that @ is short for HEAD. An older version of git may not support the short form.

>How to merge a specific commit in Git

You can use git cherry-pick to apply a single commit by itself to your current branch.
```
git cherry-pick d42c389f
```
>How to delete a branch
* Delete branch  locally: ``` git branch -d localBranchName```
* Delete branch remotely : ``` git push origin -d remoteBranchName```