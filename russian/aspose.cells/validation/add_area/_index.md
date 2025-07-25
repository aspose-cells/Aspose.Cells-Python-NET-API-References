---
title: add_area метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/validation/add_area/
is_root: false
---
##  add_area(self, cell_area) {#aspose.cells.CellArea}
Применяет проверку к области.



```python

def add_area(self, cell_area):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) | Район.|
###  Примечания

Это эквивалентно использованию [`Validation.add_area`](/cells/python-net/ru/aspose.cells/validation/add_area).
с проверкой пересечения и края.

##  add_area(self, cell_area, check_intersection, check_edge) {#aspose.cells.CellArea-bool-bool}
Применяет проверку к области.



```python

def add_area(self, cell_area, check_intersection, check_edge):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) | Район.|
| check_intersection | bool | Проверять ли пересечение заданной области с областями существующих проверок.<br/>Если в данной области (или ее части) была применена одна проверка,<br/>то существующая проверка должна быть сначала удалена из данной области.<br/>В противном случае могут быть вызваны повреждения сгенерированных валидаций.<br/>Если пользователь уверен, что добавляемая область не пересекается ни с одной существующей областью,<br/> Для повышения производительности этот параметр можно установить как false.|
| check_edge | bool | Проверяйте ли края областей применения этой проверки.<br/>Внутренние настройки проверки зависят от верхнего левого из применяемых диапазонов,<br/>так что если заданная область станет новым верхним левым из примененных диапазонов,<br/>внутренние настройки следует изменить и перестроить, в противном случае можно получить неожиданный результат.<br/>Если пользователь уверен, что добавленная область не находится в левом верхнем углу,<br/> Для повышения производительности этот параметр можно установить как false.|
###  Примечания

При использовании этого метода мы удалим все старые проверки в заданной области.
Для левого верхнего диапазона проверки, во-первых, его StartRow имеет наименьшее значение,
во-вторых, его StartColumn является наименьшим из тех областей, которые имеют такое же наименьшее значение StartRow.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Validation`](/cells/python-net/ru/aspose.cells/validation)
