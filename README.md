# OpenClaw 共享记忆仓库

这是用于OpenClaw多设备协作的共享记忆仓库。

## 目录结构

- `daily/` - 每日记录
- `projects/` - 项目状态和决策
- `shared/` - 共享上下文和知识库
- `messages/` - 设备间留言板
- `SYNC.md` - 同步状态记录

## 同步脚本

使用 `scripts/sync-memory.sh` 进行同步：

```bash
# 同步并显示最新内容
bash sync-memory.sh sync

# 推送本地更改
bash sync-memory.sh push

# 写入今日记录
bash sync-memory.sh write "内容"

# 显示当前状态
bash sync-memory.sh status
```

## Heartbeat自动化

配置 `HEARTBEAT.md` 实现定时自动同步。
