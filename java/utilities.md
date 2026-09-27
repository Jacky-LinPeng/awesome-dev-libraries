# Java · 通用工具与对象映射

[← Java 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

集合工具、数据转换和重复代码消除。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [Guava](#guava) | 集合、缓存及基础工具 | 51,911 | 近期有提交 |
| [MapStruct](#mapstruct) | 编译期生成 Java Bean 映射代码 | 7,694 | 近期有提交 |
| [Hutool](#hutool) | Java 常用功能工具集 | 30,271 | 近期有提交 |
| [Apache Commons Lang](#apache-commons-lang) | 字符串、对象与基础类型工具 | 3,008 | 近期有提交 |
| [AndroidUtilCode](#androidutilcode) | Android 常用工具 API 集合 | 33,617 | 更新较久 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## Guava

**适合**：需要成熟通用工具的 Java/JVM 工程。

**选型提醒**：Android 与 JRE 发行变体不同，按运行环境选择。

[源码](https://github.com/google/guava) · [官方文档](https://github.com/google/guava#readme) · [安装入口](https://github.com/google/guava#readme)

<sub>默认分支最近提交：2026-09-26 · [近期有提交](https://github.com/google/guava/commit/a279b884fe9890a3869142919352156f2a67a705) · 版本与许可证见上游仓库。</sub>

## MapStruct

**适合**：DTO、数据库实体与接口模型转换。

**选型提醒**：需配置注解处理器；复杂转换规则仍要明确编写。

[源码](https://github.com/mapstruct/mapstruct) · [官方文档](https://mapstruct.org/documentation/reference-guide/) · [安装入口](https://github.com/mapstruct/mapstruct#readme)

<sub>默认分支最近提交：2026-07-25 · [近期有提交](https://github.com/mapstruct/mapstruct/commit/211b2be6205a720f30aad77e5b94cd1fac441443) · 版本与许可证见上游仓库。</sub>

## Hutool

**适合**：减少日期、字符串、文件等重复工具代码。

**选型提醒**：按需选择模块，避免无差别引入全量依赖。

[源码](https://github.com/chinabugotech/hutool) · [官方文档](https://github.com/chinabugotech/hutool#readme) · [安装入口](https://github.com/chinabugotech/hutool#安装)

<sub>默认分支最近提交：2026-07-09 · [近期有提交](https://github.com/chinabugotech/hutool/commit/8870454b2a0c29cc6ffd31dcf5667c8ceb2fc442) · 版本与许可证见上游仓库。</sub>

## Apache Commons Lang

**适合**：JDK 基础工具的补充。

**选型提醒**：先确认目标 JDK 是否已有对应能力。

[源码](https://github.com/apache/commons-lang) · [官方文档](https://github.com/apache/commons-lang#readme) · [安装入口](https://github.com/apache/commons-lang#readme)

<sub>默认分支最近提交：2026-09-25 · [近期有提交](https://github.com/apache/commons-lang/commit/29624cdb50ecd794207d561345b2fc9ca3a9d326) · 版本与许可证见上游仓库。</sub>

## AndroidUtilCode

**适合**：补齐设备、文件、屏幕等常见工具能力。

**选型提醒**：属于 Android 工具集，不能直接当作普通 JVM 工具库使用。

[源码](https://github.com/Blankj/AndroidUtilCode) · [官方文档](https://github.com/Blankj/AndroidUtilCode#readme) · [安装入口](https://github.com/Blankj/AndroidUtilCode#readme)

<sub>默认分支最近提交：2024-05-11 · [更新较久](https://github.com/Blankj/AndroidUtilCode/commit/7b4caf9e5440046b3fefb63b6b6e2ead7ebaf809) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Java](README.md) · [查看调研记录](../research/README.md)
