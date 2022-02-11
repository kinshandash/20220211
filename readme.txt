https://blog.csdn.net/u011535541/article/details/83379151?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522164454892516780265443771%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=164454892516780265443771&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-83379151.pc_search_insert_es_download&utm_term=git%E6%95%99%E7%A8%8B&spm=1018.2226.3001.4187
git init
git add readme.txt
git commit -m "new create readme.txt"
git status
git diff readme.txt
git log
git log --pretty=oneline

git reset --hard HEAD^
cat
touch
vi i wq!

git checkout -- readme.txt 丢弃工作区的修改
rm b.txt
git checkout -- b.txt  在版本库中恢复此文件


ssh-keygen -t rsa –C “youremail@example.com”
git remote add origin https://github.com/tugenhua0707/testgit.git
git push -u origin master 加上了 –u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令
git push origin maste
git clone https://github.com/tugenhua0707/testgit.git

git checkout -b dev same as below 2 cmd:
git branch dev
git checkout dev

git checkout master
git merge dev
git branch -d dev       :del dev
查看分支：git branch
创建分支：git branch name
切换分支：git checkout name
创建+切换分支：git checkout –b name
合并某分支到当前分支：git merge name
删除分支：git branch –d name