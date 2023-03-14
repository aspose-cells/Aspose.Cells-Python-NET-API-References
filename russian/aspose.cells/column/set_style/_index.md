---
title: set_style метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 40
url: /ru/aspose.cells/column/set_style/
is_root: false
---
##  set_style(style) {#Style}
Задает стиль этого столбца.



```python
def set_style(self, style):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| style | [Style](/cells/python-net/ru/aspose.cells/style) | стиль, который будет использоваться в качестве стиля по умолчанию для ячеек в этом столбце.|
###  Примечания

Этот метод только устанавливает данный стиль в качестве стиля по умолчанию для этого столбца,
без изменения настроек стиля для существующих ячеек в этом столбце.
Чтобы одновременно обновить настройки стиля существующих ячеек до указанного стиля,
пожалуйста, используйте [Column.apply_style(style, flag)](/cells/python-net/ru/aspose.cells/column/apply_style)


###  Смотрите также
* модуль [aspose.cells](../../)
* класс [Column](/cells/python-net/ru/aspose.cells/column)
