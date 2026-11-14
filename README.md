# musicx-skills

个人的全局 agent skill，格式遵循 [agentskills.io](https://agentskills.io)。每个 skill 是 `skills/<name>/` 下的一个目录。

| skill | 用途 |
|---|---|
| `mx-writing` | 写或改给人读的中英文文章：汇报与技术报告、知识文档、写给领导和同事的文章、技术公众号长文。来源与取舍见 `skills/mx-writing/references/sources.md` |

## 安装

把 skill 目录链接到 agent 的全局 skill 目录，改这里的文件立即生效：

    ln -s ~/Code/projects/musicx-skills/skills/mx-writing ~/.claude/skills/mx-writing
    ln -s ~/Code/projects/musicx-skills/skills/mx-writing ~/.agents/skills/mx-writing

第一条给 Claude Code，第二条给读 `~/.agents/skills/` 的其他 agent。卸载时删掉这两个链接。

`mx-writing` 最初是 `work_sheet` 项目里的共用规范 `writing`，那一份多一节与引擎配合的说明，两份各自维护。
