# 学习Three.js

# 主要用途，实现全景图

- 第一次提交  (参考 https://blog.csdn.net/zhezhebie/article/details/78761417)

	`git init`

	`git add .` 或者 `git add` 文件名

	`git commit -m "这个干了啥。。。"`

	`git remote add origin https://github.com/shanliangdeYWJ/-Three.js-.git`  地址是仓库的 HTTPS 地址

	`git push -u origin master`    提交远程仓库
	
		按照本文档新建的项目时，在码云平台仓库上已经存在 readme 文件，故在提交时可能会存在冲突，
		这时您需要选择的是保留线上的文件或者舍弃线上的文件，
		如果您舍弃线上的文件，则在推送时选择强制推送，强制推送需要执行下面的命令：
	
	`git push origin master -f`


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



