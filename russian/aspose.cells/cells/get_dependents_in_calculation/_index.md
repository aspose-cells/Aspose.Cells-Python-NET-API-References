---
title: get_dependents_in_calculation метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 400
url: /ru/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, row, column, recursive) {#int-int-bool}
Получает все ячейки, вычисленный результат которых зависит от определенной ячейки.


###  Возврат

Перечислитель для перечисления всех зависимых объектов (Cell объектов)


```python

def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | Индекс строки конкретной ячейки|
| column | int |Индекс столбца конкретной ячейки.|
| recursive | bool | Возвращает ли те зависимые элементы, которые не ссылаются напрямую на конкретную ячейку<br/> но ссылка на другие листы этой ячейки.|
###  Примечания

Чтобы использовать этот метод, убедитесь, что для рабочей книги установлено значение true
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/ru/aspose.cells/formulasettings#enable_calculation_chain) и был полностью рассчитан с этой настройкой.
Если на эту ячейку не ссылается формула, будет возвращено значение null.
Более подробную информацию и примеры можно найти по телефону [`Cell.get_dependents_in_calculation`](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation).


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
