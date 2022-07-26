---
title: PendingTransaction
second_title: Справочник по API Aspose.Finance для .NET
description: Этот класс описывает одну незавершенную транзакцию. Он определяет тип транзакции и дату ее инициирования. Класс также может предоставлять дополнительную информацию помогающую покупателю распознать транзакцию номер чека имя получателя платежа и памятку.
type: docs
weight: 4250
url: /ru/net/aspose.finance.ofx/pendingtransaction/
---
## PendingTransaction class

Этот класс описывает одну незавершенную транзакцию. Он определяет тип транзакции и дату ее инициирования. Класс также может предоставлять дополнительную информацию, помогающую покупателю распознать транзакцию: номер чека, имя получателя платежа и памятку.

```csharp
public class PendingTransaction
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PendingTransaction](pendingtransaction)() | Инициализирует новый экземпляр класса[`PendingTransaction`](../pendingtransaction). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Currency](../../aspose.finance.ofx/pendingtransaction/currency) { get; set; } | Получает или задает[`Currency`](./currency). |
| [ExpireDate](../../aspose.finance.ofx/pendingtransaction/expiredate) { get; set; } | Получает или задает дату истечения срока удержания этой транзакции. Действителен только для TransactionType HOLD. |
| [ExtendedName](../../aspose.finance.ofx/pendingtransaction/extendedname) { get; set; } | Получает или задает расширенное имя получателя платежа или описание транзакции. |
| [ImageDatas](../../aspose.finance.ofx/pendingtransaction/imagedatas) { get; set; } | Получает или задает коллекцию[`ImageData`](../imagedata). |
| [Memo](../../aspose.finance.ofx/pendingtransaction/memo) { get; set; } | Получает или задает дополнительную информацию |
| [Name](../../aspose.finance.ofx/pendingtransaction/name) { get; set; } | Получает или задает имя получателя платежа или описание транзакции. |
| [OriginCurrency](../../aspose.finance.ofx/pendingtransaction/origincurrency) { get; set; } | Получает или задает Origin[`Currency`](./currency). |
| [ReferenceNumber](../../aspose.finance.ofx/pendingtransaction/referencenumber) { get; set; } | Получает или задает ссылочный номер, если он есть, для транзакции. |
| [TransactionAmount](../../aspose.finance.ofx/pendingtransaction/transactionamount) { get; set; } | Получает или задает сумму транзакции. |
| [TransactionDate](../../aspose.finance.ofx/pendingtransaction/transactiondate) { get; set; } | Получает или задает дату начала транзакции. |
| [TransactionType](../../aspose.finance.ofx/pendingtransaction/transactiontype) { get; set; } | Получает или задает тип транзакции. |

### Смотрите также

* пространство имен [Aspose.Finance.Ofx](../../aspose.finance.ofx)
* сборка [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->