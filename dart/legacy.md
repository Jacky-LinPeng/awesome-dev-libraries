# Dart · 旧项目维护与迁移

[← Dart 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

> 本页用于识别旧依赖和安排迁移。已归档、已弃用与长期低频更新分别标注；这些条目不进入新项目速查路线。


## 历史维护 · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Isar 原仓库](#isar-原仓库) | 嵌入式对象数据库 | 4,023 | 更新较久 |
| [Hive 原仓库](#hive-原仓库) | 轻量键值/对象存储 | 4,389 | 更新较久 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Isar 原仓库

**适合**：维护已有 Isar 数据与调用代码。

**选型提醒**：README 明确标注 v4 不适用于生产；原仓库更新较久，现有项目先核对稳定版与迁移来源。

[源码](https://github.com/isar/isar) · [官方文档](https://github.com/isar/isar#readme) · [安装入口](https://github.com/isar/isar#readme)

<sub>默认分支最近提交：2025-06-14 · [更新较久](https://github.com/isar/isar/commit/713001bf1615ea15460d9bc8d3fb9c8cb4150a2e) · 版本与许可证见上游仓库。</sub>

## Hive 原仓库

**适合**：维护已有 Hive 本地数据。

**选型提醒**：先核对原仓库维护状态、迁移路径和目标 SDK 兼容性。

[源码](https://github.com/isar/hive) · [官方文档](https://github.com/isar/hive#readme) · [安装入口](https://github.com/isar/hive#readme)

<sub>默认分支最近提交：2023-08-25 · [更新较久](https://github.com/isar/hive/commit/1b4febe967370f790759823a5e154adc383e53d3) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Dart](README.md) · [查看调研记录](../research/README.md)
