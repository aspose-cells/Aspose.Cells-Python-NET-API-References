---
title: emf_render_setting недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 130
url: /ru/aspose.cells/pptxsaveoptions/emf_render_setting/
is_root: false
---
##  emf_render_setting недвижимость

Настройка рендеринга метафайла Emf.

###  Примечания

 Метафайлы EMF, идентифицированные как «EMF+ Dual», могут содержать как записи EMF+, так и записи EMF.
Для рендеринга изображения можно использовать записи любого типа: только записи EMF+ или только записи EMF.
Если установлено [`EmfRenderSetting.EMF_PLUS_PREFER`](/cells/python-net/ru/aspose.cells/emfrendersetting#EMF_PLUS_PREFER), то при рендеринге на страницу будет анализироваться EMF+ записей, в противном случае будет анализироваться только EMF записей.
Значение по умолчанию — [`EmfRenderSetting.EMF_ONLY`](/cells/python-net/ru/aspose.cells/emfrendersetting#EMF_ONLY).
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
* модуль [`aspose.cells`](../../)
* класс [`EmfRenderSetting`](/cells/python-net/ru/aspose.cells/emfrendersetting)
* класс [`PptxSaveOptions`](/cells/python-net/ru/aspose.cells/pptxsaveoptions)
