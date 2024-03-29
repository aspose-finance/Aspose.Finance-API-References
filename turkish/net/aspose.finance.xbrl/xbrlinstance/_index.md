---
title: XbrlInstance
second_title: Aspose.Finance for .NET API Referansı
description: XBRL örneği bir xbrl etiketine sahip kök öğeye sahip XML parçasıdır. XBRL örneği her bir olgunun birConcept./concept destekleyici DTSlerinde tanımlanmıştır. XBRL örneği örnekteki gerçekleri yorumlamak için gereken ek bilgileri sağlayan bağlamları ve birimleri de içerir.
type: docs
weight: 8200
url: /tr/net/aspose.finance.xbrl/xbrlinstance/
---
## XbrlInstance class

XBRL örneği, bir xbrl etiketine sahip kök öğeye sahip XML parçasıdır. XBRL örneği, her bir olgunun bir[`Concept`](../concept) destekleyici DTS'lerinde tanımlanmıştır. XBRL örneği, örnekteki gerçekleri yorumlamak için gereken ek bilgileri sağlayan bağlamları ve birimleri de içerir.

```csharp
public class XbrlInstance
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ArcroleReferences](../../aspose.finance.xbrl/xbrlinstance/arcrolereferences) { get; set; } | Koleksiyonunu alır veya ayarlar[`ArcroleReference`](../arcrolereference) XBRL örneğindeki nesneler. |
| [Contexts](../../aspose.finance.xbrl/xbrlinstance/contexts) { get; set; } | Koleksiyonunu alır veya ayarlar[`Context`](../context) XBRL örneğindeki nesneler. |
| [Facts](../../aspose.finance.xbrl/xbrlinstance/facts) { get; } | Şunların koleksiyonunu alır:[`Fact`](../fact) XBRL örneğindeki nesneler. |
| [FootnoteLinks](../../aspose.finance.xbrl/xbrlinstance/footnotelinks) { get; set; } | Koleksiyonunu alır veya ayarlar[`FootnoteLink`](../footnotelink) XBRL örneğindeki nesneler. |
| [Items](../../aspose.finance.xbrl/xbrlinstance/items) { get; } | Şunların koleksiyonunu alır:[`Item`](../item) XBRL örneğindeki nesneler. |
| [LinkbaseRefCollection](../../aspose.finance.xbrl/xbrlinstance/linkbaserefcollection) { get; } | [`LinkbaseRefCollection`](./linkbaserefcollection) içinde[`XbrlInstance`](../xbrlinstance) . |
| [RoleReferences](../../aspose.finance.xbrl/xbrlinstance/rolereferences) { get; set; } | Koleksiyonunu alır veya ayarlar[`RoleReference`](../rolereference) XBRL örneğindeki nesneler. |
| [SchemaLocation](../../aspose.finance.xbrl/xbrlinstance/schemalocation) { get; set; } | Şema konumunu alır veya ayarlar |
| [SchemaRefs](../../aspose.finance.xbrl/xbrlinstance/schemarefs) { get; } | SchemaRef koleksiyonunu alır. |
| [Units](../../aspose.finance.xbrl/xbrlinstance/units) { get; set; } | Koleksiyonunu alır veya ayarlar[`Unit`](../unit) XBRL örneğindeki nesneler. |
| [ValidationErrors](../../aspose.finance.xbrl/xbrlinstance/validationerrors) { get; } | Doğrulama hatası koleksiyonunu alır. |
| [XbrlDocument](../../aspose.finance.xbrl/xbrlinstance/xbrldocument) { get; } | Alın[`XbrlDocument`](./xbrldocument) bu örneği içeren. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CreateElement](../../aspose.finance.xbrl/xbrlinstance/createelement)(string, string, string) | Yeni bir öğe oluşturun. |
| [GetAllLinkbaseRefCollections](../../aspose.finance.xbrl/xbrlinstance/getalllinkbaserefcollections)() | xbrl örneğindeki ve şema referanslarındaki tüm linkbase referans koleksiyonlarını alın. |
| [GetArcroleTypeByURI](../../aspose.finance.xbrl/xbrlinstance/getarcroletypebyuri)(string) | Belirtilen uri'ye sahip ArcroleType'ı alır. |
| [GetConceptById](../../aspose.finance.xbrl/xbrlinstance/getconceptbyid)(string) | Belirtilen kimliğe sahip konsepti alır. |
| [GetConceptByLoc](../../aspose.finance.xbrl/xbrlinstance/getconceptbyloc)(Loc) | Konsepti konumlandırıcıya göre alır. |
| [GetConceptByName](../../aspose.finance.xbrl/xbrlinstance/getconceptbyname)(string) | Belirtilen ada sahip konsepti alır. |
| [GetContextById](../../aspose.finance.xbrl/xbrlinstance/getcontextbyid)(string) | Belirtilen kimliğe sahip bağlamı alır. |
| [GetPresentationLinks](../../aspose.finance.xbrl/xbrlinstance/getpresentationlinks)(string, string) | xbrl örneğindeki sunum bağlantılarını alır. |
| [GetRoleTypeByURI](../../aspose.finance.xbrl/xbrlinstance/getroletypebyuri)(string) | Belirtilen uri. 'ye sahip RoleType'ı alır |
| [GetUnitById](../../aspose.finance.xbrl/xbrlinstance/getunitbyid)(string) | Belirtilen kimliğe sahip birimi alır. |
| [IsValid](../../aspose.finance.xbrl/xbrlinstance/isvalid)() | Bu XBRL örneğinin geçerli olup olmadığını kontrol eder. |
| [Validate](../../aspose.finance.xbrl/xbrlinstance/validate)() | Bu XBRL örneğini doğrular. |

### Ayrıca bakınız

* ad alanı [Aspose.Finance.Xbrl](../../aspose.finance.xbrl)
* toplantı [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
