# Java · 后台任务与并发

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

队列、定时调度和并发控制。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Quartz](#quartz) | 持久化任务调度框架 | 6,754 | 近期有提交 |
| [XXL-JOB](#xxl-job) | 分布式任务调度平台与执行器 | 30,585 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Quartz

**适合**：Java 应用中的定时和周期任务。

**选型提醒**：集群调度需配置共享存储与失败恢复。

[源码](https://github.com/quartz-scheduler/quartz) · [官方文档](https://github.com/quartz-scheduler/quartz#readme) · [安装入口](https://github.com/quartz-scheduler/quartz#readme)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/quartz-scheduler/quartz/commit/3801476e790ea143d8da23c17ca5210262aa6a58) · 版本与许可证见上游仓库。</sub>

## XXL-JOB

**适合**：需要统一管理多服务定时任务的团队。

**选型提醒**：是平台加客户端的整体方案，需要维护调度中心。

[源码](https://github.com/xuxueli/xxl-job) · [官方文档](https://github.com/xuxueli/xxl-job#readme) · [安装入口](https://github.com/xuxueli/xxl-job#readme)

<sub>默认分支最近提交：2026-07-21 · [近期有提交](https://github.com/xuxueli/xxl-job/commit/e74c784f68f81fa89cb350913ef15794865d7b12) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
