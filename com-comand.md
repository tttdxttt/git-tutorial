
git status，查询仓库状态；
git init，初始化仓库；
git add，添加文件；
git commit，提交文件；
git log，查询提交日志；
git branch，拉分支；
git checkout，切换分支或者标签；
git merge，合并分支；
git branch -d & git branch -D，删除或者强制删除分支；
git tag，添加标签。

echo "# Cpp_learn" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tttdxttt/Cpp_learn.git
git push -u origin main
When you push a new branch the first time use: >git push -u origin

After that, you can just type a shorter command: >git push

The first-time -u option created a persistent upstream tracking branch with your local branch.