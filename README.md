###git常用命令行汇总

## 创建分支 合并分支
- git checkout 分支名（查看分支）
- git branch 分支名  （创建分支）
- git merge master （合并master到当前分支，然后git push把合并的代码提交的远程仓库）
- git status 查看文件状态 及合并情况 是否有冲突
- git branch -a 查看本地和远程的分支
- git fetch origin 分支名   把远程分支拉到本地
- git checkout -b 分支名 origin/分支名  在本地创建分支并切换到该分支 然后执行git pull origin 分支名   


## git常用命令行详解地址

- http://yanhaijing.com/git/2014/11/01/my-git-note/