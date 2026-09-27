# Java · 数据模型与序列化

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

JSON、二进制数据和类型化模型。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Jackson Databind](#jackson-databind) | JSON 与 Java 对象绑定 | 3,751 | 近期有提交 |
| [Gson](#gson) | Java 对象与 JSON 转换 | 24,234 | 维护模式 |
| [Moshi](#moshi) | Java/Kotlin JSON 编解码 | 10,164 | 近期有提交 |
| [Fastjson2](#fastjson2) | JSON 与 JSONB 编解码 | 4,415 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Jackson Databind

**适合**：Java API 服务中的 JSON 处理。

**选型提醒**：注意主版本兼容和多态反序列化配置。

[源码](https://github.com/FasterXML/jackson-databind) · [官方文档](https://github.com/FasterXML/jackson-databind#readme) · [安装入口](https://github.com/FasterXML/jackson-databind#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/FasterXML/jackson-databind/commit/ae8bf3fc5170a84089c404e0feed0398c9672bec) · 版本与许可证见上游仓库。</sub>

## Gson

**适合**：已有 Gson 模型或简单 Java 数据转换。

**选型提醒**：官方处于维护模式，主要修复问题；新 Android/Kotlin 项目优先评估更适合该生态的序列化方案。

[源码](https://github.com/google/gson) · [官方文档](https://github.com/google/gson/blob/main/UserGuide.md) · [安装入口](https://github.com/google/gson#readme)

<sub>默认分支最近提交：2026-09-16 · [维护模式](https://github.com/google/gson/commit/854c8255b625cf1e13c701a83ea9ccb4caaa576a) · 版本与许可证见上游仓库。</sub>

## Moshi

**适合**：Android 接口模型与 JSON 转换。

**选型提醒**：Kotlin 项目按文档配置代码生成或反射适配。

[源码](https://github.com/square/moshi) · [官方文档](https://github.com/square/moshi#readme) · [安装入口](https://github.com/square/moshi#readme)

<sub>默认分支最近提交：2026-06-18 · [近期有提交](https://github.com/square/moshi/commit/889013ec2edb8d8034902662a1dc8c4f3b3f8111) · 版本与许可证见上游仓库。</sub>

## Fastjson2

**适合**：需要评估 JSON 处理方案的 Java 服务。

**选型提醒**：与旧 Fastjson 分开管理，不直接套用旧版本配置。

[源码](https://github.com/alibaba/fastjson2) · [官方文档](https://github.com/alibaba/fastjson2#readme) · [安装入口](https://github.com/alibaba/fastjson2#quick-start)

<sub>默认分支最近提交：2026-09-09 · [近期有提交](https://github.com/alibaba/fastjson2/commit/017e08880203c32228e0e7186f924bb5dd89f21d) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
