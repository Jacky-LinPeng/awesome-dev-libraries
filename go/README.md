# Go · 开源库导航

[← 返回首页](../README.md) · [全部库索引](../INDEX.md) · [筛选与核验](../research/README.md)

围绕业务 API、微服务和开发工具选型。项目已使用 go-zero 时，先检查框架是否已有相应能力，再增加依赖。

> 服务端 / CLI · 27 个选型入口 · 1 个历史条目 · 核验于 2026-09-27

## 按业务模块查找

| 模块 | 我要解决什么问题 | 条目数 |
|---|---|---:|
| [Web 与 API 服务](web.md) | 搭建业务接口、路由与中间件 | 4 |
| [微服务与 RPC](microservices.md) | 代码生成、服务治理与跨语言调用 | 3 |
| [数据库与本地存储](storage.md) | 离线数据、SQL、事务和结构迁移 | 5 |
| [缓存与 Redis](cache.md) | 本地缓存、Redis 与分布式数据结构 | 1 |
| [认证、权限与凭据](authentication.md) | 登录凭据、Token 和服务访问控制 | 2 |
| [后台任务与并发](jobs.md) | 队列、定时调度和并发控制 | 3 |
| [网络与通信](networking.md) | 调用 API、上传下载、长连接和协议通信 | 2 |
| [日志、调试与工程质量](tooling.md) | 定位问题、分析性能和统一代码规范 | 3 |
| [配置与工具链](configuration.md) | 应用配置、命令行或游戏策划表 | 2 |
| [参数校验](validation.md) | 请求字段和配置规则校验 | 1 |
| [自动化测试](testing.md) | 测试组织、断言、Mock 和集成验证 | 1 |
| [旧项目维护与迁移](legacy.md) | 已归档、已弃用或需重点评估的历史方案 | 1 |

## 常用路线

- **使用现有 go-zero 技术栈**：[微服务](microservices.md) → [存储](storage.md) → [任务](jobs.md)。
- **搭建轻量 API**：[Web](web.md) → [校验](validation.md) → [认证](authentication.md)。
- **补齐工程能力**：[配置](configuration.md) → [日志与指标](tooling.md) → [测试](testing.md)。

## 官方基础能力

这些是系统或框架入口，单独列出，不计入第三方库数量。

- [Go 标准库](https://pkg.go.dev/std)：net/http、database/sql、log/slog、testing 等基础能力。

## 阅读说明

Star 是核验时的仓库快照。`近期有提交` 只表示默认分支一年内有提交；`更新较久` 不等于已弃用。具体状态与选型提醒见模块页。
