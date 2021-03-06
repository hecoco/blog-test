`git config --global core.editor 'code --wait'` 
使用vsCode作为编辑器

新建.gitignore文件 不需要上传的文件名加在里面

## 本地操作
`git init` 初始化 <br>
`git add 文件名` 选择需要提交的内容 删除也需要提交<br>
~~`git commit -m 字符串` 提交代码并说明理由~~<br>
`git commit -v`显示所有修改的地方并说明理由提交到本地仓库<br>
`git log`查看历史版本<br>
`git reflog`查看所有历史版本<br>
`git reset --hard 版本号`切换版本<br>
切换版本前需要你确保你已经`git commit`过了 没有的话可能部分文件会被删除或替换<br>
`git status -sb` <br>
`git status` <br>

## 云端操作
`git push -u origin main` 上传到远程仓库 <br>
`git pish origin 本地分支名:远程仓库分支名` 上传指定分支到远程仓库的指定分支 <br>
`git checkout 本地分支名 git push -u origin 远程仓库分支名 ` 作用同上 <br>
`git pull` = `git fetch ; git merge` 从远程仓库下载重新的分支，并与本地仓库合并<br>
`git reset --hard 版本号;git push -u origin main:main -f`回滚远程分支<br>
`git clone ` 下载/克隆 远程仓库(别人的远程仓库用https,自己的用SSH) <br>

## 分支
`git branch ` 基于当前版本创建分支<br>
`git branch -d` 删除分支<br>
`git checkout ` 切换分支 (主分支:master，远程仓库主分支:main)<br>
`git branch` 查看所有分支<br>
`git push origin --delete vip` **删除远程分支**<br>
`git merge ` 合并分支<br>



blog本地分支分别上传到两个远程分支<br>
`git push origin main:main`
`git push origin main:vip`



```bash
touch ~/.bashrc
echo 'alias ga="git add"'>> ~/.bashrc
echo 'alias gc="git commit -v"'>> ~/.bashrc
echo 'alias gl="git pull"'>> ~/.bashrc
echo 'alias gp="git push"'>> ~/.bashrc
echo 'alias gco="git checkout"'>> ~/.bashrc
echo 'alias gst="git status -sb"'>> ~/.bashrc

alias glog="git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit -- | less"

source ~/.bashrc 添加以上代码后需要运行这一行才能生效
```


<br><br><br><br>
**等待补充**