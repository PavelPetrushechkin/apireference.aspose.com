---
title: AnimationNode
second_title: Aspose.3D for Java API Reference
description: Aspose.3Ds supports animation hierarchy each animation can be composed by several animations and animations key-frame definition.
type: docs
weight: 15
url: /java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D's supports animation hierarchy, each animation can be composed by several animations and animation's key-frame definition. com.aspose.threed.AnimationNode defines the transformation of a property value over time, for example, animation node can be used to control a node's transformation or other com.aspose.threed.A3DObject object's numerical properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Initializes a new instance of the com.aspose.threed.AnimationNode class. |
| [AnimationNode()](#AnimationNode--) | Initializes a new instance of the com.aspose.threed.AnimationNode class. |
## Methods

| Method | Description |
| --- | --- |
| [getBindPoints()](#getBindPoints--) | Gets the current property bind points |
| [getSubAnimations()](#getSubAnimations--) | Gets the sub-animation nodes under current animations |
| [findBindPoint(String name)](#findBindPoint-java.lang.String-) | Finds the bind point by name. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Gets the animation bind point on given property. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Gets the keyframe sequence on given property and channel. |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Gets the keyframe sequence on given property. |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Creates a BindPoint based on the property data type. |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Initializes a new instance of the com.aspose.threed.AnimationNode class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Initializes a new instance of the com.aspose.threed.AnimationNode class.

### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Gets the current property bind points

**Returns:**
java.util.List<com.aspose.threed.BindPoint>
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Gets the sub-animation nodes under current animations

**Returns:**
java.util.List<com.aspose.threed.AnimationNode>
### findBindPoint(String name) {#findBindPoint-java.lang.String-}
```
public BindPoint findBindPoint(String name)
```


Finds the bind point by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Bind point's name to find. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Gets the animation bind point on given property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | On which object to create the bind point. |
| propName | java.lang.String | The property's name. |
| create | boolean | If set to \`\`\` true \`\`\` create the bind point if it's not existing. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Gets the keyframe sequence on given property and channel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | On which instance to create the keyframe sequence. |
| propName | java.lang.String | The property's name. |
| channelName | java.lang.String | The channel name. |
| create | boolean | If set to \`\`\` true \`\`\` create the animation sequence if it's not existing. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


Gets the keyframe sequence on given property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | On which instance to create the keyframe sequence. |
| propName | java.lang.String | The property's name. |
| create | boolean | If set to \`\`\` true \`\`\`, create the sequence if it's not existing. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Creates a BindPoint based on the property data type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Object. |
| propName | java.lang.String | Property name. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
