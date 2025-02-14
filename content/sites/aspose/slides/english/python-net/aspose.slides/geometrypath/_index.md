---
title: GeometryPath
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 620
url: /python-net/aspose.slides/geometrypath/
---

## GeometryPath class

Represents geometry path of GeometryShape

The GeometryPath type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|GeometryPath()|Creates instance of GeometryPath|
## Properties
| Name | Description |
| :- | :- |
|path_data|Returns geometry path of GeometryShape as an array of path segments.|
|fill_mode|Sets fill mode|
|stroke|Sets stroke appearance|
## Methods
| Name | Description |
| :- | :- |
|line_to(point)|Adds line to the end of the path|
|line_to(x, y)|Adds line to the end of the path|
|line_to(point, index)|Adds line to the specified place of the path|
|line_to(x, y, index)|Adds line to the specified place of the path|
|cubic_bezier_to(point1, point2, point3)|Adds cubic Bezier curve at the end the path|
|cubic_bezier_to(x1, y1, x2, y2, x3, y3)|Adds cubic Bezier curve at the end the path|
|cubic_bezier_to(point1, point2, point3, index)|Adds cubic Bezier curve to the specified place of the path|
|cubic_bezier_to(x1, y1, x2, y2, x3, y3, index)|Adds cubic Bezier curve to the specified place of the path|
|quadratic_bezier_to(point1, point2)|Adds quadratic Bezier curve at the end the path|
|quadratic_bezier_to(x1, y1, x2, y2)|Adds quadratic Bezier curve at the end the path|
|quadratic_bezier_to(point1, point2, index)|Adds quadratic Bezier curve to the specified place of the path|
|quadratic_bezier_to(x1, y1, x2, y2, index)|Adds quadratic Bezier curve to the specified place of the path|
|move_to(point)|Sets next point position.|
|move_to(x, y)|Sets next point position.|
|remove_at(index)|Removes segment at the specified index of the geometry path.|
|close_figure()|Closes the current figure of this path|
|arc_to(width, heigth, start_angle, sweep_angle)|Appends the specified arc to the path.|

### See Also

* namespace [aspose.slides](/slides/python-net/aspose.slides/)
* assembly [Aspose.Slides](/slides/python-net/)

