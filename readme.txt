1.安装
2.终端中建立版本库（即为建立一个合适的文件夹）：
$ mkdir learngit
$ cd learngit
$ pwd
/Users/michael/learngit

3.通过git管理版本库：
通过git init命令把这个目录变成Git可以管理的仓库：
$git init

4.将文本加入到版本库中：建立一个文本，命名为readme.txt

git Git is a version control system.
Git is free software.

文件放到/Users/michael/learngit目录下。
A 加进去
$ git add readme.txt


B 提交：
$ git commit -m "wrote a readme file"
简单解释一下git commit命令，-m后面输入的是本次提交的说明，可以输入任意内容，当然最好是有意义的，这样你就能从历史记录里方便地找到改动记录。


初始化一个Git仓库，使用git init命令。

添加文件到Git仓库，分两步：

第一步，使用命令git add <file>，注意，可反复多次使用，添加多个文件；

第二步，使用命令git commit，完成。



6.git status命令可以让我们时刻掌握仓库当前的状态

$git status

7.git diff命令可以让我们查看修改了什么内容
$ git diff readme.txt 

8.git log 查看日志。

9.HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令git reset --hard commit_id。

穿梭前，用git log可以查看提交历史，以便确定要回退到哪个版本。

要重返未来，用git reflog查看命令历史，以便确定要回到未来的哪个版本。
Creating a new branch is quick and simple.
>>> featurel 
new row
