# Go · 后台任务与并发

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

Asynq 是有外部存储的任务队列；cron 在进程内定时；ants 控制任务并发，三者不可互相替代。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Asynq](#asynq) | 基于 Redis 的后台任务队列 | 13,742 | 近期有提交 |
| [cron](#cron) | 进程内定时任务调度 | 14,189 | 更新较久 |
| [ants](#ants) | 可复用 goroutine 池 | 14,512 | 近期有提交 |
| [gocron](#gocron) | Go 定时任务与调度管理 | 7,169 | 近期有提交 |
| [conc](#conc) | 结构化 goroutine 并发工具 | 10,431 | 更新较久 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Asynq

**适合**：邮件、图片处理、延迟任务与异步作业。

**选型提醒**：任务要设计为幂等，并考虑重试和 Redis 运维。

[源码](https://github.com/hibiken/asynq) · [官方文档](https://github.com/hibiken/asynq/wiki/Getting-Started) · [安装入口](https://github.com/hibiken/asynq#readme)

<sub>默认分支最近提交：2026-06-12 · [近期有提交](https://github.com/hibiken/asynq/commit/d135f1439bee74e989b7f9b41ecd542cc87f024a) · 版本与许可证见上游仓库。</sub>

## cron

**适合**：定时清理、轮询和周期作业。

**选型提醒**：多实例部署会重复执行，需自行协调或使用集中调度。

[源码](https://github.com/robfig/cron) · [官方文档](https://github.com/robfig/cron#readme) · [安装入口](https://github.com/robfig/cron#readme)

<sub>默认分支最近提交：2021-01-06 · [更新较久](https://github.com/robfig/cron/commit/bc59245fe10efaed9d51b56900192527ed733435) · 版本与许可证见上游仓库。</sub>

## ants

**适合**：需要限制任务并发数量的执行场景。

**选型提醒**：不是所有任务都需要池；先明确背压、阻塞和并发上限。

[源码](https://github.com/panjf2000/ants) · [官方文档](https://github.com/panjf2000/ants#readme) · [安装入口](https://github.com/panjf2000/ants#-how-to-install)

<sub>默认分支最近提交：2026-09-19 · [近期有提交](https://github.com/panjf2000/ants/commit/c101e307893f9246aaabc078c8cddaff8884eaec) · 版本与许可证见上游仓库。</sub>

## gocron

**适合**：比基础 cron 表达式更丰富的调度需求。

**选型提醒**：多实例执行仍需考虑分布式协调与幂等性。

[源码](https://github.com/go-co-op/gocron) · [官方文档](https://github.com/go-co-op/gocron#readme) · [安装入口](https://github.com/go-co-op/gocron#quick-start)

<sub>默认分支最近提交：2026-07-17 · [近期有提交](https://github.com/go-co-op/gocron/commit/cc444c2a6f2cb66b51ef180940de6398d1f9a10d) · 版本与许可证见上游仓库。</sub>

## conc

**适合**：并行执行、错误收集和任务生命周期控制。

**选型提醒**：先判断标准库并发原语是否足够。

[源码](https://github.com/sourcegraph/conc) · [官方文档](https://github.com/sourcegraph/conc#readme) · [安装入口](https://github.com/sourcegraph/conc#readme)

<sub>默认分支最近提交：2024-01-21 · [更新较久](https://github.com/sourcegraph/conc/commit/5f936abd7ae87036af1f75c95fb9d0daaf00116b) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
