# hfs

A simple example of what I talked about [here](https://draft.li/blog/2016/02/04/the-dangers-of-hfs-for-git-repositories/).

Clone this repo on macOS and do `git status`:

```
❯ g cn hfs /tmp/hfs

❯ cd /tmp/hfs
total 4
drwxr-xr-x 11 vhf 374 Jan 21 15:32 .git/
-rw-r--r--  1 vhf   2 Jan 21 15:32 a

❯ g s
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

  modified:   A

no changes added to commit (use "git add" and/or "git commit -a")
```
