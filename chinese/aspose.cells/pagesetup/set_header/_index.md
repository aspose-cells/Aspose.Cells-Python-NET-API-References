---
title: set_header方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 200
url: /zh/aspose.cells/pagesetup/set_header/
is_root: false
---
##  set_header(self, section, header_script) {#int-str}
设置格式化 Excel 文件标题的脚本。



```python

def set_header(self, section, header_script):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| section | int |0：左部分，1：中间部分，2：右部分。|
| header_script | str |标题格式脚本。|
### 注意事项

脚本命令：

|命令|描述|
| :- | :- |
|&P|当前页码|
|&N|页数|
|&D|当前日期|
|&T|当前时间|
| ＆一个|工作表名称|
|&F|不带路径的文件名|
| &"<FontName>"|字体名称，例如：&"Arial"|
| &"<FontName>, <FontStyle>"|字体名称和字体样式，例如：&"Arial,Bold"|
| &<FontSize>|字体大小。如果此命令后跟要在页眉中打印的纯数字，则该数字将与字体高度之间用空格字符分隔。|
| &K<RRGGBB>|字体颜色，例如（RED）：&KFF0000|
| &G|图片脚本|

例如：“&Arial,Bold&8Header Note”


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`PageSetup`](/cells/python-net/zh/aspose.cells/pagesetup)
