### Introduction
*这个仓库主要是用于记录在看算法导论的期间个人做的笔记*

### 目的
提高自己对于算法和数据结构的理解和掌握，养成思考和分析问题的好习惯

### 要求
每天上传自己的看书笔记，不要求内容多少，不要求看书进度，只是自己每天都要有自己的收获，真正地
能够去多思考蕴藏其中的那种分析问题和解决问题的方法。

### 时间
目前暂定15天，万事开头难，所以我们为什么不以15天来挑战一下自己？

### 打卡奖励
自给自足，放松也很重要哈哈。

### 鸡汤
Talk is cheap, show me the code.

---
关于如何使用git将本地文件上传到本仓库的步骤：
可参考：[Creating a pull request](https://help.github.com/articles/creating-a-pull-request/)

1. 在浏览器中输入以下地址:
`https://github.com/MrMalleable/notebook.git`

2. Fork本项目

3. 在本地打开git bash（假设已经安装好Git）,执行以下指令：
`
git clone https://github.com/MrMalleable/notebook.git
`

4. 切换到该目录
`
cd notebook
`

5. 创建自己的markdown文件或者其他文件并编辑，或者修改已存在的文件，保存好之后上传到远程仓库。
`
git commit -a -m "Add: balalabla"
git push -u origin master
`
6. 在浏览器中进入自己的github主页，找到你已fork的本项目，点击new pull request进入pull request界面
确认提交的更改，确认无误后，开始填写本次提交的说明。

7. 点击create pull request来填写说明，填写好之后确认即可，等待原作者merge即可。

---
关于如何更新Fork项目的最新代码：
可参考：[Syncing a fork](https://help.github.com/articles/syncing-a-fork/)

1. 切换到本地的工程目录：
`
cd notebook
`

2. 将你fork的项目的最新文件先抓过来
`
git fetch notebook
`

3. 切换到master分支
`
git checkout master
`

4. 将最新项目的master分支和本地的master分支相结合
`
git merge notebook/master
`
---
ChangeLog:
2017/10/16 暂且先想到这么多，欢迎补充，以上若有错误，欢迎联系970014590@qq.com.
