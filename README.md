## 1. 使用git管理项目
    1). 创建本地仓库
        创建.gitignore文件, 并指定需要忽略的文件/文件夹
        创建一个工作区: git init
        添加到索引区: git add *
        提交到版本区: git commit -m "xxx"
    2). 创建github远程仓库
        注册并登陆
        New Repository
        指定仓库名
        确定创建
    3). 第一次将本地仓库推送到远程仓库
        关联远程仓库: git remote add origin https://github.com/zxfjd3g/git_test.git
        推送: git push origin master
    4). 如果本地修改代码, 推送到远程
        添加到索引区: git add *
        提交到版本区: git commit -m "xxxx"
        推送: git push origin master
    5). 如果远程修改代码, 拉取到本地
        pull拉取: git pull origin master
    6). 进公司的第一个事
        克隆项目: git clone https://github.com/zxfjd3g/git_test
        
## 分支
    1). 查看分支: git branch
    2). 创建分支: git branch dev
    3). 切换分支: git checkout dev