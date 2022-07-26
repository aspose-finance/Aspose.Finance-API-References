---
title: License
second_title: Справочник по API Aspose.Finance для .NET
description: Предоставляет способы лицензирования компонента.
type: docs
weight: 10
url: /ru/net/aspose.finance/license/
---
## License class

Предоставляет способы лицензирования компонента.

```csharp
public class License
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [License](license)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetLicense](../../aspose.finance/license/setlicense#setlicense)(Stream) | Лицензирует компонент. |
| [SetLicense](../../aspose.finance/license/setlicense#setlicense_1)(string) | Лицензирует компонент. |

### Примеры

В этом примере будет предпринята попытка найти файл лицензии MyLicense.lic в папке, содержащей  компонент, в папке, содержащей вызывающую сборку, в папке входной сборки и затем во встроенной ресурсы вызывающей сборки.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

файл jar компонента:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Смотрите также

* пространство имен [Aspose.Finance](../../aspose.finance)
* сборка [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->