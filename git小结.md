## 初始化git
git init

## 把文件添加到暂存区
git add <filename>
## 把暂存区所有内容提交到当前分支
git commit -m "descripe"

## 查看日志
git log --pretty=oneline
## 查看状态
git status

## 返回上一版本
git reset --hard HEAD^
## 跳转到某一版本
git reset --hard <commitID（版本号）>

## 关联本地仓库到远程仓库
git remote add origin <https://github.com/1614080902137/gitTest.git>
## 取消关联
git remote remove origin
## 把内容推送到远程仓库
git push -u origin master
## 查看用户名和邮箱地址
* git config user.name
* git config user.email
## 修改用户名和邮箱地址
* git config --global user.name "username"
* git config --global user.email "email"
