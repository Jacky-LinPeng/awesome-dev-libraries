<div align="center">

# 开发常用开源库导航

**先选语言，再找业务模块，最后选择合适的库。**

Swift · Objective-C · Kotlin · Java · Go · Dart · C#

**7 种语言**　/　**118 个选型入口**　/　**13 个历史条目**

</div>

---

面向 iOS、Android、Flutter、Unity 与服务端开发的中文导航。每个条目提供用途、适用场景、选型提醒，以及源码、官方文档和安装入口。

> **首版核验：2026-09-27** · 收录条目的仓库均达到 **3,000 Star**，优先考虑 5,000 以上项目。Star 与维护状态均有来源可查。[查看筛选标准](research/README.md)

## 选择语言

| 语言 | 主要平台 | 去哪里找 | 选型 / 历史 |
|---|---|---|---:|
| **[Swift](swift/README.md)** | iOS / Apple 平台 | 网络、图片、UI、数据库与工程质量 | 18 / 0 |
| **[Objective-C](objective-c/README.md)** | iOS / 混编与旧项目 | 图片、数据库、日志、调试与迁移 | 5 / 5 |
| **[Kotlin](kotlin/README.md)** | Android / Kotlin Multiplatform | 网络、协程、依赖注入、媒体与测试 | 18 / 3 |
| **[Java](java/README.md)** | Android / JVM 服务端 | Android 图片、Web、数据库、缓存与测试 | 20 / 1 |
| **[Go](go/README.md)** | 服务端 / CLI | Web、微服务、数据库、任务与可观测性 | 27 / 1 |
| **[Dart](dart/README.md)** | Flutter | 网络、状态管理、路由、存储与平台能力 | 12 / 2 |
| **[C#](csharp/README.md)** | Unity / .NET | 异步、资源、热更新、联网与编辑器工具 | 18 / 1 |

## 按当前任务直达

| 我要做什么 | 入口 |
|---|---|
| iOS 接口请求、图片与本地数据 | [Swift 网络](swift/networking.md) · [图片](swift/images.md) · [数据库](swift/storage.md) |
| Android 网络、状态与调试 | [Kotlin 网络](kotlin/networking.md) · [协程与依赖](kotlin/architecture.md) · [调试](kotlin/tooling.md) |
| Flutter 状态管理、路由与插件 | [状态管理](dart/architecture.md) · [路由](dart/routing.md) · [平台插件](dart/platform.md) |
| Unity 异步、资源与热更新 | [异步](csharp/async.md) · [资源](csharp/assets.md) · [热更新](csharp/hot-update.md) |
| Unity 联网、配置与 UI | [联网](csharp/networking.md) · [策划表](csharp/configuration.md) · [UI](csharp/ui.md) |
| Java 后台接口、数据库与缓存 | [Web](java/web.md) · [数据库](java/storage.md) · [缓存](java/cache.md) |
| Go API、go-zero 与后台任务 | [Web](go/web.md) · [微服务](go/microservices.md) · [任务](go/jobs.md) |
| 接手 Objective-C 旧工程 | [常用组件](objective-c/README.md) · [历史依赖与迁移](objective-c/legacy.md) |

## 怎么用

1. 打开语言页，按业务模块进入。
2. 先看快速对比表，再看候选库的「适合」与「选型提醒」。
3. 点击官方安装入口，按目标 SDK、引擎或运行时选择发行版。

知道库名时，打开 **[全部库索引](INDEX.md)**，用浏览器查找即可。

## 阅读约定

- **按使用语言归类**：从 Kotlin 可用的 Java 库、服务于 Unity C# 的运行时工具，也会在对应语言下出现。
- **按场景推荐**：同类库通常择一；上下层组件会说明配合关系。
- **官方组件有标注**：Kotlin 扩展库、Media3、Flutter 官方包等与第三方项目区分说明。
- **历史库单列**：AFNetworking、旧 ExoPlayer、UniRx 等保留迁移入口，不作为新项目默认选型。
- **Star 按仓库统计**：多包仓库中的单个包没有独立仓库 Star，不能把总数当成单包热度。

## 数据与维护

本导航是精选清单，不承诺覆盖所有业务场景。基础能力也可直接使用系统 SDK；各语言页提供官方入口。

所有数值为核验日期的快照，后续更新需要重新核验。Star 反映关注度，不能单独证明质量或行业共识；状态标签不代表维护者的支持承诺。

**[调研与筛选记录](research/README.md)** · **[逐项来源](research/sources.md)** · **[贡献指南](CONTRIBUTING.md)**
