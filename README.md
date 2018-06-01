# gitskills

在github上进行编写文件。

用 git pull origin master 命令 拉取最新代码。

本地修改，github上也修改

冲突解决

git -branch dev 命令创建分支 dev是创建的分支名称
git checkout dev 命令是选择分支
git branch 命令是查看所有分之，*标识当前所在的分支
Creating a new branch is quick & simple.

分支合并
创建一个新的分支 feature1 git -branch feature1
切换到feature1分支 git checkout feature1 编辑Readme.txt 文件的最后银行，添加 手动测试git合并带来的冲突，很开心,也很快乐
然后 git add readme.txt git commit -m "add simple"
切换分支到主干 git checkout master 编辑Readme.txt 文件的最后银行，添加 手动测试git合并带来的冲突，很开心并且很快乐，只需执行
git add readme.txt git commit -m "merge"
合并feature1分支到主干  git merge feature1 提示会有冲突，手动解决冲突，
然后 git add readme.txt git commit -m "merge success" 
可以通过命令查看分支合并情况
git log --graph --pretty=oneline --abbrev-commit