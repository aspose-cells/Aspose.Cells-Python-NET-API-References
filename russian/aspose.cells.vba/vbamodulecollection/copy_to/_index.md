---
title: copy_to метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 60
url: /ru/aspose.cells.vba/vbamodulecollection/copy_to/
is_root: false
---
##  copy_to {#list}
Копирует весь список массивов в совместимый список одномерных массивов, начиная с начала списка целевых массивов.



```python
def copy_to(self, array):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array | list | Список одномерного массива, который является местом назначения списка скопированных элементов массива. Список массивов должен иметь индексацию, начинающуюся с нуля.|


##  copy_to {#int-list-int-int}
Копирует диапазон элементов из списка массива в совместимый список одномерных массивов, начиная с указанного индекса списка целевого массива.



```python
def copy_to(self, index, array, array_index, count):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| index | int |Индекс, отсчитываемый от нуля, в списке исходного массива, с которого начинается копирование.|
| array | list | Список одномерного массива, который является местом назначения элементов, скопированных из списка массива. Список массивов должен иметь индексацию, начинающуюся с нуля.|
| array_index | int | Индекс, отсчитываемый от нуля, в списке массивов, с которого начинается копирование.|
| count | int | Количество элементов для копирования.|



###  Смотрите также
* модуль [`aspose.cells.vba`](../../)
* класс [`VbaModuleCollection`](/cells/python-net/ru/aspose.cells.vba/vbamodulecollection)
