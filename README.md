git clone https://github.com/tianjino1/SpringCloud-test.git

git add README.md

git commit -m 'first_commit'

git remote add origin https://github.com/tianjino1/SpringCloud-test.git

跟踪项目文件夹中的所有文件和文件夹
$ git add . 

输入本次的提交说明，准备提交暂存区中的更改的已跟踪文件，单引号内为说明内容

$ git commit -m 'first_commit'

关联远程仓库，添加后，远程库的名字就是 origin，这是 Git 默认的叫法，也可以改成别的，但是 origin 这个名字一看就知道是远程库。

$ git remote add origin https://github.com/tianjino1/SpringCloud-test.git

如果关联出现错误 fatal: remote origin already exists，则执行下列语句再进行关联

git remote rm origin

把本地库的所有内容推送到远程库上

$ git push -u origin master

如果在推送时出现错误 error:failed to push som refs to.......，则执行下列语句

git pull origin master

将远程仓库 Github 上的文件拉下来合并之后重新推送上去

删除

git rm -rf file
git commit -m 'remove'
git push -u origin master

![picture](http://img.zcool.cn/community/0117e2571b8b246ac72538120dd8a4.jpg@1280w_1l_2o_100sh.jpg)
