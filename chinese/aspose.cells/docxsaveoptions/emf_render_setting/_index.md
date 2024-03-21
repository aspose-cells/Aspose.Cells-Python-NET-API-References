---
title: emf_render_setting属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells/docxsaveoptions/emf_render_setting/
is_root: false
---
## emf_render_setting属性

用于渲染 Emf 图元文件的设置。

### 评论

标识为“EMF+ Dual”的 EMF 图元文件可以包含 EMF+ 记录和 EMF 记录。
任一类型的记录都可用于渲染图像，只能使用 EMF+ 条记录，或者只能使用 EMF 条记录。
当设置 [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/zh/aspose.cells/emfrendersetting#EMF_PLUS_PREFER) 时，渲染到页面时将解析 EMF+ 条记录，否则仅解析 EMF 条记录。
默认值为 [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/zh/aspose.cells/emfrendersetting#EMF_ONLY)。
### 定义：
```python
@property
def emf_render_setting(self):
    ...
@emf_render_setting.setter
def emf_render_setting(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`DocxSaveOptions`](/cells/python-net/zh/aspose.cells/docxsaveoptions)
* 类 [`EmfRenderSetting`](/cells/python-net/zh/aspose.cells/emfrendersetting)
