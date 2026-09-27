# Kotlin · 开源库导航

[← 返回首页](../README.md) · [全部库索引](../INDEX.md) · [筛选与核验](../research/README.md)

以 Android 为主，兼顾 Kotlin Multiplatform。按“使用者的语言”归类，因此可从 Kotlin 调用的 Java 库也会出现在这里。

> Android / Kotlin Multiplatform · 18 个选型入口 · 3 个历史条目 · 核验于 2026-09-27

## 按业务模块查找

| 模块 | 我要解决什么问题 | 条目数 |
|---|---|---:|
| [网络与通信](networking.md) | 调用 API、上传下载、长连接和协议通信 | 3 |
| [图片加载与缓存](images.md) | 头像、商品图、信息流和图片处理 | 1 |
| [状态管理与依赖注入](architecture.md) | 组织业务状态、事件流和模块依赖 | 3 |
| [数据库与本地存储](storage.md) | 离线数据、SQL、事务和结构迁移 | 1 |
| [数据模型与序列化](serialization.md) | JSON、二进制数据和类型化模型 | 1 |
| [音视频与动画播放](media.md) | 播放器、媒体会话和矢量动画 | 2 |
| [日志、调试与工程质量](tooling.md) | 定位问题、分析性能和统一代码规范 | 4 |
| [自动化测试](testing.md) | 测试组织、断言、Mock 和集成验证 | 2 |
| [平台能力与权限](platform.md) | 系统权限、相机、WebView 等能力 | 1 |
| [旧项目维护与迁移](legacy.md) | 已归档、已弃用或需重点评估的历史方案 | 3 |

## 常用路线

- **搭建 Android 数据层**：[网络](networking.md) → [序列化](serialization.md) → [存储](storage.md)。
- **完善应用体验**：[图片](images.md) → [媒体](media.md) → [权限](platform.md)。
- **Java 与 Kotlin 混编**：[Java 客户端库](../java/android.md) → [依赖注入](architecture.md)。

## 官方基础能力

这些是系统或框架入口，单独列出，不计入第三方库数量。

- [Android Jetpack](https://developer.android.com/jetpack)：Compose、Room、Navigation、WorkManager 等官方能力。
- [Compose Material 3](https://developer.android.com/develop/ui/compose/designsystems/material3)：现代 Android UI 的官方组件入口。

## 阅读说明

Star 是核验时的仓库快照。`近期有提交` 只表示默认分支一年内有提交；`更新较久` 不等于已弃用。具体状态与选型提醒见模块页。
