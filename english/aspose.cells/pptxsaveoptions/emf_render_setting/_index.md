﻿---
title: emf_render_setting property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 120
url: /aspose.cells/pptxsaveoptions/emf_render_setting/
is_root: false
---

## emf_render_setting property


Setting for rendering Emf metafile.

### Remarks 


EMF metafiles identified as "EMF+ Dual" can contain both EMF+ records and EMF records. 
Either type of record can be used to render the image, only EMF+ records, or only EMF records.
When [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/aspose.cells/emfrendersetting#EMF_PLUS_PREFER) is set, then EMF+ records will be parsed while rendering to page, otherwise only EMF records will be parsed.
Default value is [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/aspose.cells/emfrendersetting#EMF_ONLY).
### Definition:
```python
@property
def emf_render_setting(self):
    ...
@emf_render_setting.setter
def emf_render_setting(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`EmfRenderSetting`](/cells/python-net/aspose.cells/emfrendersetting)
* class [`PptxSaveOptions`](/cells/python-net/aspose.cells/pptxsaveoptions)
