#bigsword-manifest

repo: https://storage.googleapis.com/git-repo-downloads/repo

下载代码：

首次：
$ repo init -u git@git.oschina.net:sevsb/bigsword-manifest.git  # 更新仓库群信息
$ repo sync     # 更新所有仓库代码。
$ repo start master --all   # 建立master分支。

后续要全部更新时可以直接 repo sync
单一工程可以直接使用git管理。

工程与文件夹的分布对应情况参考本项目的default.xml


