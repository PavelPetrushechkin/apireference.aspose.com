﻿---
title: remove_all_replies method
second_title: Aspose.Words for Python via .NET API Reference
description: "Removes all replies to this comment."
type: docs
weight: 130
url: /python-net/aspose.words/comment/remove_all_replies/
---

## remove_all_replies() {#default}

Removes all replies to this comment.


```python
def remove_all_replies(self):
    ...
```

All constituent nodes of the replies will be deleted from the document.


### Examples

Shows how to remove comment replies.

```python
doc = aw.Document()

comment = aw.Comment(doc, "John Doe", "J.D.", datetime.now())
comment.set_text("My comment.")

doc.first_section.body.first_paragraph.append_child(comment)

comment.add_reply("Joe Bloggs", "J.B.", datetime.now(), "New reply")
comment.add_reply("Joe Bloggs", "J.B.", datetime.now(), "Another reply")

self.assertEqual(2, comment.replies.count)

# Below are two ways of removing replies from a comment.
# 1 -  Use the "remove_reply" method to remove replies from a comment individually:
comment.remove_reply(comment.replies[0])

self.assertEqual(1, comment.replies.count)

# 2 -  Use the "remove_all_replies" method to remove all replies from a comment at once:
comment.remove_all_replies()

self.assertEqual(0, comment.replies.count)
```

### See Also

* module [aspose.words](../../)
* class [Comment](../)

