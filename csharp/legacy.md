# C# · 旧项目维护与迁移

[← C# 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

> 本页用于识别旧依赖和安排迁移。已归档、已弃用与长期低频更新分别标注；这些条目不进入新项目速查路线。


## 历史维护 · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [UniRx](#unirx) | 历史 Unity 响应式编程库 | 7,325 | 已归档 |
| [FASTER](#faster) | 高性能键值存储引擎 | 6,635 | 停止积极维护 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## UniRx

**适合**：维护已有 UniRx 事件与状态逻辑。

**选型提醒**：上游已归档，并推荐后继 R3；新项目优先评估后继方案。

[源码](https://github.com/neuecc/UniRx) · [官方文档](https://github.com/neuecc/UniRx#readme) · [安装入口](https://github.com/neuecc/UniRx#readme)

<sub>默认分支最近提交：2024-02-16 · [已归档](https://github.com/neuecc/UniRx/commit/6baeccf6c544c155497164327cca72f28163a578) · 版本与许可证见上游仓库。</sub>

## FASTER

**适合**：.NET 服务和工具的存储研究与接入。

**选型提醒**：官方已停止积极维护，并指向 Garnet / Tsavorite 等后继方向；不作为新项目默认方案。

[源码](https://github.com/microsoft/FASTER) · [官方文档](https://github.com/microsoft/FASTER#readme) · [安装入口](https://github.com/microsoft/FASTER#readme)

<sub>默认分支最近提交：2026-08-19 · [停止积极维护](https://github.com/microsoft/FASTER/commit/321d872eabda6a0345c8bd76419f89723ed864ae) · 版本与许可证见上游仓库。</sub>

---

[← 返回 C#](README.md) · [查看调研记录](../research/README.md)
