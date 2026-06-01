# Claude Code Skills

个人 Claude Code skill 合集。

## 可用 Skills

| Skill | 版本 | 说明 |
|-------|------|------|
| [adaptive-review](skills/adaptive-review/) | v2.1 | 自适应多智能体评审：根据任务复杂度和风险因子自动调整评审深度，支持三种协作模式、自适应镜头、证据分级、误报抑制 |

## 安装

将 `skills/` 目录下的 skill 文件夹复制到 `~/.claude/skills/` 即可使用：

```bash
cp -r skills/adaptive-review ~/.claude/skills/
```

## Skill 结构约定

```
skills/
  <skill-name>/
    SKILL.md                    # 主文件（skill 入口）
    references/                 # 参考文档（模式选择、轮次协议、prompt 模板等）
    assets/                     # 资源文件（画布模板等）
```
