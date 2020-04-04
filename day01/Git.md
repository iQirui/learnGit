# 安装
    git --version

# 初始化
    git config --global user.name 'tangqirui'
    git config --global user.email '1540232859@qq.com'
    git config --list

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



