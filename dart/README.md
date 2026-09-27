# Dart · 开源库导航

[← 返回首页](../README.md) · [全部库索引](../INDEX.md) · [筛选与核验](../research/README.md)

以 Flutter 应用开发为主。官方 packages 仓库提供多个独立包，每个入口会注明 Star 口径；平台能力请按实际包安装。

> Flutter · 36 个选型入口 · 2 个历史条目 · 高 Star 16 / 生态补充 20 · 核验于 2026-09-27

## 按业务模块查找

| 模块 | 我要解决什么问题 | 条目数 |
|---|---|---:|
| [网络与通信](networking.md) | 调用 API、上传下载、长连接和协议通信 | 2 |
| [状态管理与依赖注入](architecture.md) | 组织业务状态、事件流和模块依赖 | 5 |
| [路由与导航](routing.md) | 深链、页面跳转和 URL 同步 | 2 |
| [数据库与本地存储](storage.md) | 离线数据、SQL、事务和结构迁移 | 3 |
| [图片加载与缓存](images.md) | 头像、商品图、信息流和图片处理 | 1 |
| [UI、布局与动效](ui.md) | 页面布局、图表和界面视觉效果 | 5 |
| [平台能力与权限](platform.md) | 系统权限、相机、WebView 等能力 | 5 |
| [地图与位置展示](maps.md) | 地图图层、瓦片和交互展示 | 2 |
| [音视频与动画播放](media.md) | 播放器、媒体会话和矢量动画 | 1 |
| [数据模型与序列化](serialization.md) | JSON、二进制数据和类型化模型 | 1 |
| [后端服务接入](backend.md) | 登录、云数据、消息与分析 SDK | 1 |
| [自动化测试](testing.md) | 测试组织、断言、Mock 和集成验证 | 1 |
| [文本与 HTML](text.md) | 富文本、HTML 解析和页面内容展示 | 1 |
| [文件与文档](files.md) | 文件选择、Excel、PDF 与导入导出 | 2 |
| [日志、调试与工程质量](tooling.md) | 定位问题、分析性能和统一代码规范 | 2 |
| [游戏与交互引擎](games.md) | Flutter 2D 游戏与游戏化界面 | 1 |
| [后台任务与并发](jobs.md) | 队列、定时调度和并发控制 | 1 |
| [旧项目维护与迁移](legacy.md) | 已归档、已弃用或需重点评估的历史方案 | 2 |

## 常用路线

- **搭建业务应用**：[网络](networking.md) → [状态](architecture.md) → [路由](routing.md)。
- **离线与平台能力**：[数据库](storage.md) → [平台插件](platform.md)。
- **地图与云服务**：[地图](maps.md) → [Firebase](backend.md)。

## 官方基础能力

这些是系统或框架入口，单独列出，不计入第三方库数量。

- [Flutter 包与插件](https://docs.flutter.dev/packages-and-plugins/using-packages)：包选择与平台配置。
- [Flutter 测试](https://docs.flutter.dev/testing/overview)：单元、Widget 与集成测试。

## 阅读说明

Star 是核验时的仓库快照。`近期有提交` 只表示默认分支一年内有提交；`更新较久` 不等于已弃用。具体状态与选型提醒见模块页。
