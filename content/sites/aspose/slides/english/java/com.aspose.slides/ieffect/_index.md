---
title: IEffect
second_title: Aspose.Slides for Java API Reference
description:  Represents animation effect.
type: docs
weight: 747
url: /java/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Represents animation effect.
## Methods

| Method | Description |
| --- | --- |
| [getSequence()](#getSequence--) | Returns a sequence for an effect. |
| [getTextAnimation()](#getTextAnimation--) | Returns text animation. |
| [getPresetClassType()](#getPresetClassType--) | Defines class of effect. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Defines class of effect. |
| [getType()](#getType--) | Defines type of effect. |
| [setType(int value)](#setType-int-) | Defines type of effect. |
| [getSubtype()](#getSubtype--) | Defines subtype of effect. |
| [setSubtype(int value)](#setSubtype-int-) | Defines subtype of effect. |
| [getBehaviors()](#getBehaviors--) | Returns collection of behavior for effect. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Returns collection of behavior for effect. |
| [getTiming()](#getTiming--) | Defines timing value for effect. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Defines timing value for effect. |
| [getTargetShape()](#getTargetShape--) | Returns target shape for effect. |
| [getSound()](#getSound--) | Defined embedded sound for effect. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Defined embedded sound for effect. |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Returns a sequence for an effect. Read-only [ISequence](../../com.aspose.slides/isequence).

**Returns:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Returns text animation. Read-only [ITextAnimation](../../com.aspose.slides/itextanimation).

**Returns:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Defines class of effect. Read/write [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Returns:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Defines class of effect. Read/write [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


Defines type of effect. Read/write [EffectType](../../com.aspose.slides/effecttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Defines type of effect. Read/write [EffectType](../../com.aspose.slides/effecttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Defines subtype of effect. Read/write [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Returns:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Defines subtype of effect. Read/write [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Returns collection of behavior for effect. Read/write [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Returns:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Returns collection of behavior for effect. Read/write [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Defines timing value for effect. Read/write [ITiming](../../com.aspose.slides/itiming).

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Defines timing value for effect. Read/write [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Returns target shape for effect. Read-only [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Defined embedded sound for effect. Read/write [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Defined embedded sound for effect. Read/write [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

