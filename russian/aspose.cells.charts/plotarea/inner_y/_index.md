---
title: inner_y недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 270
url: /ru/aspose.cells.charts/plotarea/inner_y/
is_root: false
---
##  inner_y недвижимость

Возвращает или возвращает координату x верхнего угла области построения в единицах, равных 1/4000 области диаграммы.

###  Примечания

Ограничивающая рамка области построения включает в себя область построения, деления (метки делений) и небольшую рамку вокруг делений.
 Если значение не создано MS Excel, пожалуйста, вызовите метод Chart.Calculate() перед вызовом этого метода.


**Х** , **Y** , **Ширина** и**Высота** из**ПлощадьУчастка** представляет собой площадь участка
 ограничивающая рамка, включающая область графика, деления (метки делений) и небольшую рамку вокруг делений.
 Если вы хотите получить реальный размер площади участка, вам следует позвонить**InnerXRatioToChart** , **InnerYRatioToChart** , **InnerWidthRatioToChart** и
**InnerHeightRatioToChart** характеристики.


Для Excel 2007 и более поздних версий значение по умолчанию равно нулю. Вам следует вызвать get значение после вызова Chart.Calculate().
###  Определение:
```python
@property
def inner_y(self):
    ...
@inner_y.setter
def inner_y(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.charts`](../../)
* класс [`PlotArea`](/cells/python-net/ru/aspose.cells.charts/plotarea)
