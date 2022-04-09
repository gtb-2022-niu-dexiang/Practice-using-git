# Practice-using-git

## Git的使用
（两步：配置用户信息和上传）
参考：https://www.cnblogs.com/l199616j/p/10103246.html
1、配置信息
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/ndx2527/test.git
git push -u origin master
2、其它操作
git pull ————重新拉取
git reset --soft HEAD^  ————撤销暂存
git checkout master ————切换分支

3、Git提交规范
feat：新功能
fix：修复bug
