# 调研与筛选记录

[← 首页](../README.md) · [逐项来源](sources.md) · [数据快照](snapshot.json) · [扩充对比](expansion.md)

## 本次范围

核验于 **2026-09-27**。检查 **261 个候选仓库**，保留 **241 个独立仓库、242 个导航条目**。其中高 Star 选型 198 项、生态补充 26 项、历史维护 18 项。

多包仓库可能对应多个入口；系统 SDK 文档链接不计作库。导航同时涵盖第三方库、框架官方生态包和开发工具，官方包在条目中说明。

## 如何筛选

| 分区 | 收录条件 | 展示位置 |
|---|---|---|
| 高 Star | GitHub 至少 3,000 Star；优先考察 5,000 以上、用途明确的项目 | 各业务模块的高 Star 速查表 |
| 生态补充 | GitHub 至少 1,000 Star，并有下面列出的包平台使用量或其他框架官方集成证据 | 独立补充表，逐条链接依据 |
| 历史维护 | 已归档、弃用、停止积极维护，或旧项目迁移价值较高 | 各语言 legacy 页面 |

生态补充的量化门槛：pub.dev 至少 1,000 Likes 或近 30 天至少 100,000 次下载；非 pub.dev 项目需有其他框架官方文档确认的依赖或集成关系。满足门槛只是候选资格，仍需核对具体用途、维护状态及授权边界。完整证据见 [生态补充依据](supplements.md)。

筛选时阅读项目 README、官方文档与包页面，并核对归档标识、维护公告、默认分支提交。排除教程合集、纯演示、参考源码和授权不符合本清单定位的项目。Star、下载量、官方集成关系都不是质量保证；本次没有进行开发者问卷或逐库性能评测，不宣称所有开发者意见一致。

## 状态如何理解

| 标签 | 判定依据 | 阅读方式 |
|---|---|---|
| 近期有提交 | 默认分支在核验前 365 天内有提交 | 可能包含文档或自动化提交，不等同于已适配最新系统 |
| 更新较久 | 默认分支超过 365 天没有提交 | 成熟库也可能低频更新；接入前验证目标工具链 |
| 维护模式 | 上游明确减少或停止新增功能 | 以官方支持范围为准 |
| 停止积极维护 | README 明确给出该说明 | 在历史维护页查看后继方向 |
| 已弃用 / 部分已弃用 | 上游明确说明弃用或迁移 | 先阅读迁移文档 |
| 已归档 | GitHub 仓库归档标识 | 仅进入历史维护页 |

提交时间来自默认分支 Atom 订阅，采用 UTC；它不是发行版日期，也不同于包括其他分支推送的 `pushed_at`。有维护公告时优先按公告标注，不用近期提交掩盖弃用状态。

## 需要留意的结果

| 项目 | 核验结论 | 处理 |
|---|---|---|
| AFNetworking / YTKNetwork | 前者已弃用归档，后者 README 明确依赖前者 | [Objective-C 历史页](../objective-c/legacy.md) |
| 旧 ExoPlayer | 官方要求迁往 AndroidX Media3 | [Kotlin 历史页](../kotlin/legacy.md) |
| Material Components Views | 官方进入维护模式 | [Kotlin 历史页](../kotlin/legacy.md) |
| Gson | README 标注维护模式 | 保留并提示适用边界 |
| EasyExcel | 仓库已归档 | [Java 历史页](../java/legacy.md) |
| Wire / 原 GoMock | 归档或停止维护 | [Go 历史页](../go/legacy.md) |
| UniRx / FASTER | 前者归档推荐 R3；后者停止积极维护 | [C# 历史页](../csharp/legacy.md) |
| Isar / Hive 原仓库 | 分支、更新与兼容性需重点核对 | [Dart 历史页](../dart/legacy.md) |
| LiteDB | README 警告当前文件加密实现不安全，不要使用 | [存储页明确提示](../csharp/storage.md) |
| Flutter Form Builder | README 正在招募维护者 | 补充条目中提示检查维护响应 |

以上结论均可从 [逐项来源](sources.md) 的官方说明复核。

## 未收录示例

| 项目 | 原因 |
|---|---|
| [ET 当前版本](https://github.com/egametang/ET) | README 的 ET10 授权说明限制为学习使用，商业使用需购买授权；不作为可自由商用的开源库推荐。历史版本需单独核验许可证 |
| [AssetBundle Browser](https://github.com/Unity-Technologies/AssetBundles-Browser) | 官方说明不再支持，并指向 Addressables；本次不增加此旧工具入口 |
| [Tivi](https://github.com/chrisbanes/tivi) | 示例应用且已归档，不是可直接接入的通用库 |
| [UnityCsReference](https://github.com/Unity-Technologies/UnityCsReference) | 引擎参考源码，不是独立接入库 |
| 其他低于主清单门槛的候选 | 未完成足够的补充证据核验时暂不列入；不代表库不好 |

## 数据口径

- Star 来自 GitHub 公共 API 或仓库 HTML 的完整计数；每项保留实际来源和核验时间。
- 仓库转移后使用已确认的新地址；包名和安装坐标以官方安装文档为准。
- monorepo 的 Star 属于整个仓库。Dagger/Hilt、Flutter packages、FlutterFire、Bloc 等不能拆算成单包热度。
- pub.dev 的 Likes、下载量与 Flutter Favorite 标签来自官方 metrics API。下载包含开发、CI 和传递依赖，不等于用户人数；同仓库只核验代表包时会注明包名。
- 仅发布事实字段、来源链接与原创中文摘要，不再分发上游完整 README 或项目代码。
- 这是静态 Markdown 导航，没有自动更新任务。更新时同步模块页、索引、来源与快照。

[查看本版检查记录](verification.md)
