1. git clone https://github.com/dashuaishuaiwoaini/test 克隆master代码
2. git clone -b feature/xxx https://github.com/dashuaishuaiwoaini/test 克隆feature/xxx分支代码
3. git checkout feature/xxx 切换分支
4. git checkout -b feature/xxx 新建名为feature/xxx的分支并切换到此分支
5. git add . 
6. git commit -m feat: xxx 
7. git push
8. git branch 查看本地分支
9. git branch -a 查看远程分支
10. git branch -D feature/xxx 删除名为feature/xxx的本地分支
11. git push origin --delete 删除远程分支
12. git merge feature/xxx 合并指定分支到当前分支
13. git status 当前状态
14. git pull 拉取远程代码到本地
15. git log 提交日志
16. git reset --hard HEAD^ 回滚到上一个commit
17. git reset --hard commit_id 回滚指定的commit
18. git revert commit_id 已经提交到仓库，回滚