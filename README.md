# git 学习记录

- **常用命令**:

 - git reset HEAD  //  取消暂存区
 - git diff --cached  //  对比暂存区和版本库差异
 - git diff //  对比工作区和暂存区差异
 - git diff HEAD //  对比工作区和版本库的差异
 - git checkout <file> //  把工作区某个文件更改删掉
 - git diff dev master -- <file> //  比较不同分支两个文件的差异
 - git stash // 把文件放入暂存区
 - git stash list // 查看暂存区内容
 - git stash apply | pop // 应用暂存
 - git remote add upStream http://  //添加远程仓库