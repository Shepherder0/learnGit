# learnGit Day1
### 代码记录
1.  git config --global user.name "name"
2.  git config --global user.email "email"
3.  pwd --查看当前文件路径
4.  git init --把这个目录变成Git可以管理的仓库
5.  git checkout -- filrname   --想直接丢弃工作区的修改时使
6.  git remote add origin git@server-name:path/repo-name.git  --关联远程库
7.  git push -u origin master   --第一次推送master分支所有内容
8.  git push origin master  --之后的推送使用这个即
9.  git branch dev  --新建dev分支
10. git checkout dev  --切换到dev分支
11. git checkout -b dev  --新建并切换到dev分支,合并9,10的操
12. git merge dev  --合并dev分
13. git branch -d dev  -- 删除dev分支
14. git log --graph  --查看分支合
15. git tag <tagname>  --新建一个标签名，默认为head，可以指定一个commit id
16. git tag -a <tagname> -m "intraduce"  --指定标签信息
17. git tag  --查看所有标签
18. git push origin <tagname>  --推送一个本地标签到远程
19. git push origin --tags  --推送全部未推送的标签到远程
20. git tag -d <tagname>  --删除一个本地标签，似乎-d就是删除操作？
21. git push origin :refs/tags/<tagname>  --删除一个远程标
