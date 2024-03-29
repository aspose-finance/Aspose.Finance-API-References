---
title: Comment
second_title: Aspose.Finance für .NET-API-Referenz
description: Erbt von CharacterData und repräsentiert den Inhalt eines Kommentars.
type: docs
weight: 6650
url: /de/net/aspose.finance.xbrl.dom/comment/
---
## Comment class

Erbt von CharacterData und repräsentiert den Inhalt eines Kommentars.

```csharp
public class Comment : CharacterData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [BaseURI](../../aspose.finance.xbrl.dom/node/baseuri) { get; } | Ruft den absoluten Basis-URI dieses Knotens ab oder null, wenn die Implementierung keinen absoluten URI erhalten konnte. |
| [ChildNodes](../../aspose.finance.xbrl.dom/node/childnodes) { get; } | Ruft die untergeordneten Knoten ab. |
| [Data](../../aspose.finance.xbrl.dom/characterdata/data) { get; set; } | Ruft die Zeichendaten des Knotens ab, der diese Schnittstelle implementiert, oder legt sie fest. |
| [FirstChild](../../aspose.finance.xbrl.dom/node/firstchild) { get; } | Ruft das erste untergeordnete Element dieses Knotens ab. Wenn es keinen solchen Knoten gibt, gibt dies null zurück. |
| [HasChildNodes](../../aspose.finance.xbrl.dom/node/haschildnodes) { get; } | Ruft ab, ob dieser Knoten Kinder hat. |
| [LastChild](../../aspose.finance.xbrl.dom/node/lastchild) { get; } | Ruft das letzte untergeordnete Element dieses Knotens ab. Wenn es keinen solchen Knoten gibt, gibt dies null zurück. |
| [Length](../../aspose.finance.xbrl.dom/characterdata/length) { get; } | Ruft die Anzahl der 16-Bit-Einheiten ab, die über Daten verfügbar sind. Dieser kann den Wert Null haben, dh CharacterData-Knoten können leer sein. |
| virtual [LocalName](../../aspose.finance.xbrl.dom/node/localname) { get; } | Ruft den lokalen Teil des qualifizierten Namens dieses Knotens ab. |
| virtual [NamespaceURI](../../aspose.finance.xbrl.dom/node/namespaceuri) { get; } | Ruft den Namespace-URI dieses Knotens ab. |
| [NextSibling](../../aspose.finance.xbrl.dom/node/nextsibling) { get; } | Ruft den Knoten ab, der diesem Knoten unmittelbar folgt. Wenn es keinen solchen Knoten gibt, gibt dies null zurück. |
| override [NodeName](../../aspose.finance.xbrl.dom/comment/nodename) { get; } | Ruft den Knotennamen des Kommentars ab. |
| [NodeType](../../aspose.finance.xbrl.dom/node/nodetype) { get; } | Ruft den Knotentyp ab. |
| virtual [NodeValue](../../aspose.finance.xbrl.dom/node/nodevalue) { get; set; } | Ruft den Wert dieses Knotens ab oder legt ihn fest, abhängig von seinem Typ. |
| [OwnerDocument](../../aspose.finance.xbrl.dom/node/ownerdocument) { get; } | Ruft das diesem Knoten zugeordnete Dokumentobjekt ab. |
| [ParentNode](../../aspose.finance.xbrl.dom/node/parentnode) { get; } | Ruft den übergeordneten Knoten ab. |
| virtual [Prefix](../../aspose.finance.xbrl.dom/node/prefix) { get; set; } | Ruft das Namespace-Präfix dieses Knotens ab oder legt es fest. |
| [PreviousSibling](../../aspose.finance.xbrl.dom/node/previoussibling) { get; } | Ruft den Knoten ab, der diesem Knoten unmittelbar vorausgeht. Wenn es keinen solchen Knoten gibt, gibt dies null zurück. |
| virtual [TextContent](../../aspose.finance.xbrl.dom/node/textcontent) { get; set; } | Ruft den Textinhalt dieses Knotens und seiner Nachkommen ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendChild](../../aspose.finance.xbrl.dom/node/appendchild)(Node) | Fügt den Knoten newChild am Ende der Liste der Kinder dieses Knotens hinzu. |
| virtual [AppendData](../../aspose.finance.xbrl.dom/characterdata/appenddata)(string) | Hängt die Zeichenfolge an das Ende der Zeichendaten des Knotens an. |
| virtual [DeleteData](../../aspose.finance.xbrl.dom/characterdata/deletedata)(int, int) | Entfernt eine Reihe von Inhalten aus dem Knoten. |
| virtual [InsertData](../../aspose.finance.xbrl.dom/characterdata/insertdata)(int, string) | Fügt eine Zeichenfolge am angegebenen Offset ein. |
| [RemoveChild](../../aspose.finance.xbrl.dom/node/removechild)(Node) | Entfernt den durch old child angegebenen untergeordneten Knoten aus der Liste der untergeordneten Elemente. |
| [ReplaceChild](../../aspose.finance.xbrl.dom/node/replacechild)(Node, Node) | Ersetzt den alten untergeordneten Knoten des untergeordneten Knotens durch den neuen untergeordneten Knoten in der Liste der untergeordneten Elemente und gibt den alten untergeordneten Knoten zurück. |
| virtual [ReplaceData](../../aspose.finance.xbrl.dom/characterdata/replacedata)(int, int, string) | Ersetzt die Zeichen ab dem angegebenen Offset durch die angegebene Zeichenfolge. |
| virtual [Substring](../../aspose.finance.xbrl.dom/characterdata/substring)(int, int) | Extrahiert eine Reihe von Daten aus dem Knoten. |

### Siehe auch

* class [CharacterData](../characterdata)
* namensraum [Aspose.Finance.Xbrl.Dom](../../aspose.finance.xbrl.dom)
* Montage [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
