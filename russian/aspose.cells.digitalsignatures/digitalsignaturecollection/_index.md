---
title: DigitalSignatureCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.digitalsignatures/digitalsignaturecollection/
is_root: false
---
##  DigitalSignatureCollection класс
Предоставляет коллекцию цифровых подписей, прикрепленных к документу.



Тип DigitalSignatureCollection предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignaturecollection/__init__/#) | Конструктор DigitalSignatureCollection.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add(self, digital_signature)`](/cells/python-net/ru/aspose.cells.digitalsignatures/digitalsignaturecollection/add/#aspose.cells.digitalsignatures.digitalsignature) | Добавьте одну подпись в DigitalSignatureCollection.|



###  Пример

В следующем примере показано, как проверить цифровую подпись.

```python
from aspose.cells import Workbook

# workbook from a signed source file
signedWorkbook = Workbook(r"signedFile.xlsx")
# wb.IsDigitallySigned is true when the workbook is signed already.
print(signedWorkbook.is_digitally_signed)
# get digitalSignature collection from workbook
existingDsc = signedWorkbook.get_digital_signature()
for existingDs in existingDsc:
    print(existingDs.comments)
    print(existingDs.sign_time)
    print(existingDs.is_valid)

```

###  Смотрите также
* модуль [`aspose.cells.digitalsignatures`](..)
