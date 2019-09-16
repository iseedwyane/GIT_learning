# git_learning


用法：git clone [<选项>] [--] <仓库> [<路径>]

    -v, --verbose         更加详细
    -q, --quiet           更加安静
    --progress            强制显示进度报告
    -n, --no-checkout     不创建一个检出
    --bare                创建一个纯仓库
    --mirror              创建一个镜像仓库（也是纯仓库）
    -l, --local           从本地仓库克隆
    --no-hardlinks        不使用本地硬链接，始终复制
    -s, --shared          设置为共享仓库
    --recursive           在克隆时初始化子模组
    --recurse-submodules  在克隆时初始化子模组
    --template <模板目录>
                          模板目录将被使用
    --reference <仓库>    参考仓库
    --dissociate          仅在克隆时参考 --reference 指向的本地仓库
    -o, --origin <名称>   使用 <名称> 而不是 'origin' 去跟踪上游
    -b, --branch <分支>   检出 <分支> 而不是远程 HEAD
    -u, --upload-pack <路径>
                          远程 git-upload-pack 路径
    --depth <深度>        创建一个指定深度的浅克隆
    --single-branch       只克隆一个分支、HEAD 或 --branch
    --separate-git-dir <git目录>
                          git目录和工作区分离
    -c, --config <key=value>
                          在新仓库中设置配置信息

	git branch  #显示分支列表
	得到了：master 
	git checkout v1.6.5  #退出原有分支，并切换到v1.6.5 分支。

## readme：
## gitignore
gitignore - Specifies intentionally untracked files to ignore       
这个文件的作用就是告诉Git哪些文件不需要添加到版本管理中  
## license:
GitHub 可以选择的开源许可证
## issue
Issue可以用来提出question, bug, enhancement等讨论，同时他人folk提交合并后都会在Issue里面有显示。   
GitHub 的 issue 功能，对个人而言，就如同 TODO list ( from zhihu:https://www.zhihu.com/question/22969033   

....最后，作为一个路人，你可以通过 issue 给别人的项目提 bug 
## insight

## respository
我的笔记本们
### 建立文件夹  
way1:  
点击New files按钮，然后输入含有slash字符（“/”）的文件名即可。也就是建立一个含有路径（目录）的文件，即会自动产生新文件夹。  
way2:  
点击Upload files按钮，然后直接把本地的文件夹（内含文件）


## fork
叉到我的餐盘里，可以任意修改
## markdown 标记语言
用“#”分级  
换行：（句末）两个以上的空格

代码块
超链接：[显示的名字](网址)
图片：插入图片的语法和插入超链接的语法基本一致，只是在最前面多一个 !   
      可以指定图片的显示大小  
视频



## git pull 
更新本地与云端一致
## push
上传
git push 终端分支号 本地分支号 
