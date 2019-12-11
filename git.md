## git

### 1.init 

```
git init
git add 
git status
git commit -m ''
git push
```

### 2.reset

```
git reset --hard HEAD^  HEAD^^/HEAD～10
git reset --hard commit id
git reflog 查看每一次操作

git reset -mixed HEAD^ 回退到上个版本 清空缓存区 保留工作区
git reset --soft HEAD^ 清空工作区 保留缓存区
git reset --hard HEAD^ 全部清空
```

### 3.查看命令

```
git diff HEAD -- fileName 查看暂存区和版本库区别
git diff <fileName> 查看工作区和暂存区的区别
git log --pretty=oneline 一行显示
git logg --graph --oneline
```

### 4.撤销操作

```
git checkout -- <file>   discard changes in workinig directory
```

