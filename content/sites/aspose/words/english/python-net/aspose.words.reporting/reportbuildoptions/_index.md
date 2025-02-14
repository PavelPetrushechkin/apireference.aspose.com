﻿---
title: ReportBuildOptions enumeration
second_title: Aspose.Words for Python via .NET API Reference
description: "Specifies options controlling behavior of [ReportingEngine](../reportingengine/) while building a report."
type: docs
weight: 70
url: /python-net/aspose.words.reporting/reportbuildoptions/
---

## ReportBuildOptions enumeration

Specifies options controlling behavior of [ReportingEngine](../reportingengine/) while building a report.



### Members

| Name | Description |
| --- | --- |
| NONE | Specifies default options. |
| ALLOW_MISSING_MEMBERS | Specifies that missing object members should be treated as null literals by the engine. This option  affects only access to instance (that is, non-static) object members and extension methods. If this  option is not set, the engine throws an exception when encounters a missing object member. |
| REMOVE_EMPTY_PARAGRAPHS | Specifies that the engine should remove paragraphs becoming empty after template syntax tags are  removed or replaced with empty values. |
| INLINE_ERROR_MESSAGES | Specifies that the engine should inline template syntax error messages into output documents.  If this option is not set, the engine throws an exception when encounters a syntax error. |
| USE_LEGACY_HEADER_FOOTER_VISITING | Specifies that the engine should visit section child nodes (headers, footers, bodies) in an order compatible with Aspose.Words versions prior 21.9. |
| RESPECT_JPEG_EXIF_ORIENTATION | Specifies that the engine should use EXIF ​​image orientation values to appropriately rotate inserted JPEG images. |

### See Also

* module [aspose.words.reporting](../)

