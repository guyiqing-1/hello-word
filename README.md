#git的日常 
``` 
git config  
git clone  
git add 文件路径: 添加指定文件
git commit -m 'msg' : 把添加的指定文件,提交到指定文件夹中

git commit -m 'change file' : 提交并更改文件


``` 


## 添加一个HTML文件 
 
*** git add . ***  添加全部文件 

- git status : 查看当前没有提交到暂存区的，但是已修改的文件。

***git  log*** 查看已经提交的操作日志  (按上,再按q，就可以回到指令行)

***git reset HEAD 文件路径*** : 把该文件回退一个版本

***git reset --hard 文件名*** : 回退上一个或上多个版本。在最末尾添加 ^或~ 符号。   ^ ：^的个数代表回退的版本数。  ~数字：数字是几，就回退几个版本。

***git reflog*** ： 查看历史版本

***git reset --herd 版本号*** ： 回退到指定版本

