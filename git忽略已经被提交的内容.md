## git忽略已经被提交的内容

#### 1.删除掉远程要忽略的文件或文件夹﻿

```
git rm -r --cached .  #清除所有缓存  想要忽略的但已经提交在服务器上的内容
git rm -r --cached gradle      忽略gradle文件夹  清除gradle文件夹缓存
git rm -r --cached .gradle      忽略以.gradle文件夹  清除.gradle文件夹缓存
```

#### 2.在.gitignore中添加要忽略的文件或文件夹

#### 3.commit 

#### 4.push


```
但是有时在使用过称中，需要对.gitignore文件进行再次的修改。这次我们需要清除一下缓存cache，才能是.gitignore 生效。

具体做法：

git rm -r --cached .  #清除缓存
git add . #重新trace file
git commit -m "update .gitignore" #提交和注释
git push origin master #可选，如果需要同步到remote上的话  将远程要忽略的文件去掉

这样就能够使修改后的.gitignore生效。

```

