# Git Cheat Sheet

    
Git Cheat Sheet 是一个快速参考指南，包含了常用的 Git 命令和操作。它可以帮助开发者快速查找和使用 Git 命令，提高工作效率。以下是一些常用的 Git 命令和操作：

### 基本命令

- **初始化仓库**
  ```bash
  git init
  ```

- **克隆仓库**
  ```bash
  git clone <repository_url>
  ```

- **查看仓库状态**
  ```bash
  git status
  ```

- **添加文件到暂存区**
  ```bash
  git add <file>
  git add .
  ```

- **提交更改**
  ```bash
  git commit -m "commit message"
  ```

- **查看提交历史**
  ```bash
  git log
  ```

### 分支操作

- **创建新分支**
  ```bash
  git branch <branch_name>
  ```

- **切换分支**
  ```bash
  git checkout <branch_name>
  ```

- **创建并切换到新分支**
  ```bash
  git checkout -b <branch_name>
  ```

- **合并分支**
  ```bash
  git merge <branch_name>
  ```

- **删除分支**
  ```bash
  git branch -d <branch_name>
  ```

### 远程操作

- **查看远程仓库**
  ```bash
  git remote -v
  ```

- **添加远程仓库**
  ```bash
  git remote add <name> <url>
  ```

- **拉取远程仓库的更改**
  ```bash
  git pull <remote> <branch>
  ```

- **推送更改到远程仓库**
  ```bash
  git push <remote> <branch>
  ```

### 其他常用命令

- **查看差异**
  ```bash
  git diff
  ```

- **暂存当前更改**
  ```bash
  git stash
  ```

- **应用暂存的更改**
  ```bash
  git stash apply
  ```

- **查看暂存的更改**
  ```bash
  git stash list
  ```

这些命令涵盖了 Git 的基本操作和一些常用的高级操作。Git Cheat Sheet 可以帮助你快速找到所需的命令，提高工作效率。
    