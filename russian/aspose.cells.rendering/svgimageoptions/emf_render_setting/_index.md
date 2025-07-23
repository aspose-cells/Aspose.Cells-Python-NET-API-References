---
title: emf_render_setting недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 130
url: /ru/aspose.cells.rendering/svgimageoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting недвижимость

Настройка для рендеринга метафайлов Emf в исходном файле.

###  Примечания

 Метафайлы EMF, идентифицированные как «EMF+ Dual», могут содержать как записи EMF+, так и записи EMF.
Для визуализации изображения можно использовать любой тип записи: только записи EMF+ или только записи EMF.
Если установлено значение [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/ru/aspose.cells/emfrendersetting#EMF_PLUS_PREFER), то при рендеринге изображения будет проанализировано EMF+ записей, в противном случае будет проанализировано только EMF записей.
Значение по умолчанию — [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/ru/aspose.cells/emfrendersetting#EMF_ONLY).
Для фреймворков, зависящих от .Net System.Drawing.Common, этот параметр игнорируется.
###  Определение:
```python
@property
def emf_render_setting(self):
    ...
@emf_render_setting.setter
def emf_render_setting(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.rendering`](../../)
* класс [`EmfRenderSetting`](/cells/python-net/ru/aspose.cells/emfrendersetting)
* класс [`SvgImageOptions`](/cells/python-net/ru/aspose.cells.rendering/svgimageoptions)
