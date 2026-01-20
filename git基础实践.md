```sh
使用git工具，将文件从本地工作区，添加到暂存区，提交到远程仓库；
大体流程为：

git clone <repository_address>

git branch <new_branch> #创建新分支

git checkout <new_branch> #切换到新分支

git add <file>

git commit -m 'content' <file>

git push origin <branch_name>


#合并分支,当前分支合并branch_name的分支代码

git merge <branch_name>

合并之后就需要解决冲突；

可能还需要经常用到下边的命令

git reset HEAD^ #回退到上一个提交

git reset --hard <commit_hash>

git checkout -- <file>#撤销工作区的修改

# 查看提交历史

git log

# 查看仓库状态

git status

```
