# Git 的使用

## Q1

Git 是一个广泛使用的版本管理工具，适合团队开发。  
如果你用过 Git，那么请回忆一下，  
我们在确认开发需求之后，从写代码到提交进团队的代码仓库。  
这个过程中大概会用到哪几条命令？

请直接在这里作答。

答：
   git clone repo-URL
   git switch -c new-branch
   git add .
   git commit
   git push origin new-branch

## Q2

你知道和用过哪些 Git 的方法论和技巧

答：给常用的命令起别名, 如:
    git config --global alias.st status
	  git config --global alias.co checkout
	  git config --global alias.ci commit
	  git config --global alias.br branch
