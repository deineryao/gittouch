linux command
 
$ mkdir xx //创建文件夹
$ pwd //显示当前目录
$ touch xx.txt //创建文件夹
$ rm -rf xx //删除文件夹
$ rm -f xx.txt //删除文件

git command

git log //查看提交历史
git diff xx //查看两次提交/分支/文件差异 改动保存后未提交也可对比改动变化
git reset --hard HEAD^ //回退到上个版本
git reset --hard c9cec01 //回退到指定版本（通过git log 获取版本id前7位）
git reflog //记录每一次命令，可以找到删除的版本

情况分为三种
1.修改之后未add
直接使用git checkout -- readme.txt(撤销工作区的修改)
2.修改之后add了
先git reset -- HEAD .txt(撤销暂存区的修改)
后git checkout -- readme.txt(撤销工作区的修改)
3.commit之后
git reset -- hard HEAD^版本回退


查看分支：git branch
创建分支：git branch <name>
切换分支：git checkout <name>
创建+切换分支：git checkout -b <name>
合并某分支到当前分支：git merge <name>
删除分支：git branch -d <name>