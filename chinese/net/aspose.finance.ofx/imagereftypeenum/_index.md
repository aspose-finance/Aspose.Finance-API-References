---
title: ImageRefTypeEnum
second_title: Aspose.Finance for .NET API 参考
description: 图像引用类型枚举
type: docs
weight: 2310
url: /zh/net/aspose.finance.ofx/imagereftypeenum/
---
## ImageRefTypeEnum enumeration

图像引用类型枚举。

```csharp
public enum ImageRefTypeEnum
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| OPAQUE | `0` | 图像通过显式 OFX[`ImageRequest`](../../aspose.finance.ofx.image/imagerequest)请求访问，随后是图像数据。 |
| URL | `1` | 图片可通过提供的 URL 直接访问。无法通过 OFX 图像请求检索图像。 期望客户端不会提供身份验证，而只会遵循提供的 URL。 |
| FORMURL | `2` | 图像通过编码 URL 直接访问。无法通过 OFX 图像请求检索图像。期望是 客户端将向服务器发送身份验证。 |

### 也可以看看

* 命名空间 [Aspose.Finance.Ofx](../../aspose.finance.ofx)
* 部件 [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->