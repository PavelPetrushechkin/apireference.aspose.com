﻿---
title: License class
second_title: Aspose.Words for Python via .NET API Reference
description: "Provides methods to license the component."
type: docs
weight: 610
url: /python-net/aspose.words/license/
---

## License class

Provides methods to license the component.


### Constructors
| Name | Description |
| --- | --- |
| [License()](./__init__/#default) | Initializes a new instance of this class. |

### Methods

| Name | Description |
| --- | --- |
|[ set_license(license_name)](./set_license/#str) | Licenses the component. |
|[ set_license(stream)](./set_license/#bytesio) | Licenses the component. |

### Examples

Shows how initialize a license for Aspose.Words using a license file in the local file system.

```python
# Set the license for our Aspose.Words product by passing the local file system filename of a valid license file.
license = aw.License()
license.set_license(LICENSE_PATH)
```

### See Also

* module [aspose.words](../)

