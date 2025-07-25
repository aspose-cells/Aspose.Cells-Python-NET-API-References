---
title: height недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 180
url: /ru/aspose.cells.charts/plotarea/height/
is_root: false
---
##  height недвижимость

Возвращает или задает значение height ограничивающей рамки области построения в единицах, равных 1/4000 области диаграммы.

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
def height(self):
    ...
@height.setter
def height(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.charts`](../../)
* класс [`PlotArea`](/cells/python-net/ru/aspose.cells.charts/plotarea)
