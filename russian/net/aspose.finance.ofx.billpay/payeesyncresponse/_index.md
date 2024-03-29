---
title: PayeeSyncResponse
second_title: Справочник по API Aspose.Finance для .NET
description: Класс ответа синхронизации списка получателей.
type: docs
weight: 1020
url: /ru/net/aspose.finance.ofx.billpay/payeesyncresponse/
---
## PayeeSyncResponse class

Класс ответа синхронизации списка получателей.

```csharp
public class PayeeSyncResponse : AbstractSyncResponse
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PayeeSyncResponse](payeesyncresponse)() | Инициализирует новый экземпляр[`PayeeSyncResponse`](../payeesyncresponse) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [LostSynchronization](../../aspose.finance.ofx/abstractsyncresponse/lostsynchronization) { get; set; } | Да, если токен в запросе на синхронизацию старше самой ранней записи в таблице истории сервера. В этом случае некоторые ответы были потеряны. Нет, если токен в запросе на синхронизацию новее или совпадает с токеном в таблице сервера. таблица истории. |
| [OfxExtension](../../aspose.finance.ofx.billpay/payeesyncresponse/ofxextension) { get; set; } | Получает или задает[`OfxExtensionType`](../../aspose.finance.ofx/ofxextensiontype) . |
| [PayeeTransactionResponses](../../aspose.finance.ofx.billpay/payeesyncresponse/payeetransactionresponses) { get; set; } | Получает или задает коллекцию[`PayeeTransactionResponse`](../payeetransactionresponse) . |
| [Token](../../aspose.finance.ofx/abstractsyncresponse/token) { get; set; } | Получает или задает новый маркер синхронизации. |

### Смотрите также

* class [AbstractSyncResponse](../../aspose.finance.ofx/abstractsyncresponse)
* пространство имен [Aspose.Finance.Ofx.BillPay](../../aspose.finance.ofx.billpay)
* сборка [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
