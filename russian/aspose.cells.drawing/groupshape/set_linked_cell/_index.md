---
title: set_linked_cell метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 210
url: /ru/aspose.cells.drawing/groupshape/set_linked_cell/
is_root: false
---
##  set_linked_cell {#str-bool-bool}
Устанавливает диапазон, связанный со значением элемента управления.



```python
def set_linked_cell(self, formula, is_r1c1, is_local):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Диапазон, связанный со значением элемента управления.|
| is_r1c1 | bool | Необходимо ли форматировать формулу как R1C1.|
| is_local | bool | Необходимо ли форматировать формулу по локали.|

###  Пример

```python

# After executing the code below, a ScrollBar object is created in the generated file. As you drag the slider, the value is displayed in cell A12.
# ActiveX Controls
# Aspose.Cells.Drawing.Shape scrollBar = book.Worksheets[0].Shapes.AddActiveXControl( Aspose.Cells.Drawing.ActiveXControls.ControlType.ScrollBar,2, 0, 2, 0, 30, 130);
# Form Controls
scrollBar = book.worksheets[0].shapes.add_scroll_bar(2, 0, 2, 0, 130, 30)
# Sets the range linked to the control's value.
scrollBar.set_linked_cell("$A$12", False, True)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`GroupShape`](/cells/python-net/ru/aspose.cells.drawing/groupshape)
