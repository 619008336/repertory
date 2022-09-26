# repertory
仓库repertory

第一次提交测试

生成本地库,克隆一般不需要(会导致.git平级文件夹中存在.git)

git init

克隆

git clone

修改文件保存后添加所有文件

git add . 或 文件名 或 文件夹名

查看本地库状态,查看修改

git status

提交到本地库

git commit -m "提交说明" 

提交远程库的main分支

git push origin main

查看远程库所有分支

git branch -r

查看本地分支

git branch

查看本地和远程所有分支

git branch -all

更新分支

git pull --rebase

创建分支

git branch 分支名

切换(并创建)分支

git checkout (-b) 分支名

删除/强制分支

git branch -d或-D 分支名

拉取远程分支并创建本地分支

git checkout -b 本地分支名 origin/远程分支名(会建立本地分支和远程分支的映射)

git fetch otigin 远程分支名:本地分支名(不建立映射,且需要手动切换本地分支)

查看映射关系

git branch -vv

建立分支映射

git branch -u origin/分支名 或 git branch --set-upstream-to origin/分支名

撤销映射

git branch --unset-upstream
