# GTI使用说明  

##初次运行 Git 前的配置
* Git 自带一个 git config 的工具来帮助设置控制 Git 外观和行为的配置变量  
    *  你可以通过以下命令查看所有的配置  
    `git config -l`
    *  



# GIT使用说明
`git config -l` 
`git config --global user.name "username"` // 用户名
`git config --global user.email username@example.com` 

`git init` // 添加
`git add "file.file"` // 需要添加到暂存区的文件
`git commit -m "file.info"` // 提交文件的注释
git branch -M main // 分支名
git remote add origin git@github.com:gxibvcCA/gxibvcCA.github.io.git  // 添加远程仓库
git push -u origin main   推送到仓库