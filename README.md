# learn_git

Git 学习与实践仓库。

## 目录说明

```
learn_git/
├── .gitignore   # 忽略规则
└── README.md    # 本文件
```

## 常用命令速查

```bash
git status                 # 查看工作区状态
git add <file>             # 暂存指定文件
git add -A                 # 暂存全部改动（含删除）
git commit -m "说明"        # 提交暂存区
git log --oneline --graph  # 查看提交历史
git diff                   # 工作区 vs 暂存区
git diff --staged          # 暂存区 vs 最新提交
```

## 待补充

- [ ] 记录练习用的示例分支与合并场景
- [ ] 补充 rebase / cherry-pick / stash 的实践笔记
