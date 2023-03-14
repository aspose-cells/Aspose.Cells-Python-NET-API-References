---
title: get_style метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 30
url: /ru/aspose.cells/column/get_style/
is_root: false
---
##  get_style() {#}
Получает стиль этого столбца.



```python
def get_style(self):
    ...
```


###  Примечания

Изменение возвращенного объекта стиля напрямую не влияет на этот столбец или любые ячейки в этом столбце.
Вы должны вызвать метод [Column.apply_style(style, flag)](/cells/python-net/ru/aspose.cells/column/apply_style) или [Column.set_style(style)](/cells/python-net/ru/aspose.cells/column/set_style)
чтобы применить изменение к этому столбцу.

Стиль столбца — это стиль, который будет унаследован ячейками в этом столбце (теми ячейками, которые не имеют пользовательских настроек стиля,
например, существующие ячейки, стиль которых не был задан явно, или те, которые не были созданы)


###  Смотрите также
* модуль [aspose.cells](../../)
* класс [Column](/cells/python-net/ru/aspose.cells/column)
