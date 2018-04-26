---
title: Android 平台功能
description: 向 Xamarin.Forms 应用添加 Android 特有的功能
ms.prod: xamarin
ms.assetid: E24168F3-0138-4814-86EA-B467F6B8A545
ms.technology: xamarin-forms
author: davidbritch
ms.author: dabritch
ms.date: 01/13/2016
ms.openlocfilehash: 3648f6f5f576a77bf7887668352c4f3d11f3906d
ms.sourcegitcommit: 945df041e2180cb20af08b83cc703ecd1aedc6b0
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/04/2018
---
# <a name="android-platform-features"></a>Android 平台功能

## <a name="platform-support"></a>平台支持

默认的 Xamarin.Forms Android 项目通常情况使用 Android 5.0 之前的控件旧样式进行渲染
。 使用模板生成的应用程序具有`FormsApplicationActivity`作为其主要活动的基类。

## <a name="material-design-via-appcompat"></a>通过 AppCompat 材料设计

Xamarin.Forms 还具有可选`FormsAppCompatActivity`使用**AppCompat**由 Android 提供实现材料设计主题的功能。

若要向 Xamarin.Forms Android 项目中添加材料设计主题，请按照[AppCompat 的安装说明支持](appcompat.md)

下面是**Todo**示例使用默认`FormsApplicationActivity`:

[![](images/before-appcompat-sml.png "Todo 示例应用程序而无需 AppCompat")](images/before-appcompat.png#lightbox "没有 AppCompat Todo 示例应用程序")

这在升级项目以使用后是相同的代码和`FormsAppCompatActivity`（和添加其他主题的信息）：

[![](images/post-appcompat-sml.png "Todo 示例应用程序使用 AppCompat 和主题")](images/post-appcompat.png#lightbox "Todo 示例应用程序使用 AppCompat 和主题")

> [!NOTE]
> 使用时`FormsAppCompatActivity`、[某些 Android 自定义呈现器的基本类](~/xamarin-forms/app-fundamentals/custom-renderer/renderers.md)都有所不同。


## <a name="related-links"></a>相关链接

- [添加材料设计支持](appcompat.md)
