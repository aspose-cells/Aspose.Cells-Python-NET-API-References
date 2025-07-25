---
title: get_style метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 80
url: /ru/aspose.cells/row/get_style/
is_root: false
---
##  get_style(self) {#}
Получает стиль этой строки.



```python

def get_style(self):
    ...
```


###  Примечания

Изменение возвращенного объекта стиля напрямую не оказывает никакого влияния на эту строку или любые ячейки в этой строке.
Вам необходимо вызвать метод [`Row.apply_style`](/cells/python-net/ru/aspose.cells/row/apply_style) или [`Row.set_style`](/cells/python-net/ru/aspose.cells/row/set_style)
чтобы применить изменение к этой строке.

Стиль строки — это стиль, который будет унаследован ячейками в этой строке (теми ячейками, у которых нет пользовательских настроек стиля,
(например, существующие ячейки, для которых явно не задан стиль, или те, для которых не был создан экземпляр)


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Row`](/cells/python-net/ru/aspose.cells/row)
