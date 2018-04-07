**创建新仓库**
echo "# my-work-document" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin git@github.com:zrjseven/my-work-
document.git

git push -u origin master

下面把它换成ssh方式的

git remote rm origin

git remote add origin git@github.com:xxxxx/xxxx.git

git push -u origin master