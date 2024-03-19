---
title: on_circular метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 40
url: /ru/aspose.cells/abstractcalculationmonitor/on_circular/
is_root: false
---
##  on_circular {#collections.abc.Iterator}
Внедрите этот метод для ведения бизнеса при вычислении формул с циклическими ссылками.


###  Возврат

Необходимо ли обработчику формул вычислять эти ячейки по кругу после этого вызова.
Верно, чтобы позволить обработчику формул продолжать выполнять вычисления за них.
Значение False позволяет обработчику формул просто помечать эти ячейки как вычисляемые.


```python
def on_circular(self, circular_cells_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| circular_cells_data | collections.abc.Iterator | IEnumerator с элементами [`CalculationCell`](/cells/python-net/ru/aspose.cells/calculationcell), представляющими ячейки, которые<br/> зависят от циклических ссылок.|
###  Примечания

В реализации пользователь также может установить ожидаемое значение как рассчитанный результат.
для части/всех этих ячеек, чтобы механизм формул не вычислял их рекурсивно.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`AbstractCalculationMonitor`](/cells/python-net/ru/aspose.cells/abstractcalculationmonitor)
* класс [`CalculationCell`](/cells/python-net/ru/aspose.cells/calculationcell)
