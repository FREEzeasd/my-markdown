# Git基础

下附git笔记

git config --global user.name " "

git config --global user.email " "

↑ 配置个人信息

打开合适的目录，在一个文件夹内创建一个库

git init（初始化仓库）

此时这个目录里就有一个仓库力

(创建文件在文件夹里面）

git add xxx.md（将xxx.md加入暂存区）

git status（显示新加入的文件）

暂存区加错了文件，可以用git rm --cached xxx.xx  这个命令

删除文件，在Windows文件管理器中后，可往仓库加入 rm xxx.xx这玩意表示删除

git commit -m "描述信息"

提交暂存区文件到版本库

git log 显示版本(在仓库里)

git reset --hard (commit号)

git reflog 看之前版本改动

在接上reset就可以撤撤回（滚到之前reset掉的版本）

别人仓库 folk 可以窃

git clone 网址克隆

git push ---这里不知道是啥，此代码用于更新上传

再用pull reqrest申请别人更新