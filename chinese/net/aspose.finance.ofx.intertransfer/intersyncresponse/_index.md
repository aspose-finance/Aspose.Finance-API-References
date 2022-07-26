---
title: InterSyncResponse
second_title: Aspose.Finance for .NET API 参考
description: 跨行交易同步响应类
type: docs
weight: 2460
url: /zh/net/aspose.finance.ofx.intertransfer/intersyncresponse/
---
## InterSyncResponse class

跨行交易同步响应类。

```csharp
public class InterSyncResponse : AbstractSyncResponse
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [InterSyncResponse](intersyncresponse)() | 初始化[`InterSyncResponse`](../intersyncresponse)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.intertransfer/intersyncresponse/accountfrom) { get; set; } | 获取或设置来自[`BankAccount`](../../aspose.finance.ofx/bankaccount)或[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount)或[`LoanAccount`](../../aspose.finance.ofx/loanaccount)。 |
| [InterTransactionResponses](../../aspose.finance.ofx.intertransfer/intersyncresponse/intertransactionresponses) { get; set; } | 获取或设置[`InterTransactionResponse`](../intertransactionresponse)的集合。 |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | 如果同步请求中的令牌早于服务器历史记录表中的最早条目，则是。在这种情况下，一些响应已经丢失。 如果同步请求中的令牌比服务器历史记录表中的令牌更新或匹配，则否。 |
| [OfxExtension](../../aspose.finance.ofx.intertransfer/intersyncresponse/ofxextension) { get; set; } | 获取或设置[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype)。 |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | 获取或设置新的同步令牌。 |

### 也可以看看

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* 命名空间 [Aspose.Finance.Ofx.InterTransfer](../../aspose.finance.ofx.intertransfer)
* 部件 [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->