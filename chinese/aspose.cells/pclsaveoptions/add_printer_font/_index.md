---
title: add_printer_font方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/pclsaveoptions/add_printer_font/
is_root: false
---
##  add_printer_font(self, font_full_name, font_pcl_name) {#str-str}
添加有关制造商已添加到打印机的字体的信息。



```python

def add_printer_font(self, font_full_name, font_pcl_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| font_full_name | str |源文件中使用的字体的全名（例如“Times New Roman Bold Italic”）。|
| font_pcl_name | str |输出 Pcl 文档中将使用的字体的名称。|
### 注意事项

根据 Pcl 规范，任何打印机中都要内置 52 种字体。
然而制造商可以在他们的设备中添加一些其他字体。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`PclSaveOptions`](/cells/python-net/zh/aspose.cells/pclsaveoptions)
