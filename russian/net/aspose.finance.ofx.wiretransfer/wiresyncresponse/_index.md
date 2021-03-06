---
title: WireSyncResponse
second_title: Справочник по API Aspose.Finance для .NET
description: Класс ответа синхронизации проводной транзакции.
type: docs
weight: 6410
url: /ru/net/aspose.finance.ofx.wiretransfer/wiresyncresponse/
---
## WireSyncResponse class

Класс ответа синхронизации проводной транзакции.

```csharp
public class WireSyncResponse : AbstractSyncResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WireSyncResponse](wiresyncresponse)() | Инициализирует новый экземпляр класса[`WireSyncResponse`](../wiresyncresponse). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BankAccountFrom](../../aspose.finance.ofx.wiretransfer/wiresyncresponse/bankaccountfrom) { get; set; } | Получает или задает значение из[`BankAccount`](../../aspose.finance.ofx/bankaccount). |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Да, если токен в запросе на синхронизацию старше, чем самая ранняя запись в таблице истории сервера. В этом случае некоторые ответы были потеряны. Нет, если токен в запросе на синхронизацию новее или совпадает с токеном в таблице истории сервера. |
| [OfxExtension](../../aspose.finance.ofx.wiretransfer/wiresyncresponse/ofxextension) { get; set; } | Получает или задает[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype). |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Получает или задает новый маркер синхронизации. |
| [WireTransactionResponses](../../aspose.finance.ofx.wiretransfer/wiresyncresponse/wiretransactionresponses) { get; set; } | Получает или задает коллекцию[`WireTransactionResponse`](../wiretransactionresponse). |

### Смотрите также

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* пространство имен [Aspose.Finance.Ofx.WireTransfer](../../aspose.finance.ofx.wiretransfer)
* сборка [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
