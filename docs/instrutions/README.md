# 使用说明

## Docsify简介

- Docsify 是一个动态生成文档网站的工具。不同于 GitBook、Hexo 的地方是它不会生成将 .md 转成 .html 文件，所有转换工作都是在运行时进行。 

## 设置封面
- 设置我们的封面图，需要两步，首先在 docs/index.html 文件中将设置 coverpage: true，之后创建 docs/_coverpage.md 文件,在docs/_coverpage.md 文件中修改即可得到你想要的封面。
![封面](封面.png)

## 定制导航栏
- 首先在 docs/index.html 文件中配置 loadNavbar: true，之后创建 docs/_navbar.md 文件，在其中修改以获得导航栏。
![导航栏](导航栏.png)

## 定制侧边栏
- 首先在 docs/index.html 文件中配置 loadSidebar: true，之后创建 docs/_loadSidebar.md 文件，在其中修改以获得侧边栏。
![侧边栏](导航栏.png)

## 推送
- 全局User配置(只用操作一次)
    - git config --global user.name "your_Name"
    - git config --global user.email "your_email"
- 初始化本地Git仓库
   - git init

-绑定远程仓库
    - git remote add origin 远程仓库地址

- 将所有文件添加到暂存区
    - git add *

- 将暂存区的文件添加到本地仓库
    - git commit -m "注释"

- 将远程仓库和本地仓库合并(如果合并失败整理好再push 或者 强制push)
    - git pull origin master --allow-unrelated-histories

- 将本地仓库推送到远程仓库(-u 跟踪分支 -f 强制推送)
    - git push -u origin master 
    - git push -f origin master







