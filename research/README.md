# 调研与筛选记录

[← 首页](../README.md) · [逐项来源](sources.md) · [数值快照](snapshot.json) · [首版检查记录](verification.md)

## 本次范围

- 核验日期：**2026-09-27**。
- 检查 **158 个候选仓库**，覆盖 7 种语言的日常开发生态。
- 最终保留 **130 个不同仓库、131 个导航条目**，其中 118 个选型入口、13 个历史条目。
- 多包仓库可能对应多个入口；官方 SDK 文档链接不计作第三方库。

## 如何筛选

1. **可核验的热度**：本版最低 3,000 GitHub Star，优先比较 5,000 以上的候选。数值来自 GitHub API 或仓库页面的完整 Star 计数。
2. **明确的业务用途**：能解决网络、存储、UI、测试、资源等具体需求；排除教程合集、纯示例项目和源码镜像导航。
3. **可信的项目来源**：核对维护者仓库、官方 README、文档或正式包页面，跟随已确认的仓库迁移。
4. **查看维护信号**：检查归档标识、README 中的弃用/维护公告及默认分支最近提交，分别记录，避免仅凭 Star 判断。
5. **给出适用边界**：写清同类替代、互补关系、平台差异和接入成本，不使用脱离场景的性能排名。

Star 是第一道筛选条件。官方文档、长期生态使用和明确功能定位用于进一步取舍；本次没有做用户调查或为所有库运行基准测试，因此不把精选结果表述为所有开发者的一致评价。

## 状态如何理解

| 标签 | 判定依据 | 阅读方式 |
|---|---|---|
| 近期有提交 | 默认分支在核验前 365 天内有提交 | 可能含文档或自动化提交，不等同于已适配全部新系统 |
| 更新较久 | 默认分支超过 365 天没有提交 | 不自动判为废弃；成熟稳定库也可能低频更新 |
| 维护模式 | 上游明确公告减少或停止新增功能 | 根据上游支持范围决定是否继续使用 |
| 已弃用 / 部分已弃用 | 上游明确说明弃用或迁移 | 优先阅读后继方案与迁移文档 |
| 已归档 | GitHub 仓库归档标识 | 只收录在历史维护页 |

默认分支提交时间与 GitHub 的 `pushed_at` 不同；后者还可能反映其他分支或标签推送。页面展示采用前者。

## 值得留意的结论

| 项目 | 核验结果 | 导航处理 |
|---|---|---|
| AFNetworking | 官方弃用且仓库归档 | [Objective-C 迁移页](../objective-c/legacy.md) |
| 旧 ExoPlayer | 官方要求迁往 AndroidX Media3 | [Kotlin 迁移页](../kotlin/legacy.md) |
| Material Components Views | 官方进入维护模式，新的 UI 方向转向 Compose | [Kotlin 迁移页](../kotlin/legacy.md) |
| Gson | 官方 README 标注维护模式 | 保留并在 [序列化页](../java/serialization.md) 提醒 |
| EasyExcel | 仓库已归档 | [Java 迁移页](../java/legacy.md) |
| 原 GoMock | 官方已停止维护并指向后继分支 | [Go 迁移页](../go/legacy.md) |
| UniRx | 官方归档并推荐 R3 | [C# 迁移页](../csharp/legacy.md) |
| Isar / Hive 原仓库 | 需关注分支、维护与兼容性；Isar README 明示 v4 非生产版本 | [Dart 维护页](../dart/legacy.md) |

上述结论的原始依据集中在 [逐项来源](sources.md) 的「官方说明」和仓库链接。

## 本版未收录的代表候选

未达到本版 Star 门槛不代表库不好。Flutter 与 Unity 的部分常用组件在包平台或 Asset Store 更活跃，但这里保持统一的 GitHub Star 口径。

| 项目 | 核验 Star | 原因 |
|---|---:|---|
| [Baseflow/flutter_cached_network_image](https://github.com/Baseflow/flutter_cached_network_image) | 2,591 | 低于本版 3,000 Star 门槛。 |
| [rrousselGit/freezed](https://github.com/rrousselGit/freezed) | 2,194 | 低于本版 3,000 Star 门槛。 |
| [fluttercommunity/plus_plugins](https://github.com/fluttercommunity/plus_plugins) | 1,875 | 低于本版 3,000 Star 门槛。 |
| [Demigiant/dotween](https://github.com/Demigiant/dotween) | 2,691 | 低于本版 3,000 Star 门槛。 |
| [FirstGearGames/FishNet](https://github.com/FirstGearGames/FishNet) | 2,056 | 低于本版 3,000 Star 门槛。 |
| [fairygui/FairyGUI-unity](https://github.com/fairygui/FairyGUI-unity) | 2,971 | 低于本版 3,000 Star 门槛。 |
| [leancodepl/patrol](https://github.com/leancodepl/patrol) | 1,435 | 低于本版 3,000 Star 门槛。 |
| [chrisbanes/tivi](https://github.com/chrisbanes/tivi) | 6,719 | 示例应用，且已归档，不是可直接接入的通用库。 |
| [Unity-Technologies/UnityCsReference](https://github.com/Unity-Technologies/UnityCsReference) | 13,006 | Unity 参考源码，不是独立接入的第三方库。 |
| [flutter/website](https://github.com/flutter/website) | 3,120 | Flutter 文档网站源码，不是应用依赖库。 |

## 数据口径与后续更新

- 仓库转移后使用新地址；安装坐标不会因仓库名称变化而自动变化，应始终以官方安装文档为准。
- monorepo 的 Star 属于整个仓库。Dagger/Hilt、Flutter 官方 packages、FlutterFire、Bloc 等均按仓库总数理解。
- 先通过公共 GitHub API 获取可用元数据；未登录额度用尽后，改为读取公开仓库页面。提交日期通过公开 Atom 订阅核验。
- 仅保留事实字段、来源 URL 与原创中文说明，不再分发上游完整 README 或项目代码。
- 本仓库是静态 Markdown 导航，没有配置自动更新任务。更新时同时修改模块页、索引、来源表与快照。
