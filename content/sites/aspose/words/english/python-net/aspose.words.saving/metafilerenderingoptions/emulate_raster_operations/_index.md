﻿---
title: emulate_raster_operations property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets a value determining whether or not the raster operations should be emulated."
type: docs
weight: 30
url: /python-net/aspose.words.saving/metafilerenderingoptions/emulate_raster_operations/
---

## MetafileRenderingOptions.emulate_raster_operations property

Gets or sets a value determining whether or not the raster operations should be emulated.

Specific raster operations could be used in metafiles. They can not be rendered directly to vector graphics.
Emulating raster operations requires partial rasterization of the resulting vector graphics which may affect the 
metafile rendering performance.

When this value is set to ``true``, Aspose.Words emulates the raster operations. The resulting output maybe 
partially rasterized and performance might be slower.

When this value is set to ``false``, Aspose.Words does not emulate the raster operations. When Aspose.Words 
encounters a raster operation in a metafile it fallbacks to rendering the metafile into a bitmap by using the 
operating system.

This option is used only when metafile is rendered as vector graphics.

The default value is ``true``.




### See Also

* module [aspose.words.saving](../../)
* class [MetafileRenderingOptions](../)

