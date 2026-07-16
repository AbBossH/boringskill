# boringskill

公开的 BoringSkill / Hermes Skill 源库。

员工无需安装额外的 Hermes 包：在已经安装 Hermes Agent 的电脑中，发送 [`prompts/员工安装并自动更新提示词.md`](prompts/员工安装并自动更新提示词.md) 即可下载当前全部公司 Skill，并建立 Hermes 原生定时更新。

## 当前 Skill

- `heidong-scene-image-generation`：家具场景图生成工作流。

## 发布约定

- 每项 Skill 位于 `skills/<skill-name>/SKILL.md`。
- Skill 名称使用 `heidong-` 前缀，避免覆盖员工的个人 Skill。
- `catalog.json` 是员工安装提示词读取的唯一清单。
- 修改已安装 Skill 的内容后，Hermes 的原生 `skills update` 会从同一 GitHub Raw URL 更新它。
- 新增 Skill 后，已安装用户在下一次运行同一份员工提示词时会安装新增项。

## 公开边界

本仓库内容永久公开。不得提交账号、密码、Token、私钥、客户资料、内部网址或任何受限素材。
