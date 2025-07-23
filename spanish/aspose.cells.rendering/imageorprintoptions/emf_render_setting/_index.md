---
title: emf_render_setting propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 110
url: /es/aspose.cells.rendering/imageorprintoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting propiedad

Configuración para representar metarchivos Emf en el archivo de origen.

###  Observaciones

 Los metarchivos EMF identificados como "EMF+ Dual" pueden contener registros EMF+ y EMF.
Se puede usar cualquier tipo de registro para renderizar la imagen, solo EMF+ registros o solo EMF registros.
Cuando se establece [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/es/aspose.cells/emfrendersetting#EMF_PLUS_PREFER), se analizarán EMF+ registros durante la representación en imagen; de lo contrario, solo se analizarán EMF registros.
El valor predeterminado es [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/es/aspose.cells/emfrendersetting#EMF_ONLY).
Para los marcos que dependen de .Net System.Drawing.Common, esta configuración se ignora.
###  Definición:
```python
@property
def emf_render_setting(self):
    ...
@emf_render_setting.setter
def emf_render_setting(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.rendering`](../../)
* clase [`EmfRenderSetting`](/cells/python-net/es/aspose.cells/emfrendersetting)
* clase [`ImageOrPrintOptions`](/cells/python-net/es/aspose.cells.rendering/imageorprintoptions)
