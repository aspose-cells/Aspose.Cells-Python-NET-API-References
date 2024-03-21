---
title: emf_render_setting عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 110
url: /ar/aspose.cells.rendering/imageorprintoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting عقار

الإعداد لتقديم ملف التعريف Emf.

###  ملاحظات

 يمكن أن تحتوي ملفات التعريف EMF التي تم تحديدها على أنها "EMF+ Dual" على كل من السجلات EMF+ والسجلات EMF.
يمكن استخدام أي نوع من السجلات لعرض الصورة، فقط EMF+ سجلات، أو EMF سجل فقط.
عند تعيين [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/ar/aspose.cells/emfrendersetting#EMF_PLUS_PREFER)، سيتم تحليل السجلات EMF+ أثناء العرض على الصورة، وإلا سيتم تحليل السجلات EMF فقط.
القيمة الافتراضية هي [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/ar/aspose.cells/emfrendersetting#EMF_ONLY).
بالنسبة للأطر التي تعتمد على .Net System.Drawing.Common، يتم تجاهل هذا الإعداد.
###  تعريف:
```python
@property
def emf_render_setting(self):
    ...
@emf_render_setting.setter
def emf_render_setting(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](../../)
* فئة [`EmfRenderSetting`](/cells/python-net/ar/aspose.cells/emfrendersetting)
* فئة [`ImageOrPrintOptions`](/cells/python-net/ar/aspose.cells.rendering/imageorprintoptions)
