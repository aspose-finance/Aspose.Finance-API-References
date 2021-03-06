---
title: StopCheckSyncResponse
second_title: Aspose.Finance for .NET API 参考
description: Stop 检查同步响应类
type: docs
weight: 750
url: /zh/net/aspose.finance.ofx.bank/stopchecksyncresponse/
---
## StopCheckSyncResponse class

Stop 检查同步响应类。

```csharp
public class StopCheckSyncResponse : AbstractSyncResponse
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [StopCheckSyncResponse](stopchecksyncresponse)() | 初始化[`StopCheckSyncResponse`](../stopchecksyncresponse)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BankAccountFrom](../../aspose.finance.ofx.bank/stopchecksyncresponse/bankaccountfrom) { get; set; } | 获取或设置[`BankAccount`](../../aspose.finance.ofx/bankaccount)的来源。 |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | 如果同步请求中的令牌早于服务器历史记录表中的最早条目，则是。在这种情况下，一些响应已经丢失。 如果同步请求中的令牌比服务器历史记录表中的令牌更新或匹配，则否。 |
| [OfxExtension](../../aspose.finance.ofx.bank/stopchecksyncresponse/ofxextension) { get; set; } | 获取或设置[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype)。 |
| [StopCheckTransactionResponses](../../aspose.finance.ofx.bank/stopchecksyncresponse/stopchecktransactionresponses) { get; set; } | 获取或设置[`StopCheckTransactionResponse`](../stopchecktransactionresponse)的集合。 |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | 获取或设置新的同步令牌。 |

### 也可以看看

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* 命名空间 [Aspose.Finance.Ofx.Bank](../../aspose.finance.ofx.bank)
* 部件 [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
