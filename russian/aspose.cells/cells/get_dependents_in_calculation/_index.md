---
title: get_dependents_in_calculation метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 370
url: /ru/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation {#int-int-bool}
Получает все ячейки, результат вычисления которых зависит от конкретной ячейки.


###  Возврат

Перечислитель для перечисления всех зависимых объектов (Cell объектов)


```python
def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | Индекс строки конкретной ячейки|
| column | int | Индекс столбца конкретной ячейки.|
| recursive | bool | Возвращает ли те зависимые элементы, которые не ссылаются непосредственно на конкретную ячейку<br/> но ссылка на другие листы этой ячейки.|
###  Примечания

Чтобы использовать этот метод, убедитесь, что в книге установлено истинное значение для
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/ru/aspose.cells/formulasettings#enable_calculation_chain) и полностью рассчитан с этой настройкой.
Если для этой ячейки нет ссылки на формулу, будет возвращено значение null.
Более подробную информацию и пример можно найти по номеру [`Cell.get_dependents_in_calculation`](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation).


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
