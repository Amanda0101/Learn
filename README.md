github上已经有repository 和master分支
本地创建了maven项目，准备和远程的repository 的master 绑定到一起。 操作方法如下：

本地maven项目，
git init #初始本项目为git库
git remote add origin <git url>  #添加git url为远程的origin
git add .  #本地改动点 add到缓存
git commit -m 'commit modify' # 添加备注
git branch --set-upstream-to=origin/master master # 把远端的master和本地的master 关联上

把远端的master checkout到本地：git checkout master

git pull #和远端拉起

git push --set-upstream origin master  #推送到 origin

