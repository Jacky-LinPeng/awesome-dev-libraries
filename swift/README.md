# Swift · 开源库导航

[← 返回首页](../README.md) · [全部库索引](../INDEX.md) · [筛选与核验](../research/README.md)

面向 iOS 与 Apple 平台。UIKit、SwiftUI 和基础数据层分别按场景选库，不要求整套安装。

> iOS / Apple 平台 · 18 个选型入口 · 核验于 2026-09-27

## 按业务模块查找

| 模块 | 我要解决什么问题 | 条目数 |
|---|---|---:|
| [网络与通信](networking.md) | 调用 API、上传下载、长连接和协议通信 | 2 |
| [图片加载与缓存](images.md) | 头像、商品图、信息流和图片处理 | 2 |
| [UI、布局与动效](ui.md) | 页面布局、图表和界面视觉效果 | 3 |
| [数据库与本地存储](storage.md) | 离线数据、SQL、事务和结构迁移 | 2 |
| [状态管理与依赖注入](architecture.md) | 组织业务状态、事件流和模块依赖 | 3 |
| [认证、权限与凭据](authentication.md) | 登录凭据、Token 和服务访问控制 | 1 |
| [内购与订阅](commerce.md) | 订阅购买、权益与收据管理 | 1 |
| [日志、调试与工程质量](tooling.md) | 定位问题、分析性能和统一代码规范 | 2 |
| [自动化测试](testing.md) | 测试组织、断言、Mock 和集成验证 | 2 |

## 常用路线

- **接入 API 与图片**：[网络](networking.md) → [图片](images.md)。
- **构建业务界面**：[UI](ui.md) → [状态管理](architecture.md)。
- **完善工程质量**：[测试](testing.md) → [格式与静态检查](tooling.md)。

## 官方基础能力

这些是系统或框架入口，单独列出，不计入第三方库数量。

- [Apple 开发文档](https://developer.apple.com/documentation/)：URLSession、SwiftUI、AVFoundation、MapKit、StoreKit 等系统能力。

## 阅读说明

Star 是核验时的仓库快照。`近期有提交` 只表示默认分支一年内有提交；`更新较久` 不等于已弃用。具体状态与选型提醒见模块页。
