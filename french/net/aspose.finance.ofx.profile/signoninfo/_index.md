---
title: SignonInfo
second_title: Référence de l'API Aspose.Finance pour .NET
description: Classe dinformations de connexion.
type: docs
weight: 4770
url: /fr/net/aspose.finance.ofx.profile/signoninfo/
---
## SignonInfo class

Classe d'informations de connexion.

```csharp
public class SignonInfo
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SignonInfo](signoninfo)() | Initialise une nouvelle instance de[`SignonInfo`](../signoninfo) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AccessTokenRequire](../../aspose.finance.ofx.profile/signoninfo/accesstokenrequire) { get; set; } | Obtient ou définit si le serveur requiert ACCESSTOKEN pour toutes les requêtes à l'exception du profil. |
| [AuthTokenFirst](../../aspose.finance.ofx.profile/signoninfo/authtokenfirst) { get; set; } | Obtient ou définit si le serveur exige que les clients envoient AUTHTOKEN dans le cadre de la première connexion. |
| [AuthTokenInfoUrl](../../aspose.finance.ofx.profile/signoninfo/authtokeninfourl) { get; set; } | Obtient ou définit l'URL où les informations AUTHTOKEN sont fournies par l'institution exploitant le serveur OFX. |
| [AuthTokenLabel](../../aspose.finance.ofx.profile/signoninfo/authtokenlabel) { get; set; } | Obtient ou définit l'étiquette de texte pour AUTHTOKEN. |
| [CaseSensitive](../../aspose.finance.ofx.profile/signoninfo/casesensitive) { get; set; } | Obtient ou définit si le mot de passe est sensible à la casse. |
| [ChangePinFirst](../../aspose.finance.ofx.profile/signoninfo/changepinfirst) { get; set; } | Obtient ou définit si le serveur exige que les clients modifient le mot de passe utilisateur dans le cadre de la première connexion. |
| [CharType](../../aspose.finance.ofx.profile/signoninfo/chartype) { get; set; } | Obtient ou définit le type de caractères autorisés dans le mot de passe. |
| [ClientuidRequire](../../aspose.finance.ofx.profile/signoninfo/clientuidrequire) { get; set; } | Obtient ou définit si CLIENTUID est requis. |
| [Max](../../aspose.finance.ofx.profile/signoninfo/max) { get; set; } | Obtient ou définit le nombre maximal de caractères du mot de passe |
| [MFAChallengeFirst](../../aspose.finance.ofx.profile/signoninfo/mfachallengefirst) { get; set; } | Obtient ou définit si le client doit envoyer MFACHALLENGERQ dans le cadre de la première connexion, avant d'envoyer toute autre demande. |
| [MFAChallengeSupport](../../aspose.finance.ofx.profile/signoninfo/mfachallengesupport) { get; set; } | Obtient ou définit si le serveur prend en charge la fonctionnalité MFACHALLENGE. |
| [Min](../../aspose.finance.ofx.profile/signoninfo/min) { get; set; } | Obtient ou définit le nombre minimum de caractères du mot de passe. |
| [Pinch](../../aspose.finance.ofx.profile/signoninfo/pinch) { get; set; } | Obtient ou définit si le serveur prend en charge les demandes de changement de code PIN. |
| [SignonRealm](../../aspose.finance.ofx.profile/signoninfo/signonrealm) { get; set; } | Obtient ou définit l'identifie de ce domaine. |
| [Spaces](../../aspose.finance.ofx.profile/signoninfo/spaces) { get; set; } | Obtient ou définit si les espaces sont autorisés au-delà de ces caractères. |
| [Special](../../aspose.finance.ofx.profile/signoninfo/special) { get; set; } | Obtient ou définit si les caractères spéciaux sont autorisés en plus de ces caractères. |
| [UserCredential1Label](../../aspose.finance.ofx.profile/signoninfo/usercredential1label) { get; set; } | Obtient ou définit l'invite de texte pour les informations d'identification de l'utilisateur. S'il est présent, un troisième identifiant (USERCRED1) est requis en plus de USERID et USERPASS. |
| [UserCredential2Label](../../aspose.finance.ofx.profile/signoninfo/usercredential2label) { get; set; } | Obtient ou définit l'invite de texte pour les informations d'identification de l'utilisateur. S'il est présent, un quatrième identifiant (USERCRED2) est requis en plus de USERID, USERPASS et USERCRED1. S'il est présent, UserCredential1Label doit également être présent. |

### Voir également

* espace de noms [Aspose.Finance.Ofx.Profile](../../aspose.finance.ofx.profile)
* Assemblée [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->