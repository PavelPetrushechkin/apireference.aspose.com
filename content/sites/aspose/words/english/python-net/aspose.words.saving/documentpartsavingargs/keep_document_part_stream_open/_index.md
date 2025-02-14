﻿---
title: keep_document_part_stream_open property
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies whether Aspose.Words should keep the stream open or close it after saving a document part."
type: docs
weight: 40
url: /python-net/aspose.words.saving/documentpartsavingargs/keep_document_part_stream_open/
---

## DocumentPartSavingArgs.keep_document_part_stream_open property

Specifies whether Aspose.Words should keep the stream open or close it after saving a document part.

Default is ``false`` and Aspose.Words will close the stream you provided
in the [DocumentPartSavingArgs.document_part_stream](../document_part_stream/) property after writing a document part into it.
Specify ``true`` to keep the stream open. Please note that the main output stream 
provided in the call to [Document.save()](../../../aspose.words/document/save/#bytesio_saveformat) or 
[Document.save()](../../../aspose.words/document/save/#bytesio_saveoptions) will never be closed by Aspose.Words 
even if [DocumentPartSavingArgs.keep_document_part_stream_open](./) is set to ``false``.




### See Also

* module [aspose.words.saving](../../)
* class [DocumentPartSavingArgs](../)
* property [DocumentPartSavingArgs.document_part_stream](../document_part_stream/)

