# Git Learning Notes

GitHub Username: wcr1227

## Course Repositories

Introduction to Git:
https://github.com/wcr1227/skills-introduction-to-git <br>


Introduction to GitHub:
https://github.com/wcr1227/skills-introduction-to-github <br>


## Git and GitHub
可以把 github 拆成左边的 git 和右边的 hub理解，git 是一个控制版本的软件，一个文件夹被 git 管理起来以后就变成了一个 git 仓库，且会生成一个.git 的子文件夹，用来存放 git 的版本控制信息,但如果我们想要和其他人一起协作修改代码,就可以把本地仓库上传到远端服务器的仓库里,而GitHub 就是一个免费提供远端仓库的网站【不知道理解得对不对】


## Basic Workflow

### Commit
commit 就是提交作为版本控制的基本单元，每完成一次 commit，git 就保存了一个仓库此时状态的快照，随着 commit 的越来越多，会形成一条 commit 的历史链路，这样整个仓库都是可回溯的，可以查看历史的每个项目参与者的每一次改动，都会被这个 commit 链路记录下来
### branch
分支就是一条独立的开发流水线，可以理解成复制一份项目，在上面随便改，互不干扰，改完再合并回主代码。
### pull request

把分支代码，申请合并到目标分支，同时支持代码评审
## Learning record
git status : 查看 Git 当前仓库的状态 <br>
git add : 把文件的改动，加入暂存区(stage) <br>
git commit : 把暂存区里的改动，永久生成一条版本快照，保存到本地Git仓库

## Problem solving
之前对 Pull Request（PR）概念很模糊，分不清它和 git merge 的区别。现在明白了，merge只是本地合并代码，而PR是平台上的合并申请，附带代码评审、自动检测，是团队协作的规范流程，能避免错误代码直接进入主分支。


