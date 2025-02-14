---
title: Document
second_title: Référence de l'API Aspose.SVG pour .NET
description: Le Document représente lintégralité du document HTML XML ou SVG. Conceptuellement il sagit de la racine de larborescence du document et fournit laccès principal aux données du document.
type: docs
weight: 810
url: /fr/net/aspose.svg.dom/document/
---
## Document class

Le Document représente l'intégralité du document HTML, XML ou SVG. Conceptuellement, il s'agit de la racine de l'arborescence du document et fournit l'accès principal aux données du document.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes) { get; } | Un NamedNodeMap contenant les attributs de ce nœud (si c'est un Element) ou null sinon. |
| override [BaseURI](../../aspose.svg.dom/document/baseuri) { get; } | L'URI de base absolu de ce nœud ou null si l'implémentation n'a pas pu obtenir d'URI absolu. |
| [CharacterSet](../../aspose.svg.dom/document/characterset) { get; } | Récupère l'encodage du document. |
| [Charset](../../aspose.svg.dom/document/charset) { get; } | Récupère l'encodage du document. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount) { get; } | Renvoie le nombre actuel de nœuds d'élément qui sont des enfants de cet élément. 0 si cet élément n'a pas de nœuds enfants qui sont de nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes) { get; } | Une NodeList qui contient tous les enfants de ce nœud. S'il n'y a pas d'enfants, il s'agit d'une NodeList ne contenant aucun nœud.. |
| [Children](../../aspose.svg.dom/document/children) { get; } | Renvoie les éléments enfants. |
| [ContentType](../../aspose.svg.dom/document/contenttype) { get; } | Obtient le type de contenu du document. |
| [Context](../../aspose.svg.dom/document/context) { get; } | Obtient le contexte de navigation actuel. |
| [DefaultView](../../aspose.svg.dom/document/defaultview) { get; } | L'attribut defaultView IDL de l'interface Document, lors de l'obtention, doit renvoyer l'objet WindowProxy du contexte de navigation de ce document, si ce document a un contexte de navigation associé, ou null sinon. |
| [Doctype](../../aspose.svg.dom/document/doctype) { get; } | La déclaration de type de document associée à ce document. |
| [DocumentElement](../../aspose.svg.dom/document/documentelement) { get; } | Il s'agit d'un attribut de commodité qui permet un accès direct au nœud enfant qui est l'élément de document du document. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi) { get; } | L'emplacement du document ou null si non défini ou si le document a été créé à l'aide de DOMImplementation.createDocument. |
| [FirstChild](../../aspose.svg.dom/node/firstchild) { get; } | Le premier enfant de ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild) { get; } | Renvoie le premier nœud d'élément enfant de cet élément. null si cet élément n'a pas d'éléments enfants. |
| [Implementation](../../aspose.svg.dom/document/implementation) { get; } | L'objet DOMImplementation qui gère ce document. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding) { get; } | Récupère l'encodage du document. |
| [LastChild](../../aspose.svg.dom/node/lastchild) { get; } | Le dernier enfant de ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild) { get; } | Renvoie le dernier nœud d'élément enfant de cet élément. null si cet élément n'a pas d'éléments enfants. |
| virtual [LocalName](../../aspose.svg.dom/node/localname) { get; } | Renvoie la partie locale du nom qualifié de ce nœud. Pour les nœuds de tout type autre que ELEMENT_NODE et ATTRIBUTE_NODE et les nœuds créés avec une méthode DOM Niveau 1, comme Document.createElement(), c'est toujours null. |
| [Location](../../aspose.svg.dom/document/location) { get; } | L'emplacement du document. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri) { get; } | L'URI de l'espace de noms de ce nœud, ou null s'il n'est pas spécifié. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling) { get; } | Renvoie le prochain nœud d'élément frère de cet élément. null si cet élément n'a aucun nœud frère d'élément qui vient après celui-ci dans l'arborescence du document. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling) { get; } | Le nœud suivant immédiatement ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| override [NodeName](../../aspose.svg.dom/document/nodename) { get; } | Le nom de ce nœud, en fonction de son type. |
| override [NodeType](../../aspose.svg.dom/document/nodetype) { get; } | Un code représentant le type de l'objet sous-jacent. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue) { get; set; } | La valeur de ce nœud, en fonction de son type. |
| [Origin](../../aspose.svg.dom/document/origin) { get; } | Obtient l'origine du document. |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument) { get; } | Obtient le document propriétaire. |
| [ParentElement](../../aspose.svg.dom/node/parentelement) { get; } | Obtient le parent[`Element`](../element) de ce nœud. |
| [ParentNode](../../aspose.svg.dom/node/parentnode) { get; } | Le parent de ce nœud. Tous les nœuds, à l'exception de Attr, Document, DocumentFragment, Entity et Notation peuvent avoir un parent. Cependant, si un nœud vient d'être créé et n'a pas encore été ajouté à l'arbre, ou s'il a été supprimé de l'arbre, c'est null. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix) { get; set; } | Le préfixe d'espace de noms de ce nœud, ou null s'il n'est pas spécifié. Lorsqu'il est défini comme étant nul, sa définition n'a aucun effet |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling) { get; } | Renvoie le nœud d'élément frère précédent de cet élément. null si cet élément n'a aucun nœud frère d'élément qui précède celui-ci dans l'arborescence du document. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling) { get; } | Le nœud précédant immédiatement ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| [ReadyState](../../aspose.svg.dom/document/readystate) { get; } | Renvoie l'état de préparation du document. Le « chargement » pendant le chargement du document, « interactif » une fois qu'il a terminé l'analyse mais charge toujours les sous-ressources, et « complet » une fois qu'il a été chargé. |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking) { get; set; } | Un attribut spécifiant si la vérification des erreurs est appliquée ou non. Lorsqu'il est défini sur false, l'implémentation est libre de ne pas tester tous les cas d'erreur possibles normalement définis sur les opérations DOM, et de ne pas déclencher d'exception DOMException sur les opérations DOM ou de signaler des erreurs lors de l'utilisation de Document.normalizeDocument(). En cas d'erreur, le comportement est indéfini. Cet attribut est vrai par défaut. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets) { get; } | Une liste contenant toutes les feuilles de style explicitement liées ou incorporées dans un document. Pour les documents HTML, cela inclut les feuilles de style externes, incluses via l'élément HTML LINK, et les éléments STYLE en ligne. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent) { get; set; } | Cet attribut renvoie le contenu textuel de ce nœud et de ses descendants. Lorsqu'il est défini comme étant nul, sa définition n'a aucun effet. Lors de la définition, tous les enfants possibles que ce nœud peut avoir sont supprimés et, si la nouvelle chaîne n'est pas vide ou nulle, remplacés par un seul nœud de texte contenant la chaîne à laquelle cet attribut est défini. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone) { get; set; } | Un attribut spécifiant, dans le cadre de la déclaration XML, si ce document est autonome. Ceci est faux lorsqu'il n'est pas spécifié. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion) { get; set; } | Un attribut spécifiant, dans le cadre de la déclaration XML, le numéro de version de ce document. S'il n'y a pas de déclaration et si ce document prend en charge la fonctionnalité "XML", la valeur est "1.0". Si ce document ne prend pas en charge la fonctionnalité "XML", la valeur est toujours nulle. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AppendChild](../../aspose.svg.dom/node/appendchild)(Node) | Ajoute le nœud newChild à la fin de la liste des enfants de ce nœud. Si le newChild est déjà dans l'arborescence, il est d'abord supprimé. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)() | Renvoie un doublon de ce nœud, c'est-à-dire qu'il sert de constructeur de copie générique pour les nœuds. Le nœud dupliqué n'a pas de parent (parentNode est nul) et pas de données utilisateur. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)(bool) | Renvoie un doublon de ce nœud, c'est-à-dire qu'il sert de constructeur de copie générique pour les nœuds. Le nœud dupliqué n'a pas de parent (parentNode est nul) et pas de données utilisateur. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute)(string) | Crée un Attr du nom donné. |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens)(string, string) | Crée un attribut du nom qualifié donné et de l'URI de l'espace de noms. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection)(string) | Crée un nœud CDATASection dont la valeur est la chaîne spécifiée. |
| [CreateComment](../../aspose.svg.dom/document/createcomment)(string) | Crée un nœud Commentaire en fonction de la chaîne spécifiée. |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment)() | Crée un objet DocumentFragment vide. |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype)(string, string, string, string) | Crée un nœud DocumentType. |
| [CreateElement](../../aspose.svg.dom/document/createelement)(string) | Crée un élément du type spécifié. Notez que l'instance renvoyée implémente l'interface Element, de sorte que les attributs peuvent être spécifiés directement sur l'objet renvoyé. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns)(string, string) | Crée un élément du nom qualifié donné et de l'URI de l'espace de noms. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference)(string) | Crée un objet EntityReference. De plus, si l'entité référencée est connue, la liste enfant du nœud EntityReference est identique à celle du nœud Entity correspondant. |
| [CreateEvent](../../aspose.svg.dom/document/createevent)(string) | Crée un[`Event`](../../aspose.svg.dom.events/event) d'un type pris en charge par l'implémentation. |
| [CreateExpression](../../aspose.svg.dom/document/createexpression)(string, IXPathNSResolver) | Crée une expression XPath analysée avec des espaces de noms résolus. Ceci est utile lorsqu'une expression sera réutilisée dans une application car cela permet de compiler la chaîne d'expression dans une forme interne plus efficace et de pré-résoudre tous les préfixes d'espace de noms qui se produisent dans l'expression. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator#createnodeiterator)(Node) | Créer un nouveau NodeIterator sur la sous-arborescence enracinée au nœud spécifié. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator#createnodeiterator_1)(Node, long) | Créer un nouveau NodeIterator sur la sous-arborescence enracinée au nœud spécifié. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator#createnodeiterator_2)(Node, long, INodeFilter) | Créer un nouveau NodeIterator sur la sous-arborescence enracinée au nœud spécifié. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver)(Node) | Adapte n'importe quel nœud DOM pour résoudre les espaces de noms afin qu'une expression XPath puisse être facilement évaluée par rapport au contexte du nœud où elle est apparue dans le document. Cet adaptateur fonctionne comme la méthode DOM niveau 3`lookupNamespaceURI` sur les nœuds en résolvant le namespaceURI à partir d'un préfixe donné en utilisant les informations actuelles disponibles dans la hiérarchie du nœud au moment où lookupNamespaceURI est appelé, en résolvant également correctement le préfixe xml implicite. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction)(string, string) | Crée un nœud ProcessingInstruction avec le nom et les chaînes de données spécifiés. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode)(string) | Crée un nœud de texte en fonction de la chaîne spécifiée. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker#createtreewalker)(Node) | Créer un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker#createtreewalker_1)(Node, long) | Créer un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker#createtreewalker_2)(Node, long, INodeFilter) | Créer un nouveau TreeWalker sur le sous-arbre enraciné au nœud spécifié. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent)(Event) | Cette méthode permet de répartir les événements dans le modèle d'événement des implémentations. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| [Evaluate](../../aspose.svg.dom/document/evaluate)(string, Node, IXPathNSResolver, XPathResultType, object) | Évalue une chaîne d'expression XPath et renvoie un résultat du type spécifié si possible. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid)(string) | Renvoie l'élément qui a un attribut ID avec la valeur donnée. Si aucun élément de ce type n'existe, cela renvoie null. Si plusieurs éléments ont un attribut ID avec cette valeur, ce qui est renvoyé est indéfini. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname)(string) | Renvoie un objet NodeList actif contenant tous les éléments du document qui ont toutes les classes spécifiées dans l'argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname)(string) | Renvoie une NodeList de tous les éléments dans l'ordre du document avec un nom de balise donné et sont contenus dans le document. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens)(string, string) | Renvoie une NodeList de tous les éléments avec un nom local et un URI d'espace de noms donnés dans l'ordre du document. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes)() | Renvoie si ce nœud (s'il s'agit d'un élément) a des attributs |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes)() | Renvoie si ce nœud a des enfants. |
| [ImportNode](../../aspose.svg.dom/document/importnode)(Node, bool) | Importe un nœud d'un autre document vers ce document, sans modifier ni supprimer le nœud source du document d'origine ; cette méthode crée une nouvelle copie du nœud source. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore)(Node, Node) | Insère le nœud avant le nœud enfant existant. Si enfant est nul, insère le nœud à la fin de la liste des enfants. Si enfant est un objet DocumentFragment, tous ses enfants sont insérés, dans le même ordre, avant enfant. Si l'enfant est déjà dans l'arborescence, il est d'abord supprimé. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace)(string) | Cette méthode vérifie si le namespaceURI spécifié est l'espace de noms par défaut ou non. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode)(Node) | Teste si deux nœuds sont égaux. Cette méthode teste l'égalité des nœuds, pas la similitude (c'est-à-dire si les deux nœuds sont des références au même objet) qui peut être testée avec Node.isSameNode(). Tous les nœuds identiques seront également égaux, bien que l'inverse puisse ne pas être vrai. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode)(Node) | Renvoie si ce nœud est le même nœud que celui donné. Cette méthode permet de déterminer si deux références de nœud renvoyées par l'implémentation font référence au même objet. Lorsque deux références de nœud sont des références au même objet, même via un proxy, les références peuvent être utilisées de manière complètement interchangeable, de sorte que tous les attributs ont les mêmes valeurs et que l'appel de la même méthode DOM sur l'une ou l'autre des références a toujours exactement le même effet. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri)(string) | Recherchez l'URI de l'espace de noms associé au préfixe donné, à partir de ce nœud. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix)(string) | Recherchez le préfixe associé à l'URI de l'espace de noms donné, à partir de ce nœud. Les déclarations d'espace de noms par défaut sont ignorées par cette méthode. Voir Recherche de préfixe d'espace de noms pour plus de détails sur l'algorithme utilisé par cette méthode. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate)(RequestMessage) | Charge le document en fonction de l'objet de requête spécifié, en remplaçant le contenu précédent. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_4)(string) | Charge le document à l'URL (Uniform Resource Locator) spécifiée dans l'instance actuelle, en remplaçant le contenu précédent. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_1)(Url) | Charge le document à l'URL (Uniform Resource Locator) spécifiée dans l'instance actuelle, en remplaçant le contenu précédent. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_3)(Stream, string) | Charge le document à partir du contenu spécifié et utilise baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. Le chargement du document commence à partir de la position actuelle dans le flux. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_2)(Stream, Url) | Charge le document à partir du contenu spécifié et utilise baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. Le chargement du document commence à partir de la position actuelle dans le flux. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_6)(string, string) | Charge le document à partir du contenu spécifié et utilise baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_5)(string, Url) | Charge le document à partir du contenu spécifié et utilise baseUri pour résoudre les ressources relatives, en remplaçant le contenu précédent. |
| [Normalize](../../aspose.svg.dom/node/normalize)() | Met tous les nœuds de texte dans toute la profondeur de la sous-arborescence sous ce nœud, y compris les nœuds d'attribut, dans une forme "normale" où seule la structure (par exemple, les éléments, les commentaires, les instructions de traitement, les sections CDATA et les références d'entité) sépare le texte nœuds, c'est-à-dire qu'il n'y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour s'assurer que la vue DOM d'un document est la même que s'il avait été enregistré et rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d'une arborescence de document particulière doivent être utilisé. Si le paramètre "normalize-characters" de l'objet DOMConfiguration attaché au Node.ownerDocument est vrai, cette méthode normalisera également complètement les caractères des nœuds Text. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector)(string) | Renvoie le premier élément du document, qui correspond à selector |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall)(string) | Renvoie une NodeList de tous les éléments du document, qui correspondent à selector |
| [RemoveChild](../../aspose.svg.dom/node/removechild)(Node) | Supprime le nœud enfant indiqué par oldChild de la liste des enfants et le renvoie. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) est retiré d'un[`EventTarget`](../eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) est retiré d'un[`EventTarget`](../eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) est retiré d'un[`EventTarget`](../eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto)(IDevice) | Cette méthode est utilisée pour afficher le contenu du document actuel sur un périphérique graphique spécifié. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild)(Node, Node) | Remplace le nœud enfant oldChild par newChild dans la liste des enfants et renvoie le nœud oldChild. Si newChild est un objet DocumentFragment, oldChild est remplacé par tous les enfants DocumentFragment, qui sont insérés dans le même ordre. Si le newChild est déjà dans l'arborescence, il est d'abord supprimé. |
| override [ToString](../../aspose.svg.dom/node/tostring)() | Renvoie unString qui représente cette instance. |
| [Write](../../aspose.svg.dom/document/write)(params string[]) | Ecrit une chaîne de texte dans un flux de documents ouvert par open(). Notez que la fonction produira un document qui n'est pas nécessairement piloté par une DTD et peut donc être produire un résultat invalide dans le contexte du document. |
| [WriteLn](../../aspose.svg.dom/document/writeln)(params string[]) | Écrit une chaîne de texte suivie d'un caractère de saut de ligne dans un flux document ouvert par open(). Notez que la fonction va produire un document qui n'est pas nécessairement piloté par une DTD et peut donc produire un résultat invalide dans le contexte du document |

### Voir également

* class [Node](../node)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent)
* interface [IDocumentStyle](../../aspose.svg.dom.css/idocumentstyle)
* interface [IDocumentTraversal](../../aspose.svg.dom.traversal/idocumenttraversal)
* interface [IGlobalEventHandlers](../iglobaleventhandlers)
* interface [INonElementParentNode](../inonelementparentnode)
* interface [IParentNode](../iparentnode)
* interface [IXPathEvaluator](../../aspose.svg.dom.xpath/ixpathevaluator)
* espace de noms [Aspose.Svg.Dom](../../aspose.svg.dom)
* Assemblée [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
