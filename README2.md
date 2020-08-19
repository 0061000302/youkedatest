git remote -v查看绑定情况

git add

git add -A

git add .命令和上面的命令效果是一样的，-A的意思就是全部all

git commit

git commit -m "本次提交的修改的备注"

新创建的文件必须按照顺序进行提交，如果只是修改了文件，并没有创建文件，也可以使用git commit -am "本次修改的备注"来合并前两个步骤

git push

git push分为几种情形：

- 第一次提交到本地分支
- 第2-n次提交到本分支
- 提交到其他分支

第一次提交到本地分支

git push origin master

origin是远程仓库的默认名称，master是我们的分支名称（主分支）。

git pull

在实际应用中，有时候会出现本地仓黑人线上仓库不一致的情况，比如本地内容是[1,2]，线上的内容是[2,3]。这个时候我们需要使用"git pull"命令来抓取远程仓库的内容
