linux command
 
$ mkdir xx //创建文件夹
$ pwd //显示当前目录
$ touch xx.txt //创建文件夹
$ rm -rf xx //删除文件夹
$ rm -f xx.txt //删除文件

git command

git log //查看提交历史
git diff xx //查看两次提交/分支/文件差异
git reset --hard HEAD^ //回退到上个版本
git reset --hard c9cec01 //回退到指定版本（通过git log 获取版本id前7位）
git reflog //记录每一次命令，可以找到删除的版本
