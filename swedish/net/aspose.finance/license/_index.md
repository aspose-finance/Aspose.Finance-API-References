---
title: License
second_title: Aspose.Finance för .NET API-referens
description: Tillhandahåller metoder för att licensiera komponenten.
type: docs
weight: 10
url: /sv/net/aspose.finance/license/
---
## License class

Tillhandahåller metoder för att licensiera komponenten.

```csharp
public class License
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [License](license)() | Initierar en ny instans av den här klassen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [SetLicense](../../aspose.finance/license/setlicense#setlicense)(Stream) | Licensierar komponenten. |
| [SetLicense](../../aspose.finance/license/setlicense#setlicense_1)(string) | Licensierar komponenten. |

### Exempel

I det här exemplet kommer ett försök att göras att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller  komponenten, i mappen som innehåller den anropande sammansättningen, i mappen för postsammansättningen och sedan i de inbäddade resurserna för den anropande sammansättningen.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

komponentjarfilen:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Se även

* namnutrymme [Aspose.Finance](../../aspose.finance)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->