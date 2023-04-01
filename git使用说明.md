# GTI使用说明  
_详细教程请查阅[git官网](https://git-scm.com/book/zh/v2/)_

## 初次运行 Git 前的配置
* Git 自带一个 git config 的工具来帮助设置控制 Git 外观和行为的配置变量  
    * 你可以通过以下命令查看所有的配置  
        `git config -l`  
    *  安装完 Git 之后，要做的第一件事就是设置你的用户名和邮件地址  
        `git config --global user.name "username"` //设置用户名  
        `git config --global user.email username@example.com` //设置邮箱地址  
## 获取 Git 仓库
* 通常有两种获取 Git 项目仓库的方式：
    * 1.将尚未进行版本控制的本地目录转换为 Git 仓库  
        `git init`  
    * 2.从其它服务器 克隆 一个已存在的 Git 仓库  
        `git@github.com:gxibvcCA/gxibvcCA.github.io.git`  


`git add "file.file"` // 需要添加到暂存区的文件
`git commit -m "file.info"` // 提交文件的注释
git branch -M main // 分支名
git remote add origin git@github.com:gxibvcCA/gxibvcCA.github.io.git  // 添加远程仓库
git push -u origin main   推送到仓库