# 这是一级标题

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
