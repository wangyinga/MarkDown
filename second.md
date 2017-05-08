# second
## 1.	个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？

New repository新存储库 、 import repository导入存储库、 new gist新要点、 new organization新组织

## 2.	如何能将仓库中的html文件直接解析成页面？


## 3.	如何删除仓库
登陆后选择你需要删除的仓库；在仓库的主界面的右边菜单栏选择settings；进入设置页面，一直往下拉，会发现一个红色的危险地区（danger zone）找到Delete this repostory ；点击delete弹出确认页面，要自己输入一次名字进行确认删除；会提示删除成功


## 4.	Bash是什么操作系统的命令
打印当前工作目录

## 5.	Pwd是什么命令
用 pwd 命令来查看”当前工作目录“的完整路径

## 6.	Cd是什么命令
cd命令的用途就是让我们可以到任何一个目录去

## 7.	Echo是什么命令
是个批处理命令，功能是：打开回显或关闭请求回显功能，或显示消息。如果没有任何参数，echo 命令将显示当前回显设置。

## 8.	配置git用户名的命令
git config --global user.name [username]


## 9.	配置邮箱的命令
git config --global user.email [email]

## 10.	命令行换行方式
/

## 11.	命令行终结方式
ctrl+c

## 12.	使用命令行比GUI方式有何优势
文件管理；列出文件和属性；使用crontab调度作业；安装软件包；图形界面工具功能不完整

## 13.	提交到本地仓库时为什么有暂存区
git的暂存区：英文叫stage, 或index。在版本库.git）目录下，有一个index文件。它实际上就是一个包含文件索引的目录树，像是一个虚拟的工作区。在这个虚拟工作区的目录树中，记录了文件名、文件的状态信息（时间戳、文件长度等），文件的内容并不存储其中，而是保存在Git对象库（.git/objects）中，文件索引建立了文件和对象库中对象实体之间的对应。如果当前仓库，有文件更新，并且使用git add 命令，那么这些更新就会出现在暂存区中。

## 14.	新建代码仓库的命令
github-create repo_name

## 15.	git clone [url] 这个命令的作用是
将这个URL地址的远程版本库，完全克隆到本地some_project目录下

## 16.	添加指定文件到暂存区的命令
git add [file1] [file2] ...

## 17.	删除工作区文件，并且将这次删除放入暂存区的命令
$ git rm [file1] [file2] ... 

## 18.	改名文件，并且将这个改名文件放入暂存区的命令
$ git mv [file-original] [file-renamed]

## 19.	提交暂存区到仓库的命令
$ git commit -m [提交信息]

## 20.	直接从工作区提交到仓库的命令
$ git commit -a

## 21.	显示变更信息的命令
$ git status

## 22.	查看历史信息的命令
$ git log

## 23.	Commit的意义是
提交

## 24.	Pull的意义是
获取版本

## 25.	Push的意义是
推送
