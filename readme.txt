Git is a version control system.
Git is free software.

//安装后设置本季配置
git config --global user.name "Datian"
git config --global user.email "1505879845@qq.com"

//初始化一个git仓库
git init

//添加文件到git仓库，分两步
git add <file> （可反复多次使用，添加多个文件）
git commit -m <message>

//查看仓库当前的状态
git status

//查看具体修改内容
Git diff readme.txt