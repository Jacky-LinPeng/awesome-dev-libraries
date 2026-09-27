# Go · 数据模型与序列化

[← Go 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

JSON、二进制数据和类型化模型。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [GJSON](#gjson) | 按路径读取 JSON 数据 | 15,557 | 近期有提交 |
| [Sonic](#sonic) | Go JSON 编解码 | 9,602 | 近期有提交 |
| [go-json](#go-json) | 兼容常见 encoding/json 用法的 JSON 库 | 3,711 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## GJSON

**适合**：只需提取部分字段的 JSON 处理。

**选型提醒**：路径表达式与错误处理需覆盖实际输入，避免忽略无效数据。

[源码](https://github.com/tidwall/gjson) · [官方文档](https://github.com/tidwall/gjson#readme) · [安装入口](https://github.com/tidwall/gjson#getting-started)

<sub>默认分支最近提交：2026-08-28 · [近期有提交](https://github.com/tidwall/gjson/commit/8d89927eff414537088a6092d53fecf6711c1e75) · 版本与许可证见上游仓库。</sub>

## Sonic

**适合**：对 JSON 吞吐有明确要求的服务。

**选型提醒**：先核对架构、Go 版本与功能兼容，再用自身数据基准测试。

[源码](https://github.com/bytedance/sonic) · [官方文档](https://github.com/bytedance/sonic#readme) · [安装入口](https://github.com/bytedance/sonic#readme)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/bytedance/sonic/commit/5ce94543c910f7d64aacbf46f5eefae81daee56a) · 版本与许可证见上游仓库。</sub>

## go-json

**适合**：评估序列化性能与兼容性的 Go 工程。

**选型提醒**：替换前验证边界行为，不直接套用上游性能结论。

[源码](https://github.com/goccy/go-json) · [官方文档](https://github.com/goccy/go-json#readme) · [安装入口](https://github.com/goccy/go-json#installation)

<sub>默认分支最近提交：2026-09-27 · [近期有提交](https://github.com/goccy/go-json/commit/c6e282dea81b2cb32e48bd3fc39463b0228a3e0e) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Go](README.md) · [查看调研记录](../research/README.md)
