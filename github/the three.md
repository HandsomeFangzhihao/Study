#GIT GUI
##命令
	-touch + 文件名     创建
	-echo  + 内容       增加内容
	-cat   + 文件名     查看
	-git reset HEAD 回退
	-git commit -m "add 文件名"
    -git status   查看状态
    -gitk 启动GUI历史提交记录
	-git add -f file name 强制添加忽略文件
	-git check-ignore -v file name查看忽略状态
	-git log --pretty=format:'%h %s%d [%an]' --graph --date=short 显示历史
    -git config --global alias.ci commit  更改别名