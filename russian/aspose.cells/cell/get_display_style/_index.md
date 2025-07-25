---
title: get_display_style метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 110
url: /ru/aspose.cells/cell/get_display_style/
is_root: false
---
##  get_display_style(self) {#}
Получает стиль отображения этой ячейки.


###  Возврат

стиль отображения этой ячейки


```python

def get_display_style(self):
    ...
```


###  Примечания

То же самое с использованием [`BorderType.SIDE_BORDERS`](/cells/python-net/ru/aspose.cells/bordertype#SIDE_BORDERS)
для [`Cell.get_display_style`](/cells/python-net/ru/aspose.cells/cell/get_display_style).
То есть этот метод проверит и отрегулирует верхнюю/нижнюю/левую/правую границы этой ячейки.
в соответствии со стилем ([`Cell.get_style`](/cells/python-net/ru/aspose.cells/cell/get_style)) соседних с ним ячеек,
но не проверяйте объединенные ячейки и не проверяйте стиль отображения соседних ячеек.

##  get_display_style(self, include_merged_borders) {#bool}
Получает стиль отображения этой ячейки.


###  Возврат

стиль отображения этой ячейки


```python

def get_display_style(self, include_merged_borders):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| include_merged_borders | bool | Указывает, проверяются ли границы объединенных ячеек.|
###  Примечания

Если указанный флаг ложный, то то же самое с [`Cell.get_display_style`](/cells/python-net/ru/aspose.cells/cell/get_display_style).
В противном случае то же самое с использованием
[`BorderType.SIDE_BORDERS`](/cells/python-net/aspose.cells/bordertype#SIDE_BORDERS)|[`BorderType.DYNAMIC_STYLE_BORDERS`](/cells/python-net/aspose.cells/bordertype#DYNAMIC_STYLE_BORDERS)
для [`Cell.get_display_style`](/cells/python-net/ru/aspose.cells/cell/get_display_style).

##  get_display_style(self, adjacent_borders) {#aspose.cells.BorderType}
Получает стиль отображения этой ячейки.


###  Возврат

стиль отображения этой ячейки


```python

def get_display_style(self, adjacent_borders):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| adjacent_borders | [`BorderType`](/cells/python-net/ru/aspose.cells/bordertype) | Указывает, какие границы необходимо проверить и скорректировать<br/> по границам соседних ячеек.|
###  Примечания

Если на эту ячейку также влияют другие настройки, такие как условное форматирование, объекты списка и т. д.,
то стиль отображения может отличаться от [`Cell.get_style`](/cells/python-net/ru/aspose.cells/cell/get_style).

Для флагов корректировки границ по соседним ячейкам,
[`BorderType.TOP_BORDER`](/cells/python-net/aspose.cells/bordertype#TOP_BORDER)/[`BorderType.BOTTOM_BORDER`](/cells/python-net/aspose.cells/bordertype#BOTTOM_BORDER)
/[`BorderType.LEFT_BORDER`](/cells/python-net/aspose.cells/bordertype#LEFT_BORDER)/[`BorderType.RIGHT_BORDER`](/cells/python-net/aspose.cells/bordertype#RIGHT_BORDER)
обозначить, нужно ли проверять и объединять нижнюю/верхнюю/правую/левую границы
левые/правые/верхние/нижние ячейки, соседствующие с этой.

Для обеспечения производительности и совместимости,
некоторые перечисления используются для обозначения некоторых специальных операций:

[`BorderType.HORIZONTAL`](/cells/python-net/aspose.cells/bordertype#HORIZONTAL)/[`BorderType.VERTICAL`](/cells/python-net/aspose.cells/bordertype#VERTICAL)
указать, следует ли проверять и объединять нижнюю/правую границу объединенных ячеек с этой.

[`BorderType.DIAGONAL`](/cells/python-net/ru/aspose.cells/bordertype#DIAGONAL)(то есть и [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/ru/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER) и
[`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/ru/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER) были установлены) обозначает проверку и объединение границ
от стиля отображения соседних ячеек.

Обратите внимание, что проверка границ/стилей соседних ячеек, особенно стилей отображения,
Это трудоёмкий процесс. Если нет необходимости получать границы для возвращаемого стиля,
с помощью [`BorderType.NONE`](/cells/python-net/ru/aspose.cells/bordertype#NONE) отключить обработку соседних ячеек
даст лучшую производительность.
При получении границ смежных ячеек только из стилей, определенных для этих ячеек (без установки
[`BorderType.DIAGONAL`](/cells/python-net/ru/aspose.cells/bordertype#DIAGONAL)), производительность также может быть лучше, поскольку проверка
отображение стиля одной ячейки также занимает много времени.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
