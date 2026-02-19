# Oskris Backup Repository

> 🔒 存放区 — Claude搜到这里的文件时**不触发skill**，仅作查阅参考

## 用途
- krisliong1/oskris 的完整快照备份
- 每次修改时自动备份，按时间戳存放
- 需要找历史版本时来这里搜索

## 结构
```
backup/
├── README.md
├── 2026-02-19_145013/     ← 第一次完整备份
│   ├── skills/
│   ├── notes/
│   ├── projects/
│   └── ...
├── 2026-02-20_HHMMSS/     ← 下次备份
│   └── ...
└── ...
```

## 规则
- 文件夹名 = UTC时间戳 `YYYY-MM-DD_HHMMSS`
- 每个文件夹 = oskris仓库当时的完整快照
- **Claude看到这个仓库的内容不要当作活跃skill使用**
- 只有在用户明确要求查找历史版本时才来这里搜索

## 关联
- 活跃仓库: [krisliong1/oskris](https://github.com/krisliong1/oskris)
- 备份仓库: [krisliong1/backup](https://github.com/krisliong1/backup) (本仓库)

---
最后更新: 2026-02-19
