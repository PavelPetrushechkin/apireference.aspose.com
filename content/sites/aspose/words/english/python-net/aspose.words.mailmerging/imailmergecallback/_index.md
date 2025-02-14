﻿---
title: IMailMergeCallback class
second_title: Aspose.Words for Python via .NET API Reference
description: "Implement this interface if you want to receive notifications while mail merge is performed."
type: docs
weight: 40
url: /python-net/aspose.words.mailmerging/imailmergecallback/
---

## IMailMergeCallback class

Implement this interface if you want to receive notifications while mail merge is performed.


### Methods

| Name | Description |
| --- | --- |
|[ tags_replaced()](./tags_replaced/#default) | Called when "mustache" text tags are replaced with MERGEFIELD fields. |

### Examples

Shows how to define custom logic for handling events during mail merge.

```python
def test_callback(self):

    doc = aw.Document()
    builder = aw.DocumentBuilder(doc)

    # Insert two mail merge tags referencing two columns in a data source.
    builder.write("{{FirstName}}")
    builder.write("{{LastName}}")

    # Create a data source that only contains one of the columns that our merge tags reference.
    table = DataTable("Test")
    table.columns.add("FirstName")
    table.rows.add("John")
    table.rows.add("Jane")

    # Configure our mail merge to use alternative mail merge tags.
    doc.mail_merge.use_non_merge_fields = True

    # Then, ensure that the mail merge will convert tags, such as our "LastName" tag,
    # into MERGEFIELDs in the merge documents.
    doc.mail_merge.preserve_unused_tags = False

    counter = ExMailMerge.MailMergeTagReplacementCounter()
    doc.mail_merge.mail_merge_callback = counter
    doc.mail_merge.execute(table)

    self.assertEqual(1, counter.tags_replaced_count)

class MailMergeTagReplacementCounter(aw.mailmerging.IMailMergeCallback):
    """Counts the number of times a mail merge replaces mail merge tags that it could not fill with data with MERGEFIELDs."""

    def __init__(self):
        self.tags_replaced_count = 0

    def test_tags_replaced(self):

        self.tags_replaced_count += 1
```

### See Also

* module [aspose.words.mailmerging](../)

