<font size=7 face="微软雅黑">Git学习笔记</font>

<font size=5 face="微软雅黑">让Git认识你</font>  

<font size=4 face="微软雅黑">与Git搭讪</font> 

	git config --global user.name "YOUR NAME"  
	git config --global user.email "YOUR EMAIL ADDRESS"

没有消息就是好消息！

查看配置信息

	git config --list


重在掺和
目的：表达意见，别人听不听就两说了；自言自语也是可以的。
步骤：
1.


<font size=5 face="微软雅黑">Github Page</font>

<font size=4 face="微软雅黑">切换 gh-pages 分支</font>

	git checkout --orphan gh-pages  
之后用 `git branch` 命令并不显示gh-pages分支，直到git commit之后才显示出来

问题：
clone一个已经有gh-page分支的repo,用git branch发现并没有gh-page分支

默认index.html作为主页

<font size=4 face="微软雅黑">gh-pages与master分支</font>

分不清gh-pages和master分支的区别。要是把前端代码直接放到Github上，还真分不清哪个是Project哪个是Github Pages呢。如果项目是java代码呢，是不是就泾渭分明了。

	git push origin master:gh-pages

参考：  
[how-to-publish-master-branch-pages-instead-of-gh-pages](http://stackoverflow.com/questions/21163140/how-to-publish-master-branch-pages-instead-of-gh-pages)




<font size=5 face="微软雅黑">添加文件</font>

	git add -A  
	git add .  
	git add -u  

参考：  
[difference-between-git-add-a-and-git-add](http://stackoverflow.com/questions/572549/difference-between-git-add-a-and-git-add
)

	git status 
	git commit -a -m "First pages commit"

<font size=5 face="微软雅黑">origin</font>

	git remote
	git remote -v

参考：  
[what-is-origin-in-git](http://stackoverflow.com/questions/9529497/what-is-origin-in-git)








