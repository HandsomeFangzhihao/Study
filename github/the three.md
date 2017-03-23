#GIT GUI
##命令
	-touch + 文件名     创建
	-echo  + 内容       增加内容
	-cat   + 文件名     查看
	-git reset HEAD 回退
	-git clone git@github.com/HandsomeFangzhihao/文件
	-git commit -m "add 文件名"
    -git status   查看状态
    -gitk 启动GUI历史提交记录
	-git add -f file name 强制添加忽略文件
	-git check-ignore -v file name查看忽略状态
	-git log --pretty=format:'%h %s%d [%an]' --graph --date=short 显示历史
    -git config --global alias.ci commit  更改别名
    -vim .gitconfig 查看别名
    -esc shift: wq!  退出vim
    -clean - n 查看消除文件
    -       -f 消除
    
	-git rm + 文件  移除
	-git commit -m'delete 文件'提交移除分件
	-git mv a b更改名字
	-git commit -m 'rename a to be'提交更改命令
	-git mv 文件 ./文件夹/  移动到
	-git commit -m 'move b to 文件'
	-cd +文件 选中文件夹
	-git add. 提交所有文件
	-git commit 启动VIM编辑器 
    -docs(Features):fix 文件

###文件查看

	-git show HEAD 查看某个提交信息
	-git show HEAD~2 查看某2个提交信息
	-git log <file name>查看提交历史
	

	-cd..
	-ls
	-cd 文件夹名
	-git hi
	-git hi --grep add 查看过滤分件