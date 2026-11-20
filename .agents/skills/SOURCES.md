# Skill 来源与版本

原两份 Skill 收录日期：2026-09-17；find-skills 新增日期：2026-09-22。原文完整保留；项目启用规则写在 AGENTS.md，不对 SKILL.md 原文做删改或合并。

| Skill | 采用版本 | 来源 | 原文 SHA-256 |
|---|---|---|---|
| find-skills | 2026-09-22 核对的官方固定版本；提交 7407f3893ad4dceab546ac002c3ef806e4000c73 | [原始 SKILL.md](https://raw.githubusercontent.com/vercel-labs/skills/7407f3893ad4dceab546ac002c3ef806e4000c73/skills/find-skills/SKILL.md) | C00EEEA0E13E74FE4A9D84BA0A8542205A1B736D65F13134FE1A6647EB14976F |
| grill-me | 原作者自包含历史版，2026-06-10 23:01:44 +08:00；固定提交 694fa30311e02c2639942308513555e61ee84a6f | [原始 SKILL.md](https://raw.githubusercontent.com/mattpocock/skills/694fa30311e02c2639942308513555e61ee84a6f/skills/productivity/grill-me/SKILL.md) | 74147EB6010A65957EFEF2B9E0F0B3FF935C1DEF7FC117697151B1D0F3610556 |

版本选择：2026-09-17 核对的原作者 grill-me 固定提交已把该技能改为调用 grilling 的别名入口。本包采用改为别名前最后一个包含完整流程的 grill-me 文件版本，以保留原技能名称和可独立阅读的原文；这是固定历史快照，不冒充最新版本，也没有拼接不同版本。

两个来源项目均使用 MIT 许可证，许可证原文随各自 Skill 一起保留。grill-me 的许可证来自同一历史提交。find-skills 的许可证来自其原文相同提交。两项 Skill 永久默认启用属于本模板的统一采用政策，不改写技能原始元数据；原文的触发元数据不构成本模板自动停用的依据，执行规则以第三节与 AGENTS.md 为准。

来源核对：

- [find-skills 的固定版本许可证](https://raw.githubusercontent.com/vercel-labs/skills/7407f3893ad4dceab546ac002c3ef806e4000c73/LICENSE)

- [grill-me 的历史许可证](https://raw.githubusercontent.com/mattpocock/skills/694fa30311e02c2639942308513555e61ee84a6f/LICENSE)
- [grill-me 已核对的别名入口快照](https://github.com/mattpocock/skills/blob/959a8e9f1edc3adbe2f7e3054bb6fbefa6696260/skills/productivity/grill-me/SKILL.md)

随包路径：.agents/skills/find-skills/SKILL.md、.agents/skills/find-skills/LICENSE、.agents/skills/grill-me/SKILL.md、.agents/skills/grill-me/LICENSE。升级时重新核对来源和许可，同步更新本文件、本模板包第十一节内嵌原文与独立文件，校验一致后再交付；模板包在配套 ZIP 中名为 README.md，手工提取时不要求项目另有同名说明文件。

find-skills 采用规则：每项新任务及关键范围变化先查已有技能，无适用才查公开来源；同任务沿用有效结论。原文中的公开榜单优先属于公开检索阶段，安装命令不构成自动安装授权；未找到技能继续任务，检索失败如实记录，不假装完成。
