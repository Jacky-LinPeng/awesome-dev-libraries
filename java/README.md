# Java · 开源库导航

[← 返回首页](../README.md) · [全部库索引](../INDEX.md) · [筛选与核验](../research/README.md)

同时覆盖 Android 和 JVM 服务端。Android 专项集中在客户端模块；Spring、数据库连接池等按服务端用途阅读。

> Android / JVM 服务端 · 20 个选型入口 · 1 个历史条目 · 核验于 2026-09-27

## 按业务模块查找

| 模块 | 我要解决什么问题 | 条目数 |
|---|---|---:|
| [网络与通信](networking.md) | 调用 API、上传下载、长连接和协议通信 | 2 |
| [Web 与 API 服务](web.md) | 搭建业务接口、路由与中间件 | 1 |
| [认证、权限与凭据](authentication.md) | 登录凭据、Token 和服务访问控制 | 1 |
| [数据库与本地存储](storage.md) | 离线数据、SQL、事务和结构迁移 | 4 |
| [缓存与 Redis](cache.md) | 本地缓存、Redis 与分布式数据结构 | 2 |
| [数据模型与序列化](serialization.md) | JSON、二进制数据和类型化模型 | 2 |
| [通用工具与对象映射](utilities.md) | 集合工具、数据转换和重复代码消除 | 2 |
| [容错与服务保护](resilience.md) | 重试、熔断、超时和限流 | 1 |
| [Android 客户端](android.md) | 传统 View 图片展示和 Rx 事件处理 | 2 |
| [自动化测试](testing.md) | 测试组织、断言、Mock 和集成验证 | 3 |
| [旧项目维护与迁移](legacy.md) | 已归档、已弃用或需重点评估的历史方案 | 1 |

## 常用路线

- **搭建业务服务**：[Web](web.md) → [数据库](storage.md) → [认证](authentication.md)。
- **提升可靠性**：[缓存](cache.md) → [容错](resilience.md) → [测试](testing.md)。
- **开发 Android 客户端**：[客户端库](android.md) → [共用网络库](../kotlin/networking.md)。

## 官方基础能力

这些是系统或框架入口，单独列出，不计入第三方库数量。

- [Android Jetpack](https://developer.android.com/jetpack)：Android 官方组件；逐项核对 Java API 支持。

## 阅读说明

Star 是核验时的仓库快照。`近期有提交` 只表示默认分支一年内有提交；`更新较久` 不等于已弃用。具体状态与选型提醒见模块页。
