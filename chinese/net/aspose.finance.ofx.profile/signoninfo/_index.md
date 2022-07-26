---
title: SignonInfo
second_title: Aspose.Finance for .NET API 参考
description: 登录信息类
type: docs
weight: 4770
url: /zh/net/aspose.finance.ofx.profile/signoninfo/
---
## SignonInfo class

登录信息类。

```csharp
public class SignonInfo
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SignonInfo](signoninfo)() | 初始化[`SignonInfo`](../signoninfo)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AccessTokenRequire](../../aspose.finance.ofx.profile/signoninfo/accesstokenrequire) { get; set; } | 获取或设置服务器是否对除配置文件之外的所有请求都要求 ACCESSTOKEN。 |
| [AuthTokenFirst](../../aspose.finance.ofx.profile/signoninfo/authtokenfirst) { get; set; } | 获取或设置服务器是否要求客户端在首次登录时发送 AUTHTOKEN。 |
| [AuthTokenInfoUrl](../../aspose.finance.ofx.profile/signoninfo/authtokeninfourl) { get; set; } | 获取或设置运行 OFX 服务器的机构提供 AUTHTOKEN 信息的 URL。 |
| [AuthTokenLabel](../../aspose.finance.ofx.profile/signoninfo/authtokenlabel) { get; set; } | 获取或设置 AUTHTOKEN 的文本标签。 |
| [CaseSensitive](../../aspose.finance.ofx.profile/signoninfo/casesensitive) { get; set; } | 获取或设置密码是否区分大小写。 |
| [ChangePinFirst](../../aspose.finance.ofx.profile/signoninfo/changepinfirst) { get; set; } | 获取或设置服务器是否要求客户端在首次登录时更改用户密码。 |
| [CharType](../../aspose.finance.ofx.profile/signoninfo/chartype) { get; set; } | 获取或设置密码中允许的字符类型。 |
| [ClientuidRequire](../../aspose.finance.ofx.profile/signoninfo/clientuidrequire) { get; set; } | 获取或设置是否需要 CLIENTUID。 |
| [Max](../../aspose.finance.ofx.profile/signoninfo/max) { get; set; } | 获取或设置最大密码字符数 |
| [MFAChallengeFirst](../../aspose.finance.ofx.profile/signoninfo/mfachallengefirst) { get; set; } | 获取或设置客户端是否需要在第一次登录时发送 MFACHALLENGERQ，然后再发送任何其他请求。 |
| [MFAChallengeSupport](../../aspose.finance.ofx.profile/signoninfo/mfachallengesupport) { get; set; } | 获取或设置服务器是否支持 MFACHALLENGE 功能。 |
| [Min](../../aspose.finance.ofx.profile/signoninfo/min) { get; set; } | 获取或设置密码字符的最小数量。 |
| [Pinch](../../aspose.finance.ofx.profile/signoninfo/pinch) { get; set; } | 获取或设置服务器是否支持 PIN 更改请求。 |
| [SignonRealm](../../aspose.finance.ofx.profile/signoninfo/signonrealm) { get; set; } | 获取或设置此领域的标识。 |
| [Spaces](../../aspose.finance.ofx.profile/signoninfo/spaces) { get; set; } | 获取或设置是否允许在这些字符之上使用空格。 |
| [Special](../../aspose.finance.ofx.profile/signoninfo/special) { get; set; } | 获取或设置是否允许在这些字符之上使用特殊字符。 |
| [UserCredential1Label](../../aspose.finance.ofx.profile/signoninfo/usercredential1label) { get; set; } | 获取或设置用户凭据的文本提示。如果存在，除了 USERID 和 USERPASS 之外，还需要第三个凭据 (USERCRED1)。 |
| [UserCredential2Label](../../aspose.finance.ofx.profile/signoninfo/usercredential2label) { get; set; } | 获取或设置用户凭据的文本提示。如果存在，除了 USERID、USERPASS 和 USERCRED1 之外，还需要第四个凭证 (USERCRED2)。如果存在，则 UserCredential1Label 也必须存在。 |

### 也可以看看

* 命名空间 [Aspose.Finance.Ofx.Profile](../../aspose.finance.ofx.profile)
* 部件 [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->