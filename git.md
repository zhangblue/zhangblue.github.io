Git 操作手册

1.将服务器中的代码clone到本地仓库

	git clone username@host:/path/to/reposito



2.查看修改过的文件代码
	
	git status



3.提交代码到本地库

	git add . //将所有修改过的代码添加到列表

	git commit -m '<message>' //将列表中的所有文件提交到本地库，<message>为描述信息

	git push origin <分支名> //将本地库中的代码上传到服务器中的<分支名>分支,<分支名> 为服务器端分支名。如果<分支名>分支在服务器没有则会创建出分支


4.更新本地仓库

	git pull



5.查看当前所在分支

	git branch



6.创建分支

	git checkout -b <feature_x> //创建本地分支<feature_x>,并切换到新分支

	git checkout <feature_x> //切换到已存在分支<feature_x>

	git branch -d <feature_x> //删除分支<feature_x>



7.合并分支

	git diff <分支1> <分支2> //查看分支1与分支2的区别

	git merge <分支名> //把<分支名>分支与当前所在分支进行合并