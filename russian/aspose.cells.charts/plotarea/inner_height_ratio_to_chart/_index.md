---
title: inner_height_ratio_to_chart недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 220
url: /ru/aspose.cells.charts/plotarea/inner_height_ratio_to_chart/
is_root: false
---
##  inner_height_ratio_to_chart недвижимость

Возвращает или задает высоту области построения в единицах отношения площади диаграммы.

###  Примечания

Ограничивающая рамка области построения включает в себя область построения, деления (метки делений) и небольшую рамку вокруг делений.
 Если значение не создано MS Excel, пожалуйста, вызовите метод Chart.Calculate() перед вызовом этого метода.


**XRatioToChart** , **YRatioToChart** , **Отношение ширины к диаграмме** и**HeightRatioToChart** из**ПлощадьУчастка** представляет собой площадь участка
 ограничивающая рамка, включающая область графика, деления (метки делений) и небольшую рамку вокруг делений.
 Если вы хотите получить реальный размер площади участка, вам следует позвонить**InnerXRatioToChart** , **InnerYRatioToChart** , **InnerWidthRatioToChart** и
**InnerHeightRatioToChart** характеристики.


Для Excel 2007 и более поздних версий значение по умолчанию равно нулю. Вам следует вызвать get значение после вызова Chart.Calculate().

 
InnerHeight в пикселях = InnerXRatioToChart *chart.ChartObject.Width.
###  Определение:
```python
@property
def inner_height_ratio_to_chart(self):
    ...
@inner_height_ratio_to_chart.setter
def inner_height_ratio_to_chart(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.charts`](../../)
* класс [`PlotArea`](/cells/python-net/ru/aspose.cells.charts/plotarea)
