﻿---
title: language_id property
second_title: Aspose.Words for Python via .NET API Reference
description: "Gets or sets the language ID used to format the address."
type: docs
weight: 50
url: /python-net/aspose.words.fields/fieldaddressblock/language_id/
---

## FieldAddressBlock.language_id property

Gets or sets the language ID used to format the address.


### Examples

Shows how to insert an ADDRESSBLOCK field.

```python
doc = aw.Document()
builder = aw.DocumentBuilder(doc)

field = builder.insert_field(aw.fields.FieldType.FIELD_ADDRESS_BLOCK, True).as_field_address_block()

self.assertEqual(" ADDRESSBLOCK ", field.get_field_code())

# Setting this to "2" will include all countries and regions,
# unless it is the one specified in the "excluded_country_or_region_name" property.
field.include_country_or_region_name = "2"
field.format_address_on_country_or_region = True
field.excluded_country_or_region_name = "United States"
field.name_and_address_format = "<Title> <Forename> <Surname> <Address Line 1> <Region> <Postcode> <Country>"

# By default, this property will contain the language ID of the first character of the document.
# We can set a different culture for the field to format the result with like this.
field.language_id = "1033" # en-US

self.assertEqual(
    " ADDRESSBLOCK  \\c 2 \\d \\e \"United States\" \\f \"<Title> <Forename> <Surname> <Address Line 1> <Region> <Postcode> <Country>\" \\l 1033",
    field.get_field_code())
```

### See Also

* module [aspose.words.fields](../../)
* class [FieldAddressBlock](../)

