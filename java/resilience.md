# Java · 容错与服务保护

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

重试、熔断、超时和限流。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Resilience4j](#resilience4j) | 熔断、重试、限流与隔离 | 10,765 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Resilience4j

**适合**：调用远端服务时控制故障扩散。

**选型提醒**：重试必须结合幂等性和总体超时预算。

[源码](https://github.com/resilience4j/resilience4j) · [官方文档](https://resilience4j.readme.io/docs) · [安装入口](https://github.com/resilience4j/resilience4j#readme)

<sub>默认分支最近提交：2026-09-23 · [近期有提交](https://github.com/resilience4j/resilience4j/commit/7e3ab5252ed380b596e25240f19376a4435570b8) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
