---
title: InlineXbrlExcludeElement
second_title: Aspose.Finance for .NET API 参考
description: 该类表示内联xbrl排除元素
type: docs
weight: 7310
url: /zh/net/aspose.finance.xbrl.dom.inline/inlinexbrlexcludeelement/
---
## InlineXbrlExcludeElement class

该类表示内联xbrl排除元素。

```csharp
public class InlineXbrlExcludeElement : InlineXbrlElement
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Attributes](../../aspose.finance.xbrl.dom/element/attributes) { get; } | 获取元素的属性。 |
| virtual [BaseURI](../../aspose.finance.xbrl.dom/node/baseuri) { get; } | 获取此节点的绝对基 URI，如果实现无法获取绝对 URI，则为 null。 |
| [ChildElements](../../aspose.finance.xbrl.dom/element/childelements) { get; } | 获取元素的子元素。 |
| [ChildNodes](../../aspose.finance.xbrl.dom/node/childnodes) { get; } | 获取子节点。 |
| [FirstChild](../../aspose.finance.xbrl.dom/node/firstchild) { get; } | 获取此节点的第一个子节点。如果没有这样的节点，则返回 null。 |
| [HasChildNodes](../../aspose.finance.xbrl.dom/node/haschildnodes) { get; } | 获取此节点是否有子节点。 |
| [LastChild](../../aspose.finance.xbrl.dom/node/lastchild) { get; } | 获取此节点的最后一个子节点。如果没有这样的节点，则返回 null。 |
| override [LocalName](../../aspose.finance.xbrl.dom/element/localname) { get; } | 获取元素的本地名称。 |
| override [NamespaceURI](../../aspose.finance.xbrl.dom/element/namespaceuri) { get; } | 获取元素的命名空间 URI。 |
| [NextSibling](../../aspose.finance.xbrl.dom/node/nextsibling) { get; } | 获取紧跟该节点的节点。如果没有这样的节点，则返回 null。 |
| override [NodeName](../../aspose.finance.xbrl.dom/element/nodename) { get; } | 获取元素的节点名称。 |
| [NodeType](../../aspose.finance.xbrl.dom/node/nodetype) { get; } | 获取节点类型。 |
| virtual [NodeValue](../../aspose.finance.xbrl.dom/node/nodevalue) { get; set; } | 获取或设置此节点的值，具体取决于其类型。 |
| [OwnerDocument](../../aspose.finance.xbrl.dom/node/ownerdocument) { get; } | 获取与此节点关联的文档对象。 |
| [ParentElement](../../aspose.finance.xbrl.dom/element/parentelement) { get; } | 获取元素的父元素。 |
| [ParentNode](../../aspose.finance.xbrl.dom/node/parentnode) { get; } | 获取父节点。 |
| override [Prefix](../../aspose.finance.xbrl.dom/element/prefix) { get; } | 获取元素的前缀。 |
| [PreviousSibling](../../aspose.finance.xbrl.dom/node/previoussibling) { get; } | 获取紧接在此节点之前的节点。如果没有这样的节点，则返回 null。 |
| override [TextContent](../../aspose.finance.xbrl.dom/element/textcontent) { get; set; } | 获取元素的文本内容。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AppendChild](../../aspose.finance.xbrl.dom/node/appendchild)(Node) | 将节点 newChild 添加到该节点的子节点列表的末尾。 |
| [GetAttribute](../../aspose.finance.xbrl.dom/element/getattribute)(string) | 按名称获取属性值。 |
| [GetAttributeNS](../../aspose.finance.xbrl.dom/element/getattributens)(string, string) | 通过本地名称和命名空间 URI 获取属性值。 |
| [HasAttribute](../../aspose.finance.xbrl.dom/element/hasattribute)(string) | 在此元素上指定具有给定名称的属性或具有默认值时返回 true，否则返回 false。 |
| [HasAttributeNS](../../aspose.finance.xbrl.dom/element/hasattributens)(string, string) | 如果在此元素上指定了具有给定本地名称和命名空间 URI 的属性或具有默认值，则返回 true，否则返回 false。 |
| [RemoveAttribute](../../aspose.finance.xbrl.dom/element/removeattribute)(string) | 按名称删除属性。 |
| [RemoveAttributeNS](../../aspose.finance.xbrl.dom/element/removeattributens)(string, string) | 按本地名称和命名空间 URI 删除属性。 |
| [RemoveChild](../../aspose.finance.xbrl.dom/node/removechild)(Node) | 从子节点列表中删除由 old child 指示的子节点。 |
| [ReplaceChild](../../aspose.finance.xbrl.dom/node/replacechild)(Node, Node) | 用新的子节点替换子节点列表中的子节点old child，并返回旧的子节点。 |
| [SetAttribute](../../aspose.finance.xbrl.dom/element/setattribute)(string, string) | 添加一个新属性。如果元素中已存在具有该名称的属性，则其值将更改为 value 参数的值。 |
| [SetAttributeNS](../../aspose.finance.xbrl.dom/element/setattributens)(string, string, string) | 添加一个新属性。如果元素上已经存在具有相同本地名称和命名空间URI的属性，则将其前缀更改为qualifiedName的前缀部分，并将其值更改为值参数。 |

### 也可以看看

* class [InlineXbrlElement](../inlinexbrlelement)
* 命名空间 [Aspose.Finance.Xbrl.Dom.Inline](../../aspose.finance.xbrl.dom.inline)
* 部件 [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
