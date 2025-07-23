---
title: add_signature_line метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 310
url: /ru/aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---
##  add_signature_line(self, upper_left_row, upper_left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}
Добавляет строку подписи на рабочий лист.


###  Возврат




```python

def add_signature_line(self, upper_left_row, upper_left_column, signature_line):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| signature_line | [`SignatureLine`](/cells/python-net/ru/aspose.cells.drawing/signatureline) | Представляет объект строки подписи.|

###  Пример

```python
from aspose.cells.drawing import SignatureLine

wSignatureLine = SignatureLine()
wSignatureLine.allow_comments = True
wSignatureLine.email = "example@example.com"
wSignatureLine.instructions = "Sign to confirm the excel content."
wSignatureLine.is_line = True
wSignatureLine.show_signed_date = True
wSignatureLine.signer = "User"
wSignatureLine.title = "tester"
# wSignatureLine.SignatureLineType = SignatureType.Stamp;
signatureLine1 = shapes.add_signature_line(0, 0, wSignatureLine)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
