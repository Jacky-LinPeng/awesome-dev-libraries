# Dart · 数据库与本地存储

[← Dart 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

偏好响应式数据层看 Drift；希望直接操作 SQLite 看 sqflite。两者都需要设计数据库迁移。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Drift](#drift) | 响应式关系型数据层与类型化 SQL | 3,280 | 近期有提交 |
| [sqflite](#sqflite) | Flutter SQLite 插件 | 3,020 | 近期有提交 |

## 生态补充 · 速查

GitHub Star 低于 3,000，但有包平台使用量或其他框架官方集成依据；具体来源见条目。

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [flutter_secure_storage](#flutter_secure_storage) | 基于系统能力保存敏感小数据 | 1,284 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Drift

**适合**：离线业务、复杂查询和数据库观察。

**选型提醒**：涉及代码生成与数据库迁移，需维护对应构建流程。

[源码](https://github.com/simolus3/drift) · [官方文档](https://github.com/simolus3/drift#readme) · [安装入口](https://pub.dev/packages/drift/install)

<sub>默认分支最近提交：2026-09-24 · [近期有提交](https://github.com/simolus3/drift/commit/1c0beee12a528a0d0cc66a2a08b6c62a674fdecc) · 版本与许可证见上游仓库。</sub>

## sqflite

**适合**：偏好直接写 SQL 的移动端本地数据库。

**选型提醒**：跨平台能力与具体实现包有关，按目标平台核对。

[源码](https://github.com/tekartik/sqflite) · [官方文档](https://github.com/tekartik/sqflite/blob/master/sqflite/README.md) · [安装入口](https://pub.dev/packages/sqflite/install)

<sub>默认分支最近提交：2026-09-20 · [近期有提交](https://github.com/tekartik/sqflite/commit/aaabf90828645125bf7f4bd8e9a6fe4e3935b076) · 版本与许可证见上游仓库。</sub>

## flutter_secure_storage

**适合**：Token 等小型凭据的本地保存。

**选型提醒**：平台配置、备份与密钥失效策略需要按官方文档处理。

[源码](https://github.com/juliansteenbakker/flutter_secure_storage) · [官方文档](https://pub.dev/packages/flutter_secure_storage) · [安装入口](https://pub.dev/packages/flutter_secure_storage/install)

**补充依据**：pub.dev 的 flutter_secure_storage 包有 4,490 Likes、近 30 天 4,568,354 次下载。 [核验来源](https://pub.dev/api/packages/flutter_secure_storage/metrics)

<sub>默认分支最近提交：2026-09-16 · [近期有提交](https://github.com/juliansteenbakker/flutter_secure_storage/commit/e8eeb449cd512b26153f0a3376dfe374dd39a999) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Dart](README.md) · [查看调研记录](../research/README.md)
