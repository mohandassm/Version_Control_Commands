# GIT Commands Local Server
- git status
- gitk
- git commit -m
- git commit -A "Yours Commnads"
- git pull origin master  
- git push origin master
---
`Example-`
---
$git init <directory Name>

$git init --bare <Directory Name>

Git Check Information
=====================
$gitk

Git Create Branch
=================
$git branch {branchname}

Git Branch Deatails 
====================
$git branch

$git brancgh -a

Git Tag Deatails 
================
$git tag

$git tag CCSVC_PB_WEBSPHERE CCSVC-2.0

Git Check Status
================
$git status

Git Add & Commit
=================
$git add -A

$git commit -m "Inforamtion"

Git Push & pull Command
=======================
$git pull origin master

$git push origin master

Git chnage one commit Back
===========================
$git log
$git reset --hard baf8d5e7da9e41fcd37d63ae9483ee0b10bfac8e
$git rebase -i baf8d5e7da9e41fcd37d63ae9483ee0b10bfac8e
$git push origin master -f
 
Git Chnage Branch or Checkout 
==============================
$git checkout CCTerget3.0
$ git push origin CCTarget3.0

Git Remove Branch 
=================
$git branch -r -d origin/devel

Git You might be needing a cleanup
==================================
$git gc --prune=now

Git configuration Deatails check
================================
$git config --list

Git Checkout or Merge Branch
==============================
$git checkout master
$git pull origin master
$git merge test
$git push origin master

Git Rename Branch
==============================
$git mv <old name> <new name>


https://git-scm.com/docs/gitignore
