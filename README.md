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
