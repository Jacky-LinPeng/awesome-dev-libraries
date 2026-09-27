# Objective-C · 图片加载与缓存

[← Objective-C 导航](README.md) · [首页](../README.md) · [全部库索引](../INDEX.md)

头像、商品图、信息流和图片处理。


## 高 Star · 速查

| 库 | 主要用途 | Star¹ | 状态² |
|---|---|---:|---|
| [SDWebImage](#sdwebimage) | 异步图片加载、缓存与图片格式扩展 | 25,629 | 近期有提交 |
| [TZImagePickerController](#tzimagepickercontroller) | 相册图片与视频选择 | 8,140 | 近期有提交 |
| [TOCropViewController](#tocropviewcontroller) | 图片裁剪交互 | 4,947 | 近期有提交 |

¹ 仓库 Star，核验日期 **2026-09-27**；多包仓库共享总数。² 状态定义见 [核验说明](../research/README.md#状态如何理解)。

## SDWebImage

**适合**：Objective-C 或混编 iOS 应用的图片展示。

**选型提醒**：特殊格式按需添加插件，避免引入用不到的解码器。

[源码](https://github.com/SDWebImage/SDWebImage) · [官方文档](https://sdwebimage.github.io/) · [安装入口](https://github.com/SDWebImage/SDWebImage#getting-started)

<sub>默认分支最近提交：2026-04-15 · [近期有提交](https://github.com/SDWebImage/SDWebImage/commit/c3ad5e1a9bf55c9b76d4c362430b5fcded96c502) · 版本与许可证见上游仓库。</sub>

## TZImagePickerController

**适合**：需要自定义相册选择体验的 iOS 工程。

**选型提醒**：先比较系统照片选择器；留意相册权限与大图内存。

[源码](https://github.com/banchichen/TZImagePickerController) · [官方文档](https://github.com/banchichen/TZImagePickerController#readme) · [安装入口](https://github.com/banchichen/TZImagePickerController#一-installation-安装)

<sub>默认分支最近提交：2026-08-15 · [近期有提交](https://github.com/banchichen/TZImagePickerController/commit/11776eb2a589019c3e01aafba693bb03b1f37fa5) · 版本与许可证见上游仓库。</sub>

## TOCropViewController

**适合**：头像编辑和用户上传图片预处理。

**选型提醒**：裁剪结果与原图方向、尺寸和编码格式需要一起处理。

[源码](https://github.com/TimOliver/TOCropViewController) · [官方文档](https://github.com/TimOliver/TOCropViewController#readme) · [安装入口](https://github.com/TimOliver/TOCropViewController#installation)

<sub>默认分支最近提交：2026-07-28 · [近期有提交](https://github.com/TimOliver/TOCropViewController/commit/9782ecf30b5d16dfc95c89c939180adf457a2e82) · 版本与许可证见上游仓库。</sub>

---

[← 返回 Objective-C](README.md) · [查看调研记录](../research/README.md)
