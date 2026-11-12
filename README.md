# 去套话编辑

`write-edit-declutter-prose` 是一个中英文写作编辑 skill，适合润色文章、口播稿和说明文字。它删去空泛铺垫、重复和模板句式，同时保留事实、限定条件和作者语气。也可以请它审阅稿件，或依据给定事实起草。

## 安装到 Codex

1. 下载并解压或克隆本仓库，确保目录名为 `write-edit-declutter-prose`。
2. 将整个目录放入项目的 `.agents/skills/`，使入口文件位于 `.agents/skills/write-edit-declutter-prose/SKILL.md`。如需在所有项目中使用，可放入 `~/.agents/skills/`。
3. 在 Codex 中调用 `$write-edit-declutter-prose`，附上原文和修改要求。[OpenAI 官方安装文档](https://learn.chatgpt.com/docs/build-skills)

## 使用示例

```text
使用 $write-edit-declutter-prose 润色下面的文字，保留事实和限定条件，直接给出改稿。

需要强调的是，如果试点完成，预计下月仅向 20 名管理员开放。
```

可能的改稿

> 如果试点完成，预计下月仅向 20 名管理员开放。

如果只想听修改意见，可以说「使用 `$write-edit-declutter-prose` 审阅这篇稿件，指出空泛或重复的地方并给出改法」。更多中英文示例见[改写示例](references/examples.md)，完整编辑规则见 [SKILL.md](SKILL.md)。

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
