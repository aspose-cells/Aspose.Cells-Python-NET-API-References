---
title: get_array_mode_parameters метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 20
url: /ru/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters {#str}
Получает индексы параметров заданной пользовательской функции, которые необходимо вычислить в режиме массива.


###  Возврат

Индексы параметров, которые необходимо вычислить в режиме массива для заданной пользовательской функции.
По умолчанию установлено значение null, нет параметра, который необходимо вычислять в режиме массива для пользовательской функции.


```python
def get_array_mode_parameters(self, function_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| function_name | str | Имя пользовательской функции.|
###  Примечания

Для выражения, которое необходимо вычислить, на примере A:A+B:B:
Обычно в режиме значений оно рассчитывается до одного значения в соответствии с текущей базой ячеек.
Но в режиме массива все значения A1+B1,A2+B2,A3+B3,... будут рассчитаны и использованы для расчета.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CustomFunctionDefinition`](/cells/python-net/ru/aspose.cells/customfunctiondefinition)
