---
title: TextureData
second_title: Aspose.3D for Java API Reference
description: This class contains the raw data and format definition of a texture.
type: docs
weight: 167
url: /java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object
```
public class TextureData
```

This class contains the raw data and format definition of a texture.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, int pixelFormat, byte[] data)](#TextureData-int-int-int-int-int-byte---) | Constructor of com.aspose.threed.TextureData |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | Constructor of com.aspose.threed.TextureData |
| [TextureData()](#TextureData--) | Constructor of com.aspose.threed.TextureData |
## Methods

| Method | Description |
| --- | --- |
| [getData()](#getData--) | Raw bytes of pixel data |
| [getWidth()](#getWidth--) | Number of horizontal pixels |
| [getHeight()](#getHeight--) | Number of vertical pixels |
| [getStride()](#getStride--) | Number of bytes of a scanline. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Number of bytes of a pixel |
| [getPixelFormat()](#getPixelFormat--) | The pixel's format |
| [fromBitmap(BufferedImage bitmap)](#fromBitmap-java.awt.image.BufferedImage-) | Convert a java.awt.image.BufferedImage to com.aspose.threed.TextureData |
| [toBitmap()](#toBitmap--) | Convert the TextureData to a java.awt.image.BufferedImage instance. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Load a texture from stream |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Load a texture from file |
### TextureData(int width, int height, int stride, int bytesPerPixel, int pixelFormat, byte[] data) {#TextureData-int-int-int-int-int-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, int pixelFormat, byte[] data)
```


Constructor of com.aspose.threed.TextureData

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |
| height | int |  |
| stride | int |  |
| bytesPerPixel | int |  |
| pixelFormat | int |  |
| data | byte[] |  |

### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


Constructor of com.aspose.threed.TextureData

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |
| height | int |  |
| stride | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| data | byte[] |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


Constructor of com.aspose.threed.TextureData

### getData() {#getData--}
```
public byte[] getData()
```


Raw bytes of pixel data

**Returns:**
byte[]
### getWidth() {#getWidth--}
```
public int getWidth()
```


Number of horizontal pixels

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Number of vertical pixels

**Returns:**
int
### getStride() {#getStride--}
```
public int getStride()
```


Number of bytes of a scanline.

**Returns:**
int
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


Number of bytes of a pixel

**Returns:**
int
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


The pixel's format

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat)
### fromBitmap(BufferedImage bitmap) {#fromBitmap-java.awt.image.BufferedImage-}
```
public static TextureData fromBitmap(BufferedImage bitmap)
```


Convert a java.awt.image.BufferedImage to com.aspose.threed.TextureData

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | java.awt.image.BufferedImage |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Convert the TextureData to a java.awt.image.BufferedImage instance.

**Returns:**
java.awt.image.BufferedImage
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


Load a texture from stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.threed.Stream |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


Load a texture from file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
