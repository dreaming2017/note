# git命令:

## 1创建分支

- 在本地新建一个分支： git branch newBranch
- 切换到你的新分支: git checkout newBranch
- 将新分支发布在github上： git push origin newBranch

## 2 删除分支

在本地删除一个分支： git branch -d newBranch

在github远程端删除一个分支： git push origin :newBranch (分支名前的冒号代表删除)
git push origin –delete newBranch
注意删除远程分支后，如果有对应的本地分支，本地分支并不会同步删除！