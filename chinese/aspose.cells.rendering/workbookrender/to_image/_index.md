---
title: to_image方法
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 40
url: /zh/aspose.cells.rendering/workbookrender/to_image/
is_root: false
---
##  to_image(stream) {#io.RawIOBase}
将整个工作簿渲染为 Tiff Image 以流式传输。



```python
def to_image(self, stream):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| stream | io.RawIOBase |输出图像流|


##  to_image(filename) {#str}
将整个工作簿作为 Tiff 图像呈现到文件中。



```python
def to_image(self, filename):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| filename | str |输出图像的文件名|


##  to_image(page_index, file_name) {#int-str}
将特定页面渲染到文件中。



```python
def to_image(self, page_index, file_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| page_index | int |指示要转换的页面|
| file_name | str |输出图像的文件名|


##  to_image(page_index, stream) {#int-io.RawIOBase}
将特定页面渲染到流中。



```python
def to_image(self, page_index, stream):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| page_index | int |指示要转换的页面|
| stream | io.RawIOBase |输出图像流|



### 也可以看看
* 模块 [aspose.cells.rendering](../../)
* 类 [WorkbookRender](/cells/python-net/zh/aspose.cells.rendering/workbookrender)
