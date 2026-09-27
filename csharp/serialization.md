# C# · 数据模型与序列化

[← C# 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

JSON、二进制数据和类型化模型。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [MessagePack for C#](#messagepack-for-c) | 二进制序列化 | 6,789 | 近期有提交 |
| [Json.NET](#jsonnet) | JSON 序列化、解析与对象转换 | 11,316 | 近期有提交 |
| [MemoryPack](#memorypack) | .NET 二进制序列化与生成代码 | 4,739 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## MessagePack for C#

**适合**：游戏消息、存档和跨服务数据交换。

**选型提醒**：Unity/IL2CPP 下按文档配置生成代码与类型注册。

[源码](https://github.com/MessagePack-CSharp/MessagePack-CSharp) · [官方文档](https://github.com/MessagePack-CSharp/MessagePack-CSharp#readme) · [安装入口](https://github.com/MessagePack-CSharp/MessagePack-CSharp#installation)

<sub>默认分支最近提交：2026-09-23 · [近期有提交](https://github.com/MessagePack-CSharp/MessagePack-CSharp/commit/f2bfa97ef56c3e0eda92d7df34856467afcda865) · 版本与许可证见上游仓库。</sub>

## Json.NET

**适合**：JSON 配置、存档和接口数据。

**选型提醒**：Unity 中优先核对已安装的对应包，避免重复 DLL 与版本冲突。

[源码](https://github.com/JamesNK/Newtonsoft.Json) · [官方文档](https://www.newtonsoft.com/json/help) · [安装入口](https://github.com/JamesNK/Newtonsoft.Json#readme)

<sub>默认分支最近提交：2026-09-21 · [近期有提交](https://github.com/JamesNK/Newtonsoft.Json/commit/52fa3aef1f2cadcd3a3f874251eddc98d3efbbaa) · 版本与许可证见上游仓库。</sub>

## MemoryPack

**适合**：需要评估二进制数据格式的 C# 工程。

**选型提醒**：Unity 有独立兼容条件；格式演进和跨语言需求应先确认。

[源码](https://github.com/Cysharp/MemoryPack) · [官方文档](https://github.com/Cysharp/MemoryPack#readme) · [安装入口](https://github.com/Cysharp/MemoryPack#installation)

<sub>默认分支最近提交：2026-07-08 · [近期有提交](https://github.com/Cysharp/MemoryPack/commit/85ab9ad76c380aca48c09ff3a0ad955ee5a2902b) · 版本与许可证见上游仓库。</sub>

---

[← 返回 C#](README.md) · [查看调研记录](../research/README.md)
