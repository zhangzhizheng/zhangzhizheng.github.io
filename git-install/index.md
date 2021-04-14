---
title: git_install
date: 2016-05-21 11:37:22
---now I'm testing this new page, so.....


git install and setting:
$ git config –global user.name “name”
$ git config –global user.email “email”
$ git config –global color.ui auto
and then create a new directory as tutorial
$ mkdir tutorial
$ cd tutorial
$ git init
then create a new file as text.txt
$ git status
$ git add text.txt
$ git status
$ git commit -m “text”
$ git status
$ git log
next to rename the “https://…….” as origin
$ git remote add origin https://.........(do this only the first time)
$ git push -u origin master (the first time)
$ git push -u origin (do this the next time)
do clone the date-base(数据库，不知道是不是这个词)
$ git clone https://……. tutorial2(a new directory)
do pull file in your date-base
$ git pull origin master
$ git log
finally do another setting to make it better,but I meet a problem.
So I stop it temporarily,continue it if I have time.