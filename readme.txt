the first time to learn git!
pwd : to see the path 
git diff : to see the differences in the modified file
git status : to see the status
git log : 显示日志，及以往版本
git log --pretty=oneline : 以一行来显示版本
git reflog : 查看修改记录
git checkout -- file : 丢弃工作区的修改
git checkout -b file : 创建并切换分支
git branch : 查看当前分支
git checkout -b file = git branch file + git checkout file
git branch <name> : 创建分支
git checkout <name> : 切换分支
git merge <name> : 合并某分支到当前分支
git branch -d <name> : 删除分支
git log --graph : 可以看到分支合并图
git rag <tagname> : 打标签 默认为最新commit id
git rag <tagname> <commit id> : 对应commit id 打标签
git rag -a <tagname> -m 'aaaa' : 指定标签信息
git tag : 查看所有标签
git show <tagname> : 看到具体说明
git push origin <tagname> : 可以推送一个本地标签
git push origin --tags : 可以推送全部未推送过的本地标签
git tag -d <tagname> : 可以删除一个本地标签
git push origin :refs/tags/<tagname> : 可以删除一个远程标签


