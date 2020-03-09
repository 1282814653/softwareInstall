# git 

## 首先 生成 git 秘钥
1. $ ssh-keygen -t rsa -C "邮箱地址"
2. 按3个回车，密码为空。
3. 找到生成的两个文件 找到生成的 秘钥 复制到github 中
4. 就建立连接了 

## 基本操作 
1.  git init // 仓库初始化
2.  git add . // 添加所有数据
3.  git commit -m'信息介绍' // 提交介绍
4.  git push origin master // 推送本地代码到远程
5.  git pull origin master // 获取远程代码到本地更新本地代码
6.  git log  //查看历史记录
7.  git reset --hard  'axasdfsadf' // 回到某个版本
8.  git branch  xx // 创建xx分支
9.  git branch -v   // 查看所有分支
10. git checkout xx  // 切换分支
11. git merge  xxx(分支名)  // 把xxx合并到当前分支
12. git branch -d xxx(分支名) // 删除xxx分支
13. git remote add origin https://dizhi.git  // 添加远程关联 https/ssh 两种模式
14.  git remote -v   // 查看远程源
15. git remote remove origin   // 删除远程关联
16. git push -u origin master  // 推送到远程 只有第一次需要写 -u
17. git pull //  获取远程内容/ 合并远程内容到本地 如果远程出现了更新,必须先pull再commit再push


