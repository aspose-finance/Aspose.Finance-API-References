---
title: Metered
second_title: Aspose.Finance for .NET API Referansı
description: Ölçülen anahtarı ayarlamak için yöntemler sağlar.
type: docs
weight: 20
url: /tr/net/aspose.finance/metered/
---
## Metered class

Ölçülen anahtarı ayarlamak için yöntemler sağlar.

```csharp
public class Metered
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Metered](metered)() | Bu sınıfın yeni bir örneğini başlatır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [SetMeteredKey](../../aspose.finance/metered/setmeteredkey)(string, string) | Ölçülen genel ve özel anahtarı ayarlar |
| static [GetConsumptionCredit](../../aspose.finance/metered/getconsumptioncredit)() | Tüketim kredisi alır |
| static [GetConsumptionQuantity](../../aspose.finance/metered/getconsumptionquantity)() | size tüketim dosyası alır |

### Örnekler

Bu örnekte, ölçülen genel ve özel anahtarın ayarlanması denenecektir

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

bileşen jar dosyası:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Ayrıca bakınız

* ad alanı [Aspose.Finance](../../aspose.finance)
* toplantı [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->