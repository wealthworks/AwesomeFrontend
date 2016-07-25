# Git

## remote

一般把主项目设为 upstream，把自己 fork 的版本设为 origin。为方便 review 别人的 MR，也可以把他/她 fork 的版本加到 remote.

```
$ git remote -v
origin  git@<server-name>:<me>/repo.git (push)
origin  git@<server-name>:<me>/repo.git (fetch)
mate    git@<server-name>:mate/repo.git (fetch)
mate    git@<server-name>:mate/repo.git (push)
upstream        git@<server-name>:guihua/repo.git (fetch)
upstream        git@<server-name>:guihua/repo.git (push)
```
