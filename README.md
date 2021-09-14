# git-project
## Git学习	

git config --global user.name用户名         设置用户名标签

git config --global user.email邮箱     设置用户名标签

git init                                    初始化本地库

git status                               查看本地库状态

git add 									添加到暂存区

git commit -m  "日志信息"  文件名  文件名     提交到本地库(查看版本号git 	reflog         查看详细记录 git log)

git reflog 							查看历史记录

git reset --hard    版本号     版本穿梭	(回退)

Git一定要设置用户标签 否则无法提交代码		
git branch   分支名                                       创建分支

git branch -v 分支名           							查看分支

git checkout 分支名		  						切换分支

git merge 分支名	把指定分支合并到当前分支上

## 创建远程库

git remote -v	查看当前所有的远程地址别名

git remote add 别名 远程地址 

##  推送远程库

git push 别名 分支

git clone 远程地址

 1. 拉取代码 2.初始化本地库 3. 创建别名 

## 团队协作

git pull  别名  分支  (拉取本地库)
