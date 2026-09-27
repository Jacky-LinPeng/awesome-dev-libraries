# Kotlin · 数据库与本地存储

[← Kotlin 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

离线数据、SQL、事务和结构迁移。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [SQLDelight](#sqldelight) | 从 SQL 生成类型安全 Kotlin API | 6,886 | 近期有提交 |
| [MMKV](#mmkv) | 基于内存映射的键值存储 | 18,748 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## SQLDelight

**适合**：需要共享 SQL 数据层的 Kotlin 项目。

**选型提醒**：必须选择正确驱动；Android 单端也可评估官方 Room。

[源码](https://github.com/sqldelight/sqldelight) · [官方文档](https://sqldelight.github.io/sqldelight/) · [安装入口](https://github.com/sqldelight/sqldelight#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/sqldelight/sqldelight/commit/ae52be32ed1670322205cea63bef6da44ec345bf) · 版本与许可证见上游仓库。</sub>

## MMKV

**适合**：偏好设置和轻量业务状态持久化。

**选型提醒**：2.x 对架构和 Android 最低版本有要求，旧设备按官方 LTS 路线选择；Kotlin Multiplatform 支持仍标为实验性。

[源码](https://github.com/Tencent/MMKV) · [官方文档](https://github.com/Tencent/MMKV#readme) · [安装入口](https://github.com/Tencent/MMKV#getting-started)

<sub>默认分支最近提交：2026-08-21 · [近期有提交](https://github.com/Tencent/MMKV/commit/ad7657ef9d120dbcdd7432d75aa6c59391149b22) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Kotlin](README.md) · [查看调研记录](../research/README.md)
