# git的一些备忘录[自用]

1. 初始化一个仓库

```bash
git init
```

2. 添加一些文件到暂存区 用 . 表示当前目录下所有文件

```bash
git add .
```

3. 做一次提交

```bash
git commit -m "<your message>"
```

4. 查看历史

```bash
git reflog
```

5. 回退

```bash
git reset <params>
```

6. 提交到远程仓库

github会给出操作流程

```bash
git remote add origin <link_of_remote_repo>
git branch -M main
git push -u origin main
```
