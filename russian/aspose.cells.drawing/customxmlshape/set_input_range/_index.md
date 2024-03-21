---
title: set_input_range метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 190
url: /ru/aspose.cells.drawing/customxmlshape/set_input_range/
is_root: false
---
##  set_input_range {#str-bool-bool}
Устанавливает диапазон, используемый для заполнения элемента управления.



```python
def set_input_range(self, formula, is_r1c1, is_local):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Диапазон, используемый для заполнения элемента управления.|
| is_r1c1 | bool | Необходимо ли форматировать формулу как R1C1.|
| is_local | bool | Необходимо ли форматировать формулу по локали.|

###  Пример

```python

# After executing the code below, a ListBox object is created in the generated file. When the selected option is clicked, the selected value is displayed in cell A12.
for i in range(10):
    cell = book.worksheets[0].cells.get(i, 0)
    cell.value = i + 1
# Create a ListBox object
# ActiveX Controls
# Aspose.Cells.Drawing.Shape listBox = book.Worksheets[0].Shapes.AddActiveXControl( Aspose.Cells.Drawing.ActiveXControls.ControlType.ListBox,2, 0, 2, 0, 130, 130);
# Form Controls
listBox = book.worksheets[0].shapes.add_list_box(2, 0, 2, 0, 130, 130)
# Sets the range used to fill the control.
listBox.set_input_range("$A$1:$A$6", False, False)
# Sets the range linked to the control's value.
listBox.set_linked_cell("$A$12", False, True)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`CustomXmlShape`](/cells/python-net/ru/aspose.cells.drawing/customxmlshape)
