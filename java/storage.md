# Java · 数据库与本地存储

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

MyBatis 偏向手写 SQL，MyBatis-Plus 增强其 CRUD；Hibernate 偏向 ORM。HikariCP 是连接池，可与这些方案配合。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [MyBatis](#mybatis) | SQL 与 Java 对象映射 | 20,446 | 近期有提交 |
| [MyBatis-Plus](#mybatis-plus) | 为 MyBatis 增加常用 CRUD 能力 | 17,476 | 近期有提交 |
| [Hibernate ORM](#hibernate-orm) | 实体映射、关联关系与 ORM 持久化 | 6,470 | 近期有提交 |
| [HikariCP](#hikaricp) | JDBC 连接池 | 21,230 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## MyBatis

**适合**：希望直接控制 SQL 的关系型数据库应用。

**选型提醒**：需自行管理 SQL 质量、分页与查询数量。

[源码](https://github.com/mybatis/mybatis-3) · [官方文档](https://github.com/mybatis/mybatis-3#readme) · [安装入口](https://github.com/mybatis/mybatis-3#readme)

<sub>默认分支最近提交：2026-09-19 · [近期有提交](https://github.com/mybatis/mybatis-3/commit/34147d0bd2f5ed0016ef367c92b25e174149326b) · 版本与许可证见上游仓库。</sub>

## MyBatis-Plus

**适合**：以 MyBatis 为基础的管理后台与业务系统。

**选型提醒**：属于 MyBatis 的增强层，复杂 SQL 仍需自行设计。

[源码](https://github.com/baomidou/mybatis-plus) · [官方文档](https://baomidou.com) · [安装入口](https://github.com/baomidou/mybatis-plus#getting-started)

<sub>默认分支最近提交：2026-08-03 · [近期有提交](https://github.com/baomidou/mybatis-plus/commit/bf67d907478c724120bf76292da54abf9e73c2b3) · 版本与许可证见上游仓库。</sub>

## Hibernate ORM

**适合**：采用 JPA 模型的 Java 服务。

**选型提醒**：注意懒加载、N+1 查询和事务边界。

[源码](https://github.com/hibernate/hibernate-orm) · [官方文档](https://hibernate.org/orm/documentation) · [安装入口](https://github.com/hibernate/hibernate-orm#getting-started)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/hibernate/hibernate-orm/commit/e1f9fc665890067291278b67d3356b1e6754e554) · 版本与许可证见上游仓库。</sub>

## HikariCP

**适合**：关系型数据库服务的连接复用。

**选型提醒**：Spring Boot 可能已提供；连接数应结合数据库容量设置。

[源码](https://github.com/brettwooldridge/HikariCP) · [官方文档](https://github.com/brettwooldridge/HikariCP#readme) · [安装入口](https://github.com/brettwooldridge/HikariCP#readme)

<sub>默认分支最近提交：2026-06-14 · [近期有提交](https://github.com/brettwooldridge/HikariCP/commit/a4d93f4f85517f90e632b795486d7102e933d7ff) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
