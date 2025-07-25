---
title: VbaModule класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 10
url: /ru/aspose.cells.vba/vbamodule/
is_root: false
---
##  VbaModule класс
Представляет модуль в проекте VBA.



Тип VbaModule предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [name](/cells/python-net/ru/aspose.cells.vba/vbamodule/name) | Получает и задает имя модуля.|
| [type](/cells/python-net/ru/aspose.cells.vba/vbamodule/type) | Получает тип модуля.|
| [binary_codes](/cells/python-net/ru/aspose.cells.vba/vbamodule/binary_codes) | Получает и задает двоичные коды модуля.|
| [codes](/cells/python-net/ru/aspose.cells.vba/vbamodule/codes) | Получает и задает коды модуля.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
index = vbaProject.modules.add(VbaModuleType.CLASS, "test")
#  Get vba module
vbaModule = vbaProject.modules[index]
#  Set codes
vbaModule.codes = "Sub ShowMessage()\r\nMsgBox \"Welcome to Aspose!\"\r\nEnd Sub"
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Смотрите также
* модуль [`aspose.cells.vba`](..)
