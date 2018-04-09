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

test how stage works

git remote add origin git @server_name:/path/repo_name.git  #关联远程仓库
git push -u origin master  #第一次推送master分支所有内容
git push origin master  #推送最新修改

git clone git@github.com:path/repo_name.git  #从网络上克隆一个仓库

test dev

git branch  #查看分支状况
git  branch name  #创建分支
git checkout name  #切换分支
git merge name  #合并指定分支到当前分支
git checkout -b name  #创建+切换分支
git branch -d name  #删除分支

test feat1

Git 无法合并分支的时候，先解决冲突，再提交，合并完成
git log --graph  #查看分支合并图
通常合并分支时，Git采用 Fast Forward 模式，但删除分支后，会丢失分支信息

若禁用 Fast Forward 模式，Git会在merge时生成一个新的commit，这样分支历史上就能看出分支信息

a new commit

合并分支时加上 --no-ff参数就可以以普通方式合并，合并后的历史有分支，能看出合并痕迹，而Fast Forward看不出