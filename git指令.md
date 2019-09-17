
# git常用指令

**git branch -a** 查看所有分支（本地加远程）
**git checkout \[branchName\]** 切换分支
**git checkout -b \[branchName\]** 创建并切换分支

**git add** 把工作区更改提交到暂存区。
**git commit** 把暂存区的更新提交到版本库中。
**git push** 把分支版本提交到远程分支。
**git pull** 把远程分支拉取到本地分支。

**git log** 查看commit历史
**git reflog** 查看所有切换分支和commit操作

**git checkout --f** 把工作区的数据替换成暂存区的数据。
**git reset Head** 把暂存区的数据替换成当前分支的最新版本的数据。
**git reset Head^** 把暂存区的数据替换成当前分支的上个版本的数据。
**git reset commit码** 把暂存区的数据替换成当前分支上commit码相应版本的数据。

**git merge \[branchName\]** 将某分支合并到当前分支。有冲突要先解决冲突，commit之后再merge。
**git branch -d \[branchName\]** 将某分支删除
**git merge --no-ff -m \[comment\] \[branchName\]** 不用fast forward合并，用普通合并，节点提交一次commit,能在git log 查看合并情况
