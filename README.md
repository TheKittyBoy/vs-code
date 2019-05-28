# vs-code
## vs code 与 git 的相关操作
>下载git---地址：https://git-scm.com/
>>### clone远程仓库
>>>配置用户名与邮箱<br>
右键选择-Git Bash Here <br>
$ git config --global user.name 'TheKittyBoy'     #  -----配置你的用户名 <br>
$ git config --global user.email '1812128704@qq.com'     # ------配置你的邮箱 <br>
$ git clone ''https://github.com/TheKittyBoy/vscode.git'     # ------克隆你的项目（是你的项目地址） <br>
把下载下来的文件夹放入vs code中，创建一个你需要写的代码 <br>
$ cd vs--code-git/    #  -----进入你创建的文件夹 （tab键可自动补全） <br>
$ git add index.html   #  -----向git添加你的文件 <br>
$ git commit -m 'add index.html'   #  -----向git提交你的文件 <br> 
$ git push    #  -----向git远程厂库推送你的文件 从本地提交到远程<br> 
$ git pull   #  -----从远程git把文件下载下来 <br> 
