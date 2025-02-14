---
title: LoadingStreamBehavior
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 9570
url: /python-net/aspose.slides/loadingstreambehavior/
---

## LoadingStreamBehavior enumeration

The stream passed to a method is considered as a Binary Large Object (BLOB) (see <br/>            [IBlobManagementOptions](/slides/python-net/aspose.slides/iblobmanagementoptions/) description). Values of this enumeration identify how <br/>            the stream should be treated when it passed to the method. Depending on the <br/>            requirements, different decisions could be made to provide the most efficient behavior.

## Members
| Member name | Description |
| :- | :- |
|READ_STREAM_AND_RELEASE|The stream will be read to the end and then released - i.e. it will be guaranteed that this stream <br/>            will not be used by [IPresentation](/slides/python-net/aspose.slides/ipresentation/) instance in the future. It can be closed by the client <br/>            code or used in any other way.|
|KEEP_LOCKED|The stream will be locked inside the [IPresentation](/slides/python-net/aspose.slides/ipresentation/) object, i.e. the ownership of <br/>            the stream will be transferred. The [IPresentation](/slides/python-net/aspose.slides/ipresentation/) object will be responsible to <br/>            correctly dispose the stream when this object will be disposed itself. <br/>            This behavior is extremely useful when you need to serialize a large BLOB file (such as a large <br/>            video or audio -see [IBlobManagementOptions](/slides/python-net/aspose.slides/iblobmanagementoptions/) description) and want to prevent loading <br/>            this file into memory or other performance issues. You may just open the stream <br/>            for this file and pass to a method, choosing [KEEP_LOCKED](/slides/python-net/aspose.slides/loadingstreambehavior/) LoadingStreamBehavior.|

### See Also

* namespace [aspose.slides](/slides/python-net/aspose.slides/)
* assembly [Aspose.Slides](/slides/python-net/)

