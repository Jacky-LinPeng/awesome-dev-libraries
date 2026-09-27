# Swift · 数据库与本地存储

[← Swift 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

需要 SQL 控制、观察与迁移能力看 GRDB；偏好链式查询表达式看 SQLite.swift。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [GRDB.swift](#grdbswift) | SQLite 查询、事务、迁移与数据库观察 | 8,666 | 近期有提交 |
| [SQLite.swift](#sqliteswift) | 类型安全的 SQLite 查询表达式 | 10,189 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## GRDB.swift

**适合**：离线业务、复杂查询、需要可控 SQL 的应用。

**选型提醒**：数据库方案按项目需求择一；设计并测试版本迁移。

[源码](https://github.com/groue/GRDB.swift) · [官方文档](https://github.com/groue/GRDB.swift#readme) · [安装入口](https://github.com/groue/GRDB.swift#readme)

<sub>默认分支最近提交：2026-08-08 · [近期有提交](https://github.com/groue/GRDB.swift/commit/0d8cf958b4b66a0473ec6e6986eb9da462171da9) · 版本与许可证见上游仓库。</sub>

## SQLite.swift

**适合**：偏好 Swift 链式 API 操作关系型数据。

**选型提醒**：适合 SQL 数据建模；不是跨端云同步服务。

[源码](https://github.com/stephencelis/SQLite.swift) · [官方文档](https://github.com/stephencelis/SQLite.swift/blob/master/Documentation/Index.md) · [安装入口](https://github.com/stephencelis/SQLite.swift#installation)

<sub>默认分支最近提交：2026-09-22 · [近期有提交](https://github.com/stephencelis/SQLite.swift/commit/989fa8d73c2f574ee3e7b5d68e432d94c81ee945) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Swift](README.md) · [查看调研记录](../research/README.md)
