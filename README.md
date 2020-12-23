# Git1st

## 善用佳软

- [git教程](https://www.bilibili.com/video/BV1up4y167fn?p=1)
- Markdown文档(对应软件Typora)
- notepad++
- chrome 浏览器
- octotree (chrome 应用商店中download) 用来查看github中代码


## Git 三种状态与工作模式

<img src="https://git-scm.com/figures/18333fig0106-tn.png" alt="git modes" style="zoom:20%;" />

### Git 初阶

- **git init**
- **git add** *filename.suffix*
- **git status**
- **git commit -m** '*description*'
- **git commit -a -m**  *'5th submmision'* // compound command
- **git log**

### git 常用命令行

- git config --global user.name "isaacyn"
- git config --global user.email "55430491@qq.com"
- git config --list

### Git时光穿梭机

- **git reset HEAD** *filename*  // remove files from staging area before commit

- **git reset --hard HEAD^**

- **git reset --hard HEAD~2**

- **git reflog**

- **git reset --hard** *address* // git reset --hard ff960d6

- **git log --pretty=oneline**

- **git rm** *filename*
