---
title: get_dependents_in_calculation метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 100
url: /ru/aspose.cells/cell/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, recursive) {#bool}
Получает все ячейки, вычисленный результат которых зависит от этой ячейки.


###  Возврат

Перечислитель для перечисления всех зависимых объектов (Cell объектов)


```python

def get_dependents_in_calculation(self, recursive):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| recursive | bool | Возвращает ли те зависимые элементы, которые не ссылаются на эту ячейку напрямую<br/> но ссылка на другие листы этой ячейки|
###  Примечания

Чтобы использовать этот метод, убедитесь, что для рабочей книги установлено значение true
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/ru/aspose.cells/formulasettings#enable_calculation_chain) и был полностью рассчитан с этой настройкой.
Если на эту ячейку не ссылается формула, будет возвращено значение null.
###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("B1").get_dependents_in_calculation(False)
print("B1's calculation dependents:")
for c in en:
    print(c.name)
en = cells.get("B2").get_dependents_in_calculation(False)
print("B2's calculation dependents:")
for c in en:
    print(c.name)

```



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
