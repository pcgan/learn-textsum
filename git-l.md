国贸西楼5层

git init

git add

git commit -m ""

git log

git relog

git reset --hard commit_id

git pull origin master –allow-unrelated-histories

git push origin master:master | <远程主机名> <本地分支名>:<远程分支名>

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>

命令git tag <tagname>用于新建一个标签，默认为HEAD，也可以指定一个commit id；

命令git tag -a <tagname> -m "blablabla..."可以指定标签信息；

命令git tag可以查看所有标签
