# booker2020
vscode中使用git

听城

关注
1
2017.02.26 09:56:39
字数 633
阅读 83,595
vscode简介
VSCode是微软推出的一款轻量编辑器，采取了和VS相同的UI界面，搭配合适的插件可以优化前端开发的体验。
布局：左侧是用于展示所要编辑的所有文件和文件夹的文件管理器，依次是资源管理器，搜索，GIT，调试，插件，右侧是打开文件的编辑区域，最多可同时打开三个编辑区域到侧边。在初次使用时如果本地没有安装git会提示先安装git，然后重启vscode。

git下载地址
Downloading Git
如果安装过程提示无法添加环境变量到path中，则需要将git安装目录下的cmd目录添加到系统的path变量下

配置git

设置全局配置
git config --global user.name "your name" 
git config --global user.email "your email"
进入你的项目目录
cd d:/wamp/www/wap              //首先指定到你的项目目录下
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/youtname/vscode.git   
//用你仓库的url,vscode.git中vscode为仓库名称,使用时必须先创建
git push -u origin master  //提交到你的仓库
正式使用

提交代码到git
回到vs code打开git工作区就会看到所有代码显示在这里
