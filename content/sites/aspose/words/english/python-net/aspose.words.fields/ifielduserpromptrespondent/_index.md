﻿---
title: IFieldUserPromptRespondent class
second_title: Aspose.Words for Python via .NET API Reference
description: "Represents the respondent to user prompts during field update."
type: docs
weight: 1250
url: /python-net/aspose.words.fields/ifielduserpromptrespondent/
---

## IFieldUserPromptRespondent class

Represents the respondent to user prompts during field update.


The ASK and FILLIN fields are the examples of fields that prompt the user for some response. Implement this interface
and assign it to the [FieldOptions.user_prompt_respondent](../fieldoptions/user_prompt_respondent/) property to establish interaction between field update
and the user.



### Methods

| Name | Description |
| --- | --- |
|[ respond(prompt_text, default_response)](./respond/#str_str) | When implemented, returns a response from the user on prompting. Your implementation should return **null** to indicate that the user has not responded to the prompt (i.e. the user has pressed the Cancel button in the prompt window). |

### See Also

* module [aspose.words.fields](../)

