# 学习Three.js

# 主要用途，实现全景图

- 第一次提交

	git init

	git add . 或者 git add 文件名

	git commit -m "这个干了啥。。。"

	git remote add origin https://github.com/shanliangdeYWJ/-Three.js-.git  地址是仓库的 HTTPS 地址

	git push -u origin master    提交远程仓库

- 后面提交
	
	git add . 或者 git add -u .   后者是不加参数默认为将修改操作的文件和未跟踪新添加的文件添加到git系统的暂存区，注意不包括删除
	
	git push -u origin master
	
	
	
- 创建分支（肯定在某个仓库里面新建）
	
	查看现有的分支：  git branch
	
	新建分支： git branch master2

	并且切换到该分支：git checkout master2
	
	新建文件：touch index.html     当然了新建文件夹是：mkdir index

	分支上第一次添加：git add .

	将被跟踪的文件提交到暂存区： git commit -a -m "提交信息"
	
	提交远程分支：git push -u origin 远程分支名字

- 合并分支