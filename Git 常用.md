# Git 常用



**关联远程仓库**

1. **创建远程**
2. **创建本地并初始化** git init
3. **关联远程** git remote add origin  [http]
4. **拉取远程仓库变化** git pull origin master
5. **本地仓库添加到暂存区** git add .
6. **提交到暂存区** git commit -m "提交说明"
7. **暂存区代码提交至远程仓库** git push origin master		

**基础配置**

​	**设置账号**

​	git config --global user.email rkkk@163.com

​	git config --global user.name rkkk

​	**查看全部分支**

​	git branch -a

​	git checkout [branch-name] 切换分支并更新工作区

​	

​	恢复暂存区到工作区







![image-20210220104241016](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210220104241016.png)

let Git use its default branch name (currently:"master")for the initial branch in newly created reositories.The Git project intends to change this default to a more indusive name in the near future



**11**

![image-20210220104622202](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210220104622202.png)

**default fast-forward or merge**

This is the standard behavior of 'git pull' :fast-forward the current branch to the fetched branch when possible ,otherwise create a merge commit

**rebase** 

rebase the current branch onto the fetched branch .if there are no local commits to rebase,this is equivalent to a fase-forward



**only ever fast-forward**

to the fetched branch . Fail if that is no possible





![image-20210220105116018](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210220105116018.png)