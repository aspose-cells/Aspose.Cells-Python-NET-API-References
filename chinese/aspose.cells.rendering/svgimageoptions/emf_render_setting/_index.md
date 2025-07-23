---
title: emf_render_setting属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 130
url: /zh/aspose.cells.rendering/svgimageoptions/emf_render_setting/
is_root: false
---
## emf_render_setting属性

用于在源文件中渲染 Emf 元文件的设置。

### 注意事项

标识为“EMF+ Dual”的 EMF 元文件可以同时包含 EMF+ 记录和 EMF 记录。
两种类型的记录均可用于呈现图像，仅限 EMF+ 记录，或仅限 EMF 记录。
当设置了 [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/zh/aspose.cells/emfrendersetting#EMF_PLUS_PREFER) 时，渲染到图像时将解析 EMF+ 记录，否则将仅解析 EMF 记录。
默认值为 [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/zh/aspose.cells/emfrendersetting#EMF_ONLY)。
对于依赖于 .Net System.Drawing.Common 的框架，此设置将被忽略。
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
* 模块[`aspose.cells.rendering`](../../)
* 类 [`EmfRenderSetting`](/cells/python-net/zh/aspose.cells/emfrendersetting)
* 类 [`SvgImageOptions`](/cells/python-net/zh/aspose.cells.rendering/svgimageoptions)
