<!-- NOTE  git config-->

----->to set
git config --global user.name pankaj
git config --global user.email pankaj@gmail.com

----->to show
git config user.name
git config user.email

1=> git status
Check which files are in pending stages and untracked files etc

<!-- Normally 3 steps of file MSG  MODIFIED STAGING COMMITTED -->

2=> git add index.html
staging a single file

3=> git add .
staging multiple files

4=> git rm --cached index.html
unstageing a staging file

5=> git commit -m "added index and style file"
-m ---- add a meaningful message
2 file changed, 12 insertions(+) ----- total no of code added/updated

<!-- NOTE log (NORMAL AND CONDENSED) -->

6=> git log
commit 133faa65378b78079354b9ef5a2d00cba91c6734 (HEAD -> master)
Author: devpankajmishra <pmishra403@gmail.com>
Date: Mon Jun 14 08:11:54 2021 +0530

    style body fontsize added

commit 16063fd59f956a9ff5b67a67153c390e8f94f7bb
Author: devpankajmishra <pmishra403@gmail.com>
Date: Mon Jun 14 08:09:12 2021 +0530

    help.md updated

commit 9e980aef67d5c7994aeb7ca9ec535a9c4e310350
Author: devpankajmishra <pmishra403@gmail.com>
Date: Mon Jun 14 08:03:28 2021 +0530

    added index and style file

7=> git log --oneline
133faa6 (HEAD -> master) style body fontsize added
16063fd help.md updated
9e980ae added index and style file
