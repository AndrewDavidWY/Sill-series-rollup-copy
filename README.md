# 系列易拉宝文案策划

把旧会议材料与新增参考融合为有顺序的系列易拉宝文案，控制文字密度并保持具体内容；适用于展架、系列展板的内容策划。

## 安装

将本仓库完整下载或克隆到 Codex 技能目录，文件夹名使用 `series-rollup-copy`：

```sh
git clone https://github.com/AndrewDavidWY/Sill-series-rollup-copy.git ~/.codex/skills/series-rollup-copy
```

如果目标文件夹已存在，先保留已有修改，再决定是否更新。重新打开聊天后，检查技能列表。

## 使用

在 Codex 中使用 `$series-rollup-copy` 调用，并提供本次任务的资料与要求。技能会先读取配套经验记录，再按当前任务开展工作。

## 文件

- `SKILL.md`：适用范围、工作方法与验收要求。
- `agents/openai.yaml`：技能在界面中的名称与简介。
- `references/lessons.md`：历史经验及其来源边界。

## 来源与使用边界

来自《协作经验 Skills 六件套》（2026-10-19）。历史案例中的日期、尺寸、配色和项目状态只作参考；每次执行以当前项目资料与用户要求为准。无需访问原聊天或私有项目，也不附带原项目素材。
