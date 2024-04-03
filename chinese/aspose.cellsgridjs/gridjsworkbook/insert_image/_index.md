---
title: insert_image方法
second_title: Aspose.Cells.GridJs for Python via .NET API 参考文献
description:
type: docs
weight: 130
url: /zh/aspose.cellsgridjs/gridjsworkbook/insert_image/
is_root: false
---
##  insert_image {#str-str-io.RawIOBase-str}

从文件流或 URL 插入工作表中的图像（应提供文件流或 URL）
或者
当 p.type 是 AutoShapeType 之一时插入形状


### 返回


插入图片的JSON格式字符串


```python
def insert_image(self, uid, p, s, image_url):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| uid | str |文件缓存的唯一 ID|
| p | str |JSON 操作的格式字符串，指定单元格位置、工作表名称、图像的左上行、左上列等 {name:'sheet1',ri:1,ci:1} |
| s | io.RawIOBase |图像文件的文件流|
| image_url | str |图像文件的 URL|



### 也可以看看
* 模块[`aspose.cellsgridjs`](../../)
* 类 [`GridJsWorkbook`](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook)
