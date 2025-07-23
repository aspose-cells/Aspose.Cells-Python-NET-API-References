---
title: SignatureLine класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 610
url: /ru/aspose.cells.drawing/signatureline/
is_root: false
---
##  SignatureLine класс
Представляет строку подписи.



Тип SignatureLine предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells.drawing/signatureline/__init__/#) | Создает новый экземпляр SignatureLine|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [id](/cells/python-net/ru/aspose.cells.drawing/signatureline/id) | Получает или задает идентификатор для этой строки подписи.|
| [provider_id](/cells/python-net/ru/aspose.cells.drawing/signatureline/provider_id) | Получает или задает идентификатор поставщика подписи.|
| [signer](/cells/python-net/ru/aspose.cells.drawing/signatureline/signer) | Получает или задает подписчика.|
| [title](/cells/python-net/ru/aspose.cells.drawing/signatureline/title) | Получает или задает имя певца.|
| [email](/cells/python-net/ru/aspose.cells.drawing/signatureline/email) | Получает или задает адрес электронной почты певца.|
| [is_line](/cells/python-net/ru/aspose.cells.drawing/signatureline/is_line) | Указывает, является ли это строкой подписи.|
| [allow_comments](/cells/python-net/ru/aspose.cells.drawing/signatureline/allow_comments) | Указывает, можно ли прикреплять комментарии.|
| [show_signed_date](/cells/python-net/ru/aspose.cells.drawing/signatureline/show_signed_date) | Указывает, следует ли показывать дату подписания.|
| [instructions](/cells/python-net/ru/aspose.cells.drawing/signatureline/instructions) | Получает или задает текст, отображаемый пользователю во время подписания.|
| [signature_line_type](/cells/python-net/ru/aspose.cells.drawing/signatureline/signature_line_type) | Получает или задает тип подписи.<br/>По умолчанию — если установлено значение по умолчанию, соответствующее значение ProviderId фиксируется на уровне {0000000000-0000-0000-0000-0000000000}.<br/>Stamp — если значение равно Stamp, соответствующее значение ProviderId обычно равно {000CD6A4-0000-0000-C000-000000000046}.<br/> Пользовательский. Если установлено значение «Пользовательский», соответствующее значение ProviderId обычно должно быть задано пользователем. Его следует получить из документации, поставляемой с поставщиком.|



###  Пример

```python
from aspose.cells import Workbook
from aspose.cells.drawing import SignatureLine

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
#  Create signature line object
s = SignatureLine()
s.signer = "Simon"
s.title = "Development"
s.email = "simon@aspose.com"
s.instructions = "Sign to confirm the excel content."
#  Adds a Signature Line to the worksheet.
signatureLine = worksheet.shapes.add_signature_line(0, 0, s)
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Смотрите также
* модуль [`aspose.cells.drawing`](..)
