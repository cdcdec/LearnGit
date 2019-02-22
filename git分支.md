## GIT分支

#### 1.分支

git branch  查看本地分支

git checkout -b rtmp    新建一个本地分支,分支的名称是rtmp.此命令会在本地创建一个rtmp分支并且自动切换到rtmp分支上.

```
在新建本地分支之前,要保证原来所在的分支是干净的,也没有需要提交的.例如:
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
```

git push origin rtmp:rtmp    把新建的本地分支push到远程服务器,远程分支与本地分支同名(远程分支可以随意起名)

git branch -a  查看所有分支

```
$ git branch -a
  master
* rtmp
  remotes/origin/HEAD -> origin/master
  remotes/origin/master
  remotes/origin/rtmp


* rtmp表示当前所在的分支是rtmp分支;
以remotes开头的分支是远程分支,不以remotes开头的是本地分支;
origin/HEAD就像一个指针,表示默认分支,它指向origin/master,即origin/master是默认分支。
```

git push origin :rtmp   推送一个空分支到远程分支,相当于删除远程分支

git push origin --delete rtmp    删除指定的远程分支


git branch -d 本地分支名    删除本地分支命令，注意这条命令不能在要删除的分支下执行
