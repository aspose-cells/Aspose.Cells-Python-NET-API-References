---
title: get_style метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells/column/get_style/
is_root: false
---
##  get_style(self) {#}
Получает стиль этого столбца.



```python

def get_style(self):
    ...
```


###  Примечания

Изменение возвращаемого объекта стиля напрямую не оказывает никакого влияния на этот столбец или любые ячейки в этом столбце.
Вам необходимо вызвать метод [`Column.apply_style`](/cells/python-net/ru/aspose.cells/column/apply_style) или [`Column.set_style`](/cells/python-net/ru/aspose.cells/column/set_style)
чтобы применить изменение к этому столбцу.

Стиль столбца — это стиль, который будет унаследован ячейками в этом столбце (теми ячейками, у которых нет пользовательских настроек стиля,
(например, существующие ячейки, для которых явно не задан стиль, или те, для которых не был создан экземпляр)


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Column`](/cells/python-net/ru/aspose.cells/column)
