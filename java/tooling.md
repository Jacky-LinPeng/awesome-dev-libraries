# Java · 日志、调试与工程质量

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

定位问题、分析性能和统一代码规范。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Logback](#logback) | Java 日志实现 | 3,236 | 近期有提交 |
| [Lombok](#lombok) | 通过编译处理减少 Java 样板代码 | 13,480 | 近期有提交 |

## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [SLF4J](#slf4j) | Java 日志门面 | 2,526 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Logback

**适合**：JVM 应用的日志输出、轮转与过滤。

**选型提醒**：与日志门面及桥接包版本配套，防止重复日志实现。

[源码](https://github.com/qos-ch/logback) · [官方文档](https://github.com/qos-ch/logback#readme) · [安装入口](https://github.com/qos-ch/logback#readme)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/qos-ch/logback/commit/37d0152822caf81b9c6b1b82d4f764ef1b043cb8) · 版本与许可证见上游仓库。</sub>

## SLF4J

**适合**：统一不同库与业务代码的日志 API。

**选型提醒**：它不是完整日志后端，需要匹配的 provider。

[源码](https://github.com/qos-ch/slf4j) · [官方文档](https://github.com/qos-ch/slf4j#readme) · [安装入口](https://github.com/qos-ch/slf4j#readme)

**补充依据**：Logback 官方文档将 slf4j-api 列为 logback-classic 的依赖。 [核验来源](https://logback.qos.ch/manual/introduction.html)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/qos-ch/slf4j/commit/90658112710a99a6ff7dbb2db0c1d13f8fb456f8) · 版本与许可证见上游仓库。</sub>

## Lombok

**适合**：团队接受注解生成的模型和构造器代码。

**选型提醒**：需兼容 JDK、IDE 和构建工具；避免隐藏重要业务逻辑。

[源码](https://github.com/projectlombok/lombok) · [官方文档](https://github.com/projectlombok/lombok#readme) · [安装入口](https://github.com/projectlombok/lombok#readme)

<sub>默认分支最近提交：2026-09-08 · [近期有提交](https://github.com/projectlombok/lombok/commit/e50d44b071c955d85f7b94a7cf06142c7ff2622b) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
