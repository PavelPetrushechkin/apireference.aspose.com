---
title: CompositeNodeT
second_title: Aspose.Note for .NET API Referansı
description: Diğer düğümleri içerebilen düğümler için temel genel sınıf.
type: docs
weight: 40
url: /tr/net/aspose.note/compositenode-1/
---
## CompositeNode&lt;T&gt; class

Diğer düğümleri içerebilen düğümler için temel genel sınıf.

```csharp
public abstract class CompositeNode<T> : CompositeNodeBase, ICompositeNode<T>
    where T : INode
```

| Parametre | Tanım |
| --- | --- |
| T | Bileşik düğümdeki öğelerin türü. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.note/node/document) { get; } | Düğümün belgesini alır. |
| [FirstChild](../../aspose.note/compositenode`1/firstchild) { get; } | Bu düğümün ilk alt düğümünü alır. |
| [IsComposite](../../aspose.note/compositenode`1/iscomposite) { get; } | Düğümün bileşik olup olmadığını kontrol eder. Doğruysa, düğümün alt düğümleri olabilir. |
| [LastChild](../../aspose.note/compositenode`1/lastchild) { get; } | Bu düğümün son alt düğümünü alır. |
| [NextSibling](../../aspose.note/node/nextsibling) { get; } | Aynı düğüm ağacı düzeyinde bir sonraki düğümü alır. |
| [NodeType](../../aspose.note/node/nodetype) { get; } | Düğüm türünü alır. |
| [ParentNode](../../aspose.note/node/parentnode) { get; } | Üst düğümü alır. |
| [PreviousSibling](../../aspose.note/node/previoussibling) { get; } | Aynı düğüm ağacı düzeyinde önceki düğümü alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Accept](../../aspose.note/compositenode`1/accept)(DocumentVisitor) | Düğümün ziyaretçisini kabul eder. |
| virtual [AppendChildFirst&lt;T1&gt;](../../aspose.note/compositenode`1/appendchildfirst)(T1) | Düğümü, bu düğüm için alt düğümler listesinin başına ekler. |
| virtual [AppendChildLast&lt;T1&gt;](../../aspose.note/compositenode`1/appendchildlast)(T1) | Düğümü, bu düğüm için alt düğümler listesinin sonuna ekler. |
| override [GetChildNodes&lt;T1&gt;](../../aspose.note/compositenode`1/getchildnodes#getchildnodes_1)() | Tüm alt düğümleri düğüm türüne göre alın. |
| [GetEnumerator](../../aspose.note/compositenode`1/getenumerator)() | Alt düğümler arasında yinelenen bir Numaralandırıcı döndürür.[`CompositeNode`](../compositenode-1) . |
| virtual [InsertChild&lt;T1&gt;](../../aspose.note/compositenode`1/insertchild)(int, T1) | Düğümü, bu düğüm için alt düğümler listesinde belirtilen konuma ekler. |
| [InsertChildrenRange](../../aspose.note/compositenode`1/insertchildrenrange#insertchildrenrange)(int, IEnumerable&lt;T&gt;) | Bu düğüm için alt düğümler listesinde belirtilen konumdan başlayarak düğümün sırasını ekler. |
| [InsertChildrenRange](../../aspose.note/compositenode`1/insertchildrenrange#insertchildrenrange_1)(int, params T[]) | Bu düğüm için alt düğümler listesinde belirtilen konumdan başlayarak düğümün sırasını ekler. |
| [RemoveChild&lt;T1&gt;](../../aspose.note/compositenode`1/removechild)(T1) | Alt düğümü kaldırır. |

### Ayrıca bakınız

* class [CompositeNodeBase](../compositenodebase)
* interface [ICompositeNode&lt;T&gt;](../icompositenode-1)
* interface [INode](../inode)
* ad alanı [Aspose.Note](../../aspose.note)
* toplantı [Aspose.Note](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Note.dll -->
