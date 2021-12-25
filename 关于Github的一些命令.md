`git config --global core.editor 'code --wait'` 
使用vsCode作为编辑器

## 本地操作
`git init` 初始化 <br>
`git add 文件名` 选择需要提交的内容 删除也需要提交<br>
`git commit -m 字符串` 提交代码并说明理由<br>
`git commit -v`显示所有修改的地方并说明理由提交到本地仓库<br>
`git log`查看历史版本<br>
`git reflog`查看**所有**历史版本<br>
`git reset --hard 版本号`切换版本<br>
切换版本前需要你确保你已经`git commit`过了 没有的话可能部分文件会被删除或替换
<br>
`git branch 字符串` 基于当前版本创建分支<br>
`git branch -d` 删除分支<br>
`git branch` 查看所有分支<br>
`git checkout 字符串` 切换分支 (主分支:master)<br>
`git merge 字符串` 合并分支<br>
`git status -sb` <br>
`git status` <br>

## 云端操作
`git push`
`git pish origin 本地分支名:远程仓库分支名`
`
git checkout 本地分支名
git push -u origin 远程仓库分支名
`
`git pull`
`git clone `








<br><br><br><br>
**等待补充**
