版本回退

阅读: 1192511
现在，你已经学会了修改文件，然后把修改提交到Git版本库，现在，再练习一次，修改readme.txt文件如下：

Git is a distributed version control system.
Git is free software distributed under the GPL.
然后尝试提交：

$ git add readme.txt
$ git commit -m "append GPL"
[master 3628164] append GPL
 1 file changed, 1 insertion(+), 1 deletion(-)
 hei nima 