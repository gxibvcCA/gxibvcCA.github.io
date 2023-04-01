# GTI使用说明  
_详细教程请查阅[git官网](https://git-scm.com/book/zh/v2/)_

## 初次运行 Git 前的配置
* Git 自带一个 git config 的工具来帮助设置控制 Git 外观和行为的配置变量  
    * 你可以通过以下命令查看所有的配置  
        `git config -l`  
    *  安装完 Git 之后，要做的第一件事就是设置你的用户名和邮件地址  
        `git config --global user.name "username"` // 设置用户名  
        `git config --global user.email username@gxibvc.com` // 设置邮箱地址  
## 获取 Git 仓库
* 通常有两种获取 Git 项目仓库的方式：
    * 1.将尚未进行版本控制的本地目录转换为 Git 仓库  
        `git init`  
    * 2.从其它服务器 克隆 一个已存在的 Git 仓库  
        `git@github.com:gxibvcCA/gxibvcCA.github.io.git`  
## 提交文件
* 暂存已修改的文件
    `git add "file.file"` // 需要添加到暂存区的文件
* 提交更新  
    `git commit`  
* 新建分支  
    `git branch "branchname"` // 设置分支名  
* 添加远程仓库  
    `git remote add gxibvc git@github.com:gxibvcCA/gxibvcCA.github.io.git`  // gxibvc 为 shortname 可以任意设置  
* 从远程仓库中拉取  
    `git fetch gxibvc`  // 拉取gxibvc仓库中的数据
* 推送到远程仓库  
    `git push gxibvc branchname` // 将branchname推送到gxibvc仓库  