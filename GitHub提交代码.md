## 提交新代码
1. cd 本地项目文件夹
2. git init
3. git add .
4. git commit -m "提交注释"
5. git remote add origin https://github.com/juezhan/项目名.git
6. git push -u origin master	// 提交到主分支
7. git config user.email "注册邮箱"
8. git config user.name "用户名"

## 更新代码
1. git status   
    查看修改了哪些文件
1. git add -A
    将新增修改的文件到缓存列表
2. git commit -m "提交注释"
3. git push -u origin master:master
    提交到主分支
5. git config user.email "注册邮箱"
6. git config user.name "用户名"
