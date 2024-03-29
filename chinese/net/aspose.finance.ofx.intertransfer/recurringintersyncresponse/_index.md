---
title: RecurringInterSyncResponse
second_title: Aspose.Finance for .NET API 参考
description: 周期性跨行交易同步响应类
type: docs
weight: 2560
url: /zh/net/aspose.finance.ofx.intertransfer/recurringintersyncresponse/
---
## RecurringInterSyncResponse class

周期性跨行交易同步响应类。

```csharp
public class RecurringInterSyncResponse : AbstractSyncResponse
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RecurringInterSyncResponse](recurringintersyncresponse)() | 初始化一个新的实例[`RecurringInterSyncResponse`](../recurringintersyncresponse)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AccountFrom](../../aspose.finance.ofx.intertransfer/recurringintersyncresponse/accountfrom) { get; set; } | 获取或设置 from[`BankAccount`](../../aspose.finance.ofx/bankaccount)或者[`CreditCardAccount`](../../aspose.finance.ofx/creditcardaccount)或者[`LoanAccount`](../../aspose.finance.ofx/loanaccount). |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | 如果同步请求中的令牌比服务器历史表中最早的条目更旧，则为是。在这种情况下，一些响应已丢失。 如果同步请求中的令牌比服务器历史表中的令牌更新或匹配，则为否历史表. |
| [OfxExtension](../../aspose.finance.ofx.intertransfer/recurringintersyncresponse/ofxextension) { get; set; } | 获取或设置[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype). |
| [RecurringInterTransactionResponses](../../aspose.finance.ofx.intertransfer/recurringintersyncresponse/recurringintertransactionresponses) { get; set; } | 获取或设置的集合[`RecurringInterTransactionResponse`](../recurringintertransactionresponse). |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | 获取或设置新的同步令牌。 |

### 也可以看看

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* 命名空间 [Aspose.Finance.Ofx.InterTransfer](../../aspose.finance.ofx.intertransfer)
* 部件 [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
