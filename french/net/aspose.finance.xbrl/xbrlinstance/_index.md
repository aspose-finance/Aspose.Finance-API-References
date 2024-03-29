---
title: XbrlInstance
second_title: Référence de l'API Aspose.Finance pour .NET
description: Linstance XBRL est un fragment XML avec un élément racine ayant une balise xbrl. Linstance XBRL contient des faits de rapport dactivité chaque fait correspondant à unConcept./concept définis dans leur DTS de support. Linstance XBRL contient également des contextes et des unités qui fournissent des informations supplémentaires nécessaires pour interpréter les faits dans linstance.
type: docs
weight: 8200
url: /fr/net/aspose.finance.xbrl/xbrlinstance/
---
## XbrlInstance class

L'instance XBRL est un fragment XML avec un élément racine ayant une balise xbrl. L'instance XBRL contient des faits de rapport d'activité, chaque fait correspondant à un[`Concept`](../concept) définis dans leur DTS de support. L'instance XBRL contient également des contextes et des unités qui fournissent des informations supplémentaires nécessaires pour interpréter les faits dans l'instance.

```csharp
public class XbrlInstance
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ArcroleReferences](../../aspose.finance.xbrl/xbrlinstance/arcrolereferences) { get; set; } | Obtient ou définit la collection de[`ArcroleReference`](../arcrolereference) objets dans l'instance XBRL. |
| [Contexts](../../aspose.finance.xbrl/xbrlinstance/contexts) { get; set; } | Obtient ou définit la collection de[`Context`](../context) objets dans l'instance XBRL. |
| [Facts](../../aspose.finance.xbrl/xbrlinstance/facts) { get; } | Obtient la collection de[`Fact`](../fact) objets dans l'instance XBRL. |
| [FootnoteLinks](../../aspose.finance.xbrl/xbrlinstance/footnotelinks) { get; set; } | Obtient ou définit la collection de[`FootnoteLink`](../footnotelink) objets dans l'instance XBRL. |
| [Items](../../aspose.finance.xbrl/xbrlinstance/items) { get; } | Obtient la collection de[`Item`](../item) objets dans l'instance XBRL. |
| [LinkbaseRefCollection](../../aspose.finance.xbrl/xbrlinstance/linkbaserefcollection) { get; } | Obtient le[`LinkbaseRefCollection`](./linkbaserefcollection) dans le[`XbrlInstance`](../xbrlinstance) . |
| [RoleReferences](../../aspose.finance.xbrl/xbrlinstance/rolereferences) { get; set; } | Obtient ou définit la collection de[`RoleReference`](../rolereference) objets dans l'instance XBRL. |
| [SchemaLocation](../../aspose.finance.xbrl/xbrlinstance/schemalocation) { get; set; } | Obtient ou définit l'emplacement du schéma |
| [SchemaRefs](../../aspose.finance.xbrl/xbrlinstance/schemarefs) { get; } | Obtient la collection SchemaRef. |
| [Units](../../aspose.finance.xbrl/xbrlinstance/units) { get; set; } | Obtient ou définit la collection de[`Unit`](../unit) objets dans l'instance XBRL. |
| [ValidationErrors](../../aspose.finance.xbrl/xbrlinstance/validationerrors) { get; } | Obtient la collection d'erreur de validation. |
| [XbrlDocument](../../aspose.finance.xbrl/xbrlinstance/xbrldocument) { get; } | Obtenez le[`XbrlDocument`](./xbrldocument) qui contient cette instance. |

## Méthodes

| Nom | La description |
| --- | --- |
| [CreateElement](../../aspose.finance.xbrl/xbrlinstance/createelement)(string, string, string) | Créer un nouvel élément. |
| [GetAllLinkbaseRefCollections](../../aspose.finance.xbrl/xbrlinstance/getalllinkbaserefcollections)() | Obtenir toutes les collections de référence de base de liens dans les références d'instance et de schéma xbrl. |
| [GetArcroleTypeByURI](../../aspose.finance.xbrl/xbrlinstance/getarcroletypebyuri)(string) | Obtient l'ArcroleType qui a l'uri spécifié. |
| [GetConceptById](../../aspose.finance.xbrl/xbrlinstance/getconceptbyid)(string) | Obtient le concept qui a l'identifiant spécifié. |
| [GetConceptByLoc](../../aspose.finance.xbrl/xbrlinstance/getconceptbyloc)(Loc) | Obtient le concept par le localisateur. |
| [GetConceptByName](../../aspose.finance.xbrl/xbrlinstance/getconceptbyname)(string) | Obtient le concept qui porte le nom spécifié. |
| [GetContextById](../../aspose.finance.xbrl/xbrlinstance/getcontextbyid)(string) | Obtient le contexte qui a l'identifiant spécifié. |
| [GetPresentationLinks](../../aspose.finance.xbrl/xbrlinstance/getpresentationlinks)(string, string) | Obtient les liens de présentation dans l'instance xbrl. |
| [GetRoleTypeByURI](../../aspose.finance.xbrl/xbrlinstance/getroletypebyuri)(string) | Obtient le RoleType qui a l'uri spécifié. |
| [GetUnitById](../../aspose.finance.xbrl/xbrlinstance/getunitbyid)(string) | Obtient l'unité qui a l'identifiant spécifié. |
| [IsValid](../../aspose.finance.xbrl/xbrlinstance/isvalid)() | Vérifie si cette instance XBRL est valide. |
| [Validate](../../aspose.finance.xbrl/xbrlinstance/validate)() | Valide cette instance XBRL. |

### Voir également

* espace de noms [Aspose.Finance.Xbrl](../../aspose.finance.xbrl)
* Assemblée [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
