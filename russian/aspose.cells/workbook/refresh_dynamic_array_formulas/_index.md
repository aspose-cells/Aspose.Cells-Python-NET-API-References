---
title: refresh_dynamic_array_formulas метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 290
url: /ru/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas(self, calculate) {#bool}
Обновляет динамические формулы массива (переносит в новый диапазон соседних ячеек в соответствии с текущими данными)
Другие формулы в рабочей книге не будут вычисляться рекурсивно, даже если они использовались в формулах динамического массива.



```python

def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| calculate | bool | Вычисляет ли и обновляет ли значения ячеек для этих динамических формул массива|


##  refresh_dynamic_array_formulas(self, calculate, copts) {#bool-aspose.cells.CalculationOptions}
Обновляет динамические формулы массива (переносит в новый диапазон соседних ячеек в соответствии с текущими данными)



```python

def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| calculate | bool | Вычисляет ли и обновляет ли значения ячеек для этих динамических формул массива|
| copts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчетных формул|
###  Примечания

Из соображений производительности мы не обновляем автоматически все формулы динамического массива.
когда изменилась сама формула или данные, на которые она ссылается.
Поэтому пользователю необходимо вызывать этот метод вручную после операций, которые могут повлиять на формулы динамического массива,
такие как импорт/установка значений ячеек, вставка/удаление строк/столбцов/диапазонов и т. д.

Для большинства формул с функциями расчет диапазона разлива также требует расчета формулы,
поэтому в общем случае предпочтительным является истинное значение флага «вычислить».
Если формула простая, например, ссылка на диапазон или массив (например, "=C1:E5", "={1,2;3,4}", ...),
простая функция для диапазона или массива (например, "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
и все формулы будут рассчитаны позже (например, по [`Workbook.calculate_formula`](/cells/python-net/ru/aspose.cells/workbook/calculate_formula)),
то использование ложного значения для флага «calculate» может помочь избежать дублирования вычислений и повысить производительность.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
