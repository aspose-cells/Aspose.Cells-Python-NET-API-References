---
title: VbaProject класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells.vba/vbaproject/
is_root: false
---
##  VbaProject класс
Представляет проект VBA.



Тип VbaProject предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_valid_signed](/cells/python-net/ru/aspose.cells.vba/vbaproject/is_valid_signed) | Указывает, действительна ли подпись проекта VBA.|
| [cert_raw_data](/cells/python-net/ru/aspose.cells.vba/vbaproject/cert_raw_data) | Получает необработанные данные сертификата, если этот проект VBA подписан.|
| [encoding](/cells/python-net/ru/aspose.cells.vba/vbaproject/encoding) |Получает и задает кодировку проекта VBA.|
| [name](/cells/python-net/ru/aspose.cells.vba/vbaproject/name) | Получает и задает имя проекта VBA.|
| [is_signed](/cells/python-net/ru/aspose.cells.vba/vbaproject/is_signed) | Указывает, подписан ли VBAcode.|
| [is_protected](/cells/python-net/ru/aspose.cells.vba/vbaproject/is_protected) | Указывает, защищен ли этот проект VBA.|
| [islocked_for_viewing](/cells/python-net/ru/aspose.cells.vba/vbaproject/islocked_for_viewing) | Указывает, заблокирован ли этот проект VBA для просмотра.|
| [modules](/cells/python-net/ru/aspose.cells.vba/vbaproject/modules) | Получает все [`VbaModule`](/cells/python-net/ru/aspose.cells.vba/vbamodule) объектов.|
| [references](/cells/python-net/ru/aspose.cells.vba/vbaproject/references) | Получает все ссылки проекта VBA.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`sign(self, digital_signature)`](/cells/python-net/ru/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.digitalsignature) | Подпишите этот проект VBA с помощью DigitalSignature|
| [`protect(self, islocked_for_viewing, password)`](/cells/python-net/ru/aspose.cells.vba/vbaproject/protect/#bool-str) | Защищает или снимает защиту этого проекта VBA.|
| [`copy(self, source)`](/cells/python-net/ru/aspose.cells.vba/vbaproject/copy/#aspose.cells.vba.vbaproject) | Скопировать проект VBA из другого файла.|
| [`validate_password(self, password)`](/cells/python-net/ru/aspose.cells.vba/vbaproject/validate_password/#str) | Проверяет пароль защиты.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Смотрите также
* модуль [`aspose.cells.vba`](..)
* класс [`VbaModule`](/cells/python-net/ru/aspose.cells.vba/vbamodule)
