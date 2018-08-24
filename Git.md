# Git

## Commands

- `git clone <url>` = download the repository into your laptop
- `git add <filename>` = add the new files in the git list
- `git commit -m <"message">` =  Keeps tracks of you additions
- `git commit -a -m <message>` = where -a is for `git add`
- `git status` = self explanatory
- `git push` = will upload the committed changes to the on-line repository
- `git log` = provides the hash, time, author and message from the last files committed
- `git reflog` = It is a shot version of `git log`
- `git reset` --hard <commit hash> = copy the repository from that commit
- `git reset` --hard origin/master = copy the origin of the master to my local repository
## Merge Conflict
- `git pull`
```
  <<<<<<<<< HEAD
    some text 1
  =========
    some text 2
  >>>>>>>>> commit hash
```
