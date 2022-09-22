---
title: License
second_title: Référence de l'API Aspose.Finance pour .NET
description: Fournit des méthodes pour autoriser le composant.
type: docs
weight: 10
url: /fr/net/aspose.finance/license/
---
## License class

Fournit des méthodes pour autoriser le composant.

```csharp
public class License
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [License](license)() | Initialise une nouvelle instance de cette classe. |

## Méthodes

| Nom | La description |
| --- | --- |
| [SetLicense](../../aspose.finance/license/setlicense#setlicense)(Stream) | Licence du composant. |
| [SetLicense](../../aspose.finance/license/setlicense#setlicense_1)(string) | Licence du composant. |

### Exemples

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier qui contient  le composant, dans le dossier qui contient l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources embarquées de l'assembly appelant.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

le fichier jar du composant :

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Voir également

* espace de noms [Aspose.Finance](../../aspose.finance)
* Assemblée [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->