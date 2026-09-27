# Java · 缓存与 Redis

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

Caffeine 缓存在当前 JVM 内；Redisson 访问外部 Redis。先明确是否需要跨实例共享。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Caffeine](#caffeine) | JVM 本地缓存与淘汰策略 | 17,879 | 近期有提交 |
| [Redisson](#redisson) | Redis 客户端与分布式数据结构 | 24,403 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Caffeine

**适合**：进程内热点数据、计算结果缓存。

**选型提醒**：本地缓存不跨实例共享；必须考虑失效与内存上限。

[源码](https://github.com/ben-manes/caffeine) · [官方文档](https://github.com/ben-manes/caffeine#readme) · [安装入口](https://github.com/ben-manes/caffeine#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/ben-manes/caffeine/commit/9dbafaacecce7c6b361dffbf63d3b4513f859b5a) · 版本与许可证见上游仓库。</sub>

## Redisson

**适合**：Redis 对象操作、分布式协调场景。

**选型提醒**：分布式锁仍需考虑租期、故障与幂等性，不能只依赖 API 名称。

[源码](https://github.com/redisson/redisson) · [官方文档](https://redisson.pro/docs/) · [安装入口](https://github.com/redisson/redisson#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/redisson/redisson/commit/883d9c4e49a7428ee9ccc6a9a633724c892dbb93) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
