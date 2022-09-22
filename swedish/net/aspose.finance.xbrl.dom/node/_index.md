---
title: Node
second_title: Aspose.Finance för .NET API-referens
description: Nodeklassen är den primära datatypen för hela dokumentobjektmodellen. Den representerar en enda nod i dokumentträdet.
type: docs
weight: 7430
url: /sv/net/aspose.finance.xbrl.dom/node/
---
## Node class

Node-klassen är den primära datatypen för hela dokumentobjektmodellen. Den representerar en enda nod i dokumentträdet.

```csharp
public abstract class Node
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [BaseURI](../../aspose.finance.xbrl.dom/node/baseuri) { get; } | Får den absoluta bas-URI för denna nod eller noll om implementeringen inte kunde erhålla en absolut URI. |
| [ChildNodes](../../aspose.finance.xbrl.dom/node/childnodes) { get; } | Hämtar barnnoderna. |
| [FirstChild](../../aspose.finance.xbrl.dom/node/firstchild) { get; } | Får det första barnet till denna nod. Om det inte finns någon sådan nod, returnerar detta null. |
| [HasChildNodes](../../aspose.finance.xbrl.dom/node/haschildnodes) { get; } | Hämtar om denna nod har några barn. |
| [LastChild](../../aspose.finance.xbrl.dom/node/lastchild) { get; } | Hämtar det sista barnet till denna nod. Om det inte finns någon sådan nod, returnerar detta null. |
| virtual [LocalName](../../aspose.finance.xbrl.dom/node/localname) { get; } | Hämtar den lokala delen av det kvalificerade namnet på denna nod. |
| virtual [NamespaceURI](../../aspose.finance.xbrl.dom/node/namespaceuri) { get; } | Hämtar namnområdets URI för denna nod. |
| [NextSibling](../../aspose.finance.xbrl.dom/node/nextsibling) { get; } | Hämtar noden omedelbart efter denna nod. Om det inte finns någon sådan nod, returnerar detta null. |
| abstract [NodeName](../../aspose.finance.xbrl.dom/node/nodename) { get; } | Hämtar nodnamnet, beroende på dess typ. |
| [NodeType](../../aspose.finance.xbrl.dom/node/nodetype) { get; } | Hämtar nodtypen. |
| virtual [NodeValue](../../aspose.finance.xbrl.dom/node/nodevalue) { get; set; } | Hämtar eller ställer in värdet för denna nod, beroende på dess typ. |
| [OwnerDocument](../../aspose.finance.xbrl.dom/node/ownerdocument) { get; } | Hämtar dokumentobjektet som är associerat med denna nod. |
| [ParentNode](../../aspose.finance.xbrl.dom/node/parentnode) { get; } | Hämtar den överordnade noden. |
| virtual [Prefix](../../aspose.finance.xbrl.dom/node/prefix) { get; set; } | Hämtar eller ställer in namnområdesprefixet för denna nod. |
| [PreviousSibling](../../aspose.finance.xbrl.dom/node/previoussibling) { get; } | Hämtar noden omedelbart före denna nod. Om det inte finns någon sådan nod, returnerar detta null. |
| virtual [TextContent](../../aspose.finance.xbrl.dom/node/textcontent) { get; set; } | Hämtar eller ställer in textinnehållet för denna nod och dess avkomlingar. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AppendChild](../../aspose.finance.xbrl.dom/node/appendchild)(Node) | Lägger till noden newChild i slutet av listan över underordnade till denna nod. |
| [RemoveChild](../../aspose.finance.xbrl.dom/node/removechild)(Node) | Tar bort den underordnade noden som indikeras av gammalt barn från listan över barn. |
| [ReplaceChild](../../aspose.finance.xbrl.dom/node/replacechild)(Node, Node) | Ersätter det gamla underordnade barnet med nytt underordnat i listan över underordnade och returnerar den gamla underordnade noden. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [COMMENT_NODE](../../aspose.finance.xbrl.dom/node/comment_node) | Kommentarsnodtyp. |
| const [DOCUMENT_NODE](../../aspose.finance.xbrl.dom/node/document_node) | Dokumentnodtyp. |
| const [DOCUMENT_TYPE_NODE](../../aspose.finance.xbrl.dom/node/document_type_node) | Dokumenttyp nodtyp. |
| const [ELEMENT_NODE](../../aspose.finance.xbrl.dom/node/element_node) | Element nodtyp. |
| const [PROCESSING_INSTRUCTION_NODE](../../aspose.finance.xbrl.dom/node/processing_instruction_node) | Bearbetningsinstruktionsnodtyp. |
| const [TEXT_NODE](../../aspose.finance.xbrl.dom/node/text_node) | Textnodtyp. |

### Se även

* namnutrymme [Aspose.Finance.Xbrl.Dom](../../aspose.finance.xbrl.dom)
* hopsättning [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->