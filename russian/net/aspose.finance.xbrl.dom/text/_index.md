---
title: Text
second_title: Справочник по API Aspose.Finance для .NET
description: Класс представляет текстовое содержимое.
type: docs
weight: 7460
url: /ru/net/aspose.finance.xbrl.dom/text/
---
## Text class

Класс представляет текстовое содержимое.

```csharp
public class Text : CharacterData
```

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [BaseURI](../../aspose.finance.xbrl.dom/node/baseuri) { get; } | Получает абсолютный базовый URI этого узла или null, если реализация не смогла получить абсолютный URI. |
| [ChildNodes](../../aspose.finance.xbrl.dom/node/childnodes) { get; } | Получает дочерние узлы. |
| [Data](../../aspose.finance.xbrl.dom/characterdata/data) { get; set; } | Получает или задает символьные данные узла, реализующего этот интерфейс. |
| [FirstChild](../../aspose.finance.xbrl.dom/node/firstchild) { get; } | Получает первый дочерний элемент этого узла. Если такого узла нет, возвращается null. |
| [HasChildNodes](../../aspose.finance.xbrl.dom/node/haschildnodes) { get; } | Получает, есть ли у этого узла дочерние элементы. |
| [LastChild](../../aspose.finance.xbrl.dom/node/lastchild) { get; } | Получает последний дочерний элемент этого узла. Если такого узла нет, возвращается null. |
| [Length](../../aspose.finance.xbrl.dom/characterdata/length) { get; } | Получает количество 16-битных единиц, доступных для данных. Это может иметь нулевое значение, т. е. узлы CharacterData могут быть пустыми. |
| virtual [LocalName](../../aspose.finance.xbrl.dom/node/localname) { get; } | Получает локальную часть полного имени этого узла. |
| virtual [NamespaceURI](../../aspose.finance.xbrl.dom/node/namespaceuri) { get; } | Получает URI пространства имен этого узла. |
| [NextSibling](../../aspose.finance.xbrl.dom/node/nextsibling) { get; } | Получает узел, следующий сразу за этим узлом. Если такого узла нет, возвращается null. |
| override [NodeName](../../aspose.finance.xbrl.dom/text/nodename) { get; } | Получает имя этого текста. |
| [NodeType](../../aspose.finance.xbrl.dom/node/nodetype) { get; } | Получает тип узла. |
| virtual [NodeValue](../../aspose.finance.xbrl.dom/node/nodevalue) { get; set; } | Получает или задает значение этого узла в зависимости от его типа. |
| [OwnerDocument](../../aspose.finance.xbrl.dom/node/ownerdocument) { get; } | Получает объект документа, связанный с этим узлом. |
| [ParentNode](../../aspose.finance.xbrl.dom/node/parentnode) { get; } | Получает родительский узел. |
| virtual [Prefix](../../aspose.finance.xbrl.dom/node/prefix) { get; set; } | Получает или задает префикс пространства имен этого узла. |
| [PreviousSibling](../../aspose.finance.xbrl.dom/node/previoussibling) { get; } | Получает узел, непосредственно предшествующий этому узлу. Если такого узла нет, возвращается null. |
| virtual [TextContent](../../aspose.finance.xbrl.dom/node/textcontent) { get; set; } | Получает или задает текстовое содержимое этого узла и его потомков. |

## Методы

| Имя | Описание |
| --- | --- |
| [AppendChild](../../aspose.finance.xbrl.dom/node/appendchild)(Node) | Добавляет узел newChild в конец списка дочерних элементов этого узла. |
| virtual [AppendData](../../aspose.finance.xbrl.dom/characterdata/appenddata)(string) | Добавляет строку в конец символьных данных узла. |
| virtual [DeleteData](../../aspose.finance.xbrl.dom/characterdata/deletedata)(int, int) | Удаляет диапазон контента из узла. |
| virtual [InsertData](../../aspose.finance.xbrl.dom/characterdata/insertdata)(int, string) | Вставляет строку по указанному смещению. |
| [RemoveChild](../../aspose.finance.xbrl.dom/node/removechild)(Node) | Удаляет дочерний узел, указанный старым дочерним элементом, из списка дочерних элементов. |
| [ReplaceChild](../../aspose.finance.xbrl.dom/node/replacechild)(Node, Node) | Заменяет дочерний узел old child новым дочерним элементом в списке дочерних элементов и возвращает старый дочерний узел. |
| virtual [ReplaceData](../../aspose.finance.xbrl.dom/characterdata/replacedata)(int, int, string) | Заменяет символы, начинающиеся с указанного смещения, на указанную строку. |
| virtual [Substring](../../aspose.finance.xbrl.dom/characterdata/substring)(int, int) | Извлекает диапазон данных из узла. |

### Смотрите также

* class [CharacterData](../characterdata)
* пространство имен [Aspose.Finance.Xbrl.Dom](../../aspose.finance.xbrl.dom)
* сборка [Aspose.Finance](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Finance.dll -->
