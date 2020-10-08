# xwj2020
云计算课程

```JavaScript
console.log("this is README.md");
```

```shell
分支1 ---- 分支2

git switch 分支1

……产生冲突

git merge 分支2 # 尝试合并

……冲突文件无法合并，手动修改冲突文件，并重新提交

git add Hello.js

git commit -m "conflict fixed"

此时已将分支1和分支2合并，不影响分支2。（所有操作仅影响本分支
```

其次，git push 等于 *将本地分支合并到远程分支（远程仓库执行：git merge 本地分支）*，git pull 等于 *将远程分支合并到本地分支（本地仓库执行：git merge 远程分支）*

实例：修改远程分支内容，在本地pull远程分支（无冲突）。

```shell
E:\hbpu\云计算\xwj2020>git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From github.com:NomadJohn/xwj2020
   0cc278c..890de2f  main       -> origin/main
Updating 0cc278c..890de2f
Fast-forward
 README.md | 10 +++++++++-
 1 file changed, 9 insertions(+), 1 deletion(-)
```
