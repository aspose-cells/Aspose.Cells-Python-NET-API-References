---
title: VbaProjectReference класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells.vba/vbaprojectreference/
is_root: false
---
##  VbaProjectReference класс
Представляет собой ссылку на проект VBA.



Тип VbaProjectReference предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [type](/cells/python-net/ru/aspose.cells.vba/vbaprojectreference/type) |Получает тип этой ссылки.|
| [name](/cells/python-net/ru/aspose.cells.vba/vbaprojectreference/name) | Получает и задает имя ссылки.|
| [libid](/cells/python-net/ru/aspose.cells.vba/vbaprojectreference/libid) | Получает и задает Libid ссылки.|
| [twiddledlibid](/cells/python-net/ru/aspose.cells.vba/vbaprojectreference/twiddledlibid) | Получает и задает измененный Libid ссылки.|
| [extended_libid](/cells/python-net/ru/aspose.cells.vba/vbaprojectreference/extended_libid) | Получает и задает расширенный Libid ссылки.|
| [relative_libid](/cells/python-net/ru/aspose.cells.vba/vbaprojectreference/relative_libid) | Получает и задает идентификатор указанного проекта VBA с относительным путем.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/ru/aspose.cells.vba/vbaprojectreference/copy/#aspose.cells.vba.vbaprojectreference) |  |



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add vba project reference
vbaProject.references.add_registered_reference("stdole", "*\\G{00020430-0000-0000-C000-000000000046}#2.0#0#C:\\Windows\\system32\\stdole2.tlb#OLE Automation")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Смотрите также
* модуль [`aspose.cells.vba`](..)
