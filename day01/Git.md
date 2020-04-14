# 安装
    git --version

# 初始化
    git config --global user.name 'tangqirui'
    git config --global user.email '1540232859@qq.com'
    git config --list
    git config --global alias.别名 "要执行的git命令"
    //删除配置
    git config --global --unset 配置名

# 区域
    工作区
    暂存区
    版本区

# 对象
    Git对象
    树对象
    提交对象
# 高层命令
## git init                 
    git init                |-----初始化仓库
## git status
    git status              |-----查看文件状态
## git add
    git add ./              |-----将修改添加到暂存区
    git add -A              |-----提交所有变化
    git add -u              |-----提交被修改(modified)和被删除(deleted)文件，不包括新文件(new)
    git add .               |-----提交新文件(new)和被修改(modified)文件，不包括被删除(deleted)文件
## git commit
    git commit              |将暂存区提交到版本库，可以打开编辑器写注释
    git commit -m 注释      |-----将暂存区提交到版本库
    git commit -a -m 注释   |-----可以跳过暂存区，将暂存区提交到版本库
## git diff 
    git diff                |-----修改之后还没有暂存起来的变化内容
    git diff --cached       |-----查看以及被暂存还没提交
    git diff --staged       |-----查看以及被暂存还没提交
## git log
    git log
    git log --oneline       |-----查看历史提交记录
    git log --oneline --graph --all      |-----查看项目分叉历史
## git rm
    git rm 文件名            | 删除工作目录中对应的文件,再将修改添加到暂存区
    git mv 原文件 新文件      |-----将工作目录中对应的文件重命名,再将修改添加到暂存区
## git branch
    git branch               |-----显示分支列表
    git branch 分之名         |-----创建分支
    git branch -d 分之名     |删除分支
    git branch -D 分之名     |强制删除分支
    git branch -v           |查看每一个分支最后一次提交
    git branch 分之名 提交hash           |以提交的hash为基础创建分支
## git checkout
    git checkout 分之名       |-----切换分支
## git config --global alias ""
    git checkout 分之名       |-----切换分支

## git merge
    gir merge 分之名          |--把分支合并到当前分支

    git remote -v
    git remote add origin https://github.com/iQirui/learnGit.git
    git push -u origin master




