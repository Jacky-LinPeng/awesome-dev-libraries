# Go · 数据库与本地存储

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

模型驱动选 GORM；手写 SQL 比较 sqlx 与 sqlc；使用 PostgreSQL 原生能力看 pgx。数据库迁移单独管理。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [GORM](#gorm) | ORM、关联关系与数据迁移辅助 | 39,968 | 近期有提交 |
| [sqlx](#sqlx) | 扩展 database/sql 的结构体映射与查询 | 17,744 | 更新较久 |
| [pgx](#pgx) | PostgreSQL 驱动与工具 | 14,272 | 近期有提交 |
| [sqlc](#sqlc) | 从 SQL 生成类型化数据访问代码 | 18,326 | 近期有提交 |
| [golang-migrate](#golang-migrate) | 按版本执行数据库迁移 | 18,942 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## GORM

**适合**：偏好模型驱动 CRUD 的 Go 服务。

**选型提醒**：复杂查询要检查实际 SQL、事务和查询开销。

[源码](https://github.com/go-gorm/gorm) · [官方文档](https://github.com/go-gorm/gorm#readme) · [安装入口](https://github.com/go-gorm/gorm#getting-started)

<sub>默认分支最近提交：2026-09-14 · [近期有提交](https://github.com/go-gorm/gorm/commit/b3d3bf219f0283f8e2e985bac509cb643170f729) · 版本与许可证见上游仓库。</sub>

## sqlx

**适合**：希望自己写 SQL，同时减少扫描代码。

**选型提醒**：它不是 ORM；驱动、事务和 SQL 仍由项目控制。

[源码](https://github.com/jmoiron/sqlx) · [官方文档](https://github.com/jmoiron/sqlx#readme) · [安装入口](https://github.com/jmoiron/sqlx#install)

<sub>默认分支最近提交：2024-05-30 · [更新较久](https://github.com/jmoiron/sqlx/commit/41dac167fdad5e3fd81d66cafba0951dc6823a30) · 版本与许可证见上游仓库。</sub>

## pgx

**适合**：需要使用 PostgreSQL 特性的 Go 服务。

**选型提醒**：专用于 PostgreSQL；按需要选择原生接口或 database/sql 适配。

[源码](https://github.com/jackc/pgx) · [官方文档](https://github.com/jackc/pgx/wiki/Getting-started-with-pgx) · [安装入口](https://github.com/jackc/pgx#quick-start)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/jackc/pgx/commit/e77dc328ac40cbed528b102b7224d0c7379dddc5) · 版本与许可证见上游仓库。</sub>

## sqlc

**适合**：希望在编译期检查 SQL 对应调用结构。

**选型提醒**：属于代码生成工具，需要把生成流程纳入构建。

[源码](https://github.com/sqlc-dev/sqlc) · [官方文档](https://docs.sqlc.dev) · [安装入口](https://github.com/sqlc-dev/sqlc#readme)

<sub>默认分支最近提交：2026-09-13 · [近期有提交](https://github.com/sqlc-dev/sqlc/commit/bdbe55db3ee08745827090d4aad1781bea2ee4ee) · 版本与许可证见上游仓库。</sub>

## golang-migrate

**适合**：开发、测试与生产的结构变更管理。

**选型提醒**：迁移失败处理、回滚和数据备份需由发布流程保障。

[源码](https://github.com/golang-migrate/migrate) · [官方文档](https://github.com/golang-migrate/migrate/blob/master/GETTING_STARTED.md) · [安装入口](https://github.com/golang-migrate/migrate#getting-started)

<sub>默认分支最近提交：2026-09-09 · [近期有提交](https://github.com/golang-migrate/migrate/commit/504568a3cbd23b8754760f55a3d89aec1b0c4963) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
