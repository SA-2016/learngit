Oh!It is great!
It is beautiful!

git config --global user.email "My Email"  #设置用户邮箱
git config --global user.name "My Name"  #设置用户名字

mkdir learngit  #创建新文件夹
cd learngit  #进入新文件夹
git init  #将文件夹初始化为工作区

git add file.txt  #提交工作区文件到暂存区
git commit -m "My Message"  #提交暂存区镜像到版本库，附加说明信息

test back

git reset --hard commit_id  #切换工作区文件到指定版本号，HEAD指向当前版本
git log  #查看提交历史
git reflog  #查看命令历史

test tree