---
title: NamedNodeMap
second_title: Aspose.Finance for .NET API 参考
description: 表示可以按名称访问的属性集合
type: docs
weight: 7420
url: /zh/net/aspose.finance.xbrl.dom/namednodemap/
---
## NamedNodeMap class

表示可以按名称访问的属性集合。

```csharp
public class NamedNodeMap : IEnumerable<Attr>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Item](../../aspose.finance.xbrl.dom/namednodemap/item) { get; } | 获取具有指定名称的属性。 (2 indexers) |
| [Length](../../aspose.finance.xbrl.dom/namednodemap/length) { get; } | 获取地图中的属性数量。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetEnumerator](../../aspose.finance.xbrl.dom/namednodemap/getenumerator)() | 返回一个遍历地图的枚举器。 |
| [GetNamedItem](../../aspose.finance.xbrl.dom/namednodemap/getnameditem)(string) | 获取 name 指定的属性。 |
| [GetNamedItemNS](../../aspose.finance.xbrl.dom/namednodemap/getnameditemns)(string, string) | 获取由本地名称和命名空间 URI 指定的属性。 |
| [RemoveNamedItem](../../aspose.finance.xbrl.dom/namednodemap/removenameditem)(string) | 删除由名称指定的属性。 |
| [RemoveNamedItemNS](../../aspose.finance.xbrl.dom/namednodemap/removenameditemns)(string, string) | 删除由本地名称和命名空间 URI 指定的属性。 |
| [SetNamedItem](../../aspose.finance.xbrl.dom/namednodemap/setnameditem)(Attr) | 使用其 nodeName 属性添加一个节点。如果此映射中已存在具有该名称的节点，则将其替换为新节点。自行替换节点无效。 |
| [SetNamedItemNS](../../aspose.finance.xbrl.dom/namednodemap/setnameditemns)(Attr) | 使用其 namespaceURI 和 localName 添加一个节点。如果具有该名称空间 URI 和该本地名称的节点已存在于此映射中，则将其替换为新节点。自行替换节点无效。 |

### 也可以看看

* class [Attr](../attr)
* 命名空间 [Aspose.Finance.Xbrl.Dom](../../aspose.finance.xbrl.dom)
* 部件 [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
