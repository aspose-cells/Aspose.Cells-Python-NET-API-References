---
title: get_enumerator метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 100
url: /ru/aspose.cells/range/get_enumerator/
is_root: false
---
##  get_enumerator {#}
Получает перечислитель для ячеек в этом диапазоне.


###  Возврат

Перечислитель ячеек


```python
def get_enumerator(self):
    ...
```


###  Примечания

При обходе элементов возвращаемым Enumerator коллекция ячеек
не следует изменять (например, операции, которые приведут к созданию нового экземпляра Cell/Row или удалению существующего Cell/Row).
В противном случае перечислитель не сможет правильно пройти все ячейки (некоторые элементы могут проходиться повторно или пропускаться).
###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook("template.xlsx")
cells = workbook.worksheets[0].cells
en = cells.create_range("B2:C3").get_enumerator()
for cell in en:
    print(cell.name + ": "  + str(cell.value))

```



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Range`](/cells/python-net/ru/aspose.cells/range)
