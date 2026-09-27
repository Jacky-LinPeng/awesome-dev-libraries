# Go · 日志、调试与工程质量

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

定位问题、分析性能和统一代码规范。

## 快速选择

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [zap](#zap) | 结构化日志 | 24,660 | 近期有提交 |
| [zerolog](#zerolog) | 链式结构化 JSON 日志 | 12,507 | 近期有提交 |
| [Prometheus Go client](#prometheus-go-client) | 暴露应用指标 | 6,035 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## zap

**适合**：需要结构化字段与较低日志开销的服务。

**选型提醒**：新项目也可评估标准库 log/slog；避免混用多套日志入口。

[源码](https://github.com/uber-go/zap) · [官方文档](https://pkg.go.dev/go.uber.org/zap) · [安装入口](https://github.com/uber-go/zap#installation)

<sub>默认分支最近提交：2026-09-16 · [近期有提交](https://github.com/uber-go/zap/commit/4892335e05f14bce8a98a69a577fcf3844a42623) · 版本与许可证见上游仓库。</sub>

## zerolog

**适合**：偏好简洁链式 API 的服务日志。

**选型提醒**：与 zap 按团队习惯择一，统一字段和采集方式。

[源码](https://github.com/rs/zerolog) · [官方文档](https://github.com/rs/zerolog#readme) · [安装入口](https://github.com/rs/zerolog#installation)

<sub>默认分支最近提交：2026-09-08 · [近期有提交](https://github.com/rs/zerolog/commit/5eb5f3a76c09eeadc1f2464baf4a4e3f1037c830) · 版本与许可证见上游仓库。</sub>

## Prometheus Go client

**适合**：接入 Prometheus 指标监控。

**选型提醒**：限制标签基数，避免把用户 ID 等放进指标标签。

[源码](https://github.com/prometheus/client_golang) · [官方文档](https://github.com/prometheus/client_golang#readme) · [安装入口](https://github.com/prometheus/client_golang#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/prometheus/client_golang/commit/ae383cad8807236fc4ab113c9d98fe343daa039e) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
