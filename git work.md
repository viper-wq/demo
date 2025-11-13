## 绑定用户名以及邮箱

git config --global user.name"用户名"

git config --global user.email 邮箱

## 创建本地库

复制他人的库 git clone 粘贴的地址

新建文件夹 git init

## 上传到暂存区

git add 文件名 or git add .

git commit -m " 备注"

## 查看节点

git log 可查看上传节点

git log --stat 可查看提交时修改哪些文件

git diff 某次提交的commit id 可以查看某次提交的内容

## 代码回溯

git reset --hard[commit id] 

git checkout[commit id]

## 分支

git chekout -b develop 创建develop分支

git brach 查看分支

## 合并分支

git add .

git commit

git checkout master

git merge develop 完成合并









- 