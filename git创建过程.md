1.创建仓库

  git init 文件夹目录 ：它将会被作为本地仓库使用，稍后它会被推送到github仓库 

​      init：将转化为一个github仓库

 cd 该目录

2.新建文件描述 gedit READEME

3.将仓库里的文件加入一个索引    git  add 将任意数量的文件和目录加入到索引 

 索引：是指有一定空间的缓冲区，这个缓冲区存储了所有已经被加入到git仓库的文件或目录

4.git commit -m "some_message":"some_message"在命令里可以是一些简单的信息如：“我第一次提交”或者“编辑了readme文件”，等等

5.在github创建一个仓库 仓库名字必须和本地创建的仓库名字一致

6.git remote add origin https://github.com/LINTOO/Mytest.git 连接到github仓库

7.git push origin master