# Objective-C · 开源库导航

[← 返回首页](../README.md) · [全部库索引](../INDEX.md) · [筛选与核验](../research/README.md)

面向 Objective-C 与 Swift 混编工程。网络、相机、定位等基础能力也可直接使用 Apple SDK；历史热门库集中放在维护页。

> iOS / 混编与旧项目 · 14 个选型入口 · 8 个历史条目 · 高 Star 14 / 生态补充 0 · 核验于 2026-09-27

## 按业务模块查找

| 模块 | 我要解决什么问题 | 条目数 |
|---|---|---:|
| [图片加载与缓存](images.md) | 头像、商品图、信息流和图片处理 | 3 |
| [数据库与本地存储](storage.md) | 离线数据、SQL、事务和结构迁移 | 1 |
| [日志、调试与工程质量](tooling.md) | 定位问题、分析性能和统一代码规范 | 3 |
| [网络与通信](networking.md) | 调用 API、上传下载、长连接和协议通信 | 1 |
| [UI、布局与动效](ui.md) | 页面布局、图表和界面视觉效果 | 4 |
| [数据模型与序列化](serialization.md) | JSON、二进制数据和类型化模型 | 1 |
| [日历与日期界面](calendar.md) | 签到、日程与日期选择 | 1 |
| [旧项目维护与迁移](legacy.md) | 已归档、已弃用或需重点评估的历史方案 | 8 |

## 常用路线

- **维护常规业务**：[图片](images.md) → [存储](storage.md) → [日志与调试](tooling.md)。
- **接手旧工程**：[历史库与迁移](legacy.md) → [Swift 导航](../swift/README.md)。

## 官方基础能力

这些是系统或框架入口，单独列出，不计入第三方库数量。

- [Apple Foundation](https://developer.apple.com/documentation/foundation)：网络与基础数据类型，按文档选择 Objective-C 接口。

## 阅读说明

Star 是核验时的仓库快照。`近期有提交` 只表示默认分支一年内有提交；`更新较久` 不等于已弃用。具体状态与选型提醒见模块页。
