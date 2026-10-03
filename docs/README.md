# 文档入口

更新时间：2026-09-27

## 技术维护

- [项目范围与非官方声明](scope.md)：定义统计边界、样本库 vs 全量库、当前留洋样本提示和维护入口。
- [来源政策与冲突处理](source-policy.md)：定义来源优先级、交叉验证、冲突处理、当前注册和未来生效转会口径。
- [数据字典](data-dictionary.md)：解释核心 JSON 文件、生成文件和常用字段。
- [数据流与生成产物](data-flow.md)：raw JSON、site JSON、SQLite、本地预览和 GitHub Pages 的生成链路。
- [SQLite 本地库](sqlite.md)：ER 图、表结构和字段说明。
- [本地开发与故障排查](local-development.md)：Node、`node:sqlite`、Python 静态服务和 Pages 构建失败处理。
- [数据校验脚本](validation.md)：`scripts/validate-data.mjs` 校验什么、不校验什么。
- [Transfermarkt 身价刷新说明](transfermarkt-market-values.md)：外部身价快照的刷新流程、频率和人工复核责任。
- [静态 JSON API 说明](api.md)：`data/site/*.json` 能否作为公开数据接口使用。
- [Release 与数据快照机制](snapshots.md)：月度、赛事节点和口径变更快照的命名、检查和 release 说明。
- [已知限制](known-limitations.md)：非官方、非实时、第三方来源冲突和青年球员资料滞后等使用边界。

## 研究口径

- [数据治理、来源状态与质量控制规则](research/data-governance-and-quality-rules.md)
- [亚洲/中国球员与教练信息收集说明](research/asian-chinese-player-coach-collection.md)
- [日韩 U17/U23 青训路径来源层补充](research/japan-korea-u17-u23-source-layers.md)
- [伊朗及剩余 U20/U23 官方名单来源审计](research/issue-55-iran-remaining-u20-u23-source-audit.md)
- [海外青训、球探与青年球员检索源目录](research/scouting-source-directory.md)
- [比利亚雷亚尔 U19 梯队注册与年龄结构（2026/27）](research/villarreal-u19-registration-2026-27.md)
- [中国足球联赛层级与地方城市联赛说明](research/china-league-pyramid-and-regional-super-leagues.md)
- [中国足协体系、江苏城市联赛与青训路径](research/china-fa-system-and-jiangsu-city-league-youth.md)
- [中国足球体系与 2034 杯赛树](research/china-football-system-and-2034-cup-tree.md)
- [中国 U20 2025 比赛统计](research/china-u20-2025-match-statistics.md)
- [中国 U23 2026 比赛统计](research/china-u23-2026-match-statistics.md)
- [中国青年世界杯球员统计](research/china-youth-world-cup-player-stats.md)
- [中国亚运会男足 2026](research/china-asian-games-men-2026.md)
- [中国职业青训统计 2026](research/china-professional-youth-statistics-2026.md)
- [中国留洋状态模型](research/china-overseas-status-model-issue-15.md)
- [中国基层青训教练](research/china-grassroots-coaches-issue-12.md)
- [中国球员五大联赛出场记录](research/china-big-five-appearance-records.md)
- [亚洲教练扩展](research/asian-coaches-extension.md)
- [上海明日之星冠军杯 2026](research/shanghai-future-star-cup-2026.md)
- [青年欧冠参赛队与观察球员](research/issue-11-uefa-youth-league-entrants.md)
- [青训项目名单与批次](research/issue-10-youth-project-rosters.md)
- [Transfermarkt 身价覆盖](research/transfermarkt-market-value-coverage.md)
- [乌兹别克斯坦青训与留洋路径](research/uzbekistan-youth-development-and-overseas-pathway.md)

## 变更记录

- [CHANGELOG](../CHANGELOG.md)
- [CONTRIBUTING](../CONTRIBUTING.md)
- [SECURITY](../SECURITY.md)
