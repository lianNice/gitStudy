git remote add origin git@github.com:michaelliao/learngit.git  ## 下载远程仓库 <br>
git push -u origin master  将本地库推送到远程仓库<br>
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；<br>

关联后，使用命令git push -u origin master第一次推送master分支的所有内容；<br>

此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；<br>


