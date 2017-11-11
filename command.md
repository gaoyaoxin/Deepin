### cd

|命令|功能|
|-|-|
|cd|进入用户主目录|
|cd ~|进入用户主目录|
|cd -|返回进入此目录之前所在的目录|
|cd ..|返回上级目录（若当前目录为“/“，则执行完后还在“/"；".."为上级目录的意思）|
|cd ../..|返回上两级目录|
|cd !$|把上个命令的参数作为cd参数使用|

### git
|命令|功能|
|-|-|
|git clone URL地址|克隆|
|git pull origin master|将origin版本库中master分支更新到本地当前分支|
|git config --global user.email "you@example.com"|设置身份标识，如果仅在本仓库设置身份标识，则省略 --global 参数|
|git config --global user.name "Your Name"|设置身份标识，如果仅在本仓库设置身份标识，则省略 --global 参数|
|git remote add origin URL|# 关联远程库|
|git push -u origin master|# 首次推送master分支|
|git add .||
|git commit||
|git push origin master|推送最新修改|

\# 可省略
