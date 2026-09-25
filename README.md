# git-team-workflow-2026
Git 分支、Pull Request、代码审查与合并练习

## 协作流程

贡献者从 `main` 创建功能分支，在分支上提交修改并发起 Pull Request。仓库所有者审查后，贡献者继续在原分支修改，最后由所有者合并到 `main`。

## 合并后验证

A 和 B 分别在自己的本地仓库执行以下命令，更新 `main` 并查看包含功能分支及合并提交的历史：

```bash
git switch main
git pull origin main
git log --graph --oneline --all
```
