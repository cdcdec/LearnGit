## git标签

#### 1.新建标签﻿

```
git tag v1.0
//v1.0是标签名
//此标签还在本地

将标签推送到远程
git push origin v1.0   将v1.0标签推送到远程

git push origin --tags   推送全部标签
```

#### 2.删除标签

```
git tag -d v1.0
//先删除本地标签
git push origin :refs/tags/v1.0
//再删除远程标签
```
#### 3.显示标签

```
git tag  显示所有标签
```

