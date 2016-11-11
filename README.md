# 记录常用git命令

# 创建版本库
git init

# 时光机穿梭
git status                          #仓库当前的状态
git diff                            #查看difference
git add .                           #提交所有修改和新文件到暂存区
git commit                          #提交“保存一个快照”

git log                             #显示从最近到最远的提交日志(提交历史)
git log --pretty=oneline            #嫌输出信息太多

git reset --hard HEAD^              #在Git中，用HEAD表示当前版本，上一个版本就是HEAD^，上上一个版本就是HEAD^^ => 往上100个版本 HEAD~100 
git reset --hard 3628164            #版本号没必要写全，前几位就可以了

git reflog                          #查看命令历史