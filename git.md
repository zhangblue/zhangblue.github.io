Git 操作手册

1.将服务器中的代码clone到本地仓库

	git clone username@host:/path/to/reposito



2.查看修改过的文件代码
	
	git status



3.提交代码到本地库

	git add . //将所有修改过的代码添加到列表

	git commit -m '<message>' //将列表中的所有文件提交到本地库，<message>为描述信息

	git push origin <master> //将本地库中的代码上传到服务器中的master分之,<master> 为服务器端分之名



4.