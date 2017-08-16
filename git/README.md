# Git

在Github上同步Fork过来的Repository
> https://blog.nex3z.com/2015/06/04/%E5%9C%A8github%E4%B8%8A%E5%90%8C%E6%AD%A5fork%E8%BF%87%E6%9D%A5%E7%9A%84repository/

Syncing a fork
> https://help.github.com/articles/syncing-a-fork/

Configuring a remote for a fork
> https://help.github.com/articles/configuring-a-remote-for-a-fork/

<br>

### 顯示、加入遠端儲存庫(repository)
```
$ git remote -v

origin https://github.com/user/repo.git (fetch)
origin https://github.com/user/repo.git (push)

$ git remote add upstream https://github.com/otheruser/repo.git
$ git remote -v

origin https://github.com/user/repo.git (fetch)
origin https://github.com/user/repo.git (push)
upstream https://github.com/otheruser/repo.git (fetch)
upstream https://github.com/otheruser/repo.git (push)
```
<br>

### 分支顯示、新增與切換
```
$ git branch

* master

$ git branch feature/test
$ git branch

  feature/test
* master
  
$ git checkout feature/test

Switched to branch 'develop'

$ git branch

* feature/test
  master
```
<br>

### 同步遠端伺服器上的資料到本地
```
$ git fetch origin
$ git fetch upstream
```

```
$ git pull upstream master
```

> git pull = git fetch + merge to local

<br>





