---
title: ShapePath класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 540
url: /ru/aspose.cells.drawing/shapepath/
is_root: false
---
##  ShapePath класс
Представляет собой путь создания, состоящий из серии ходов, линий и кривых, которые при объединении образуют геометрическую фигуру.



Тип ShapePath предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells.drawing/shapepath/__init__/#) | Инициализирует новый экземпляр класса [`ShapePath`](/cells/python-net/ru/aspose.cells.drawing/shapepath).|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [path_segement_list](/cells/python-net/ru/aspose.cells.drawing/shapepath/path_segement_list) | Получает список [`ShapeSegmentPathCollection`](/cells/python-net/ru/aspose.cells.drawing/shapesegmentpathcollection)|
| [width_pixel](/cells/python-net/ru/aspose.cells.drawing/shapepath/width_pixel) | Получает ширину этого пути в пикселях.|
| [height_pixel](/cells/python-net/ru/aspose.cells.drawing/shapepath/height_pixel) | Получает высоту этого пути в пикселях.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`move_to(self, x, y)`](/cells/python-net/ru/aspose.cells.drawing/shapepath/move_to/#float-float) |Начинает новую фигуру из указанной точки, не замыкая текущую. Все последующие точки, добавляемые к контуру, добавляются к этой новой фигуре.|
| [`line_to(self, x, y)`](/cells/python-net/ru/aspose.cells.drawing/shapepath/line_to/#float-float) | Добавляет отрезок линии к текущей фигуре.<br/> Начальная точка — это конечная точка текущей фигуры.|
| [`cubic_bezier_to(self, ctr_x1, ctr_y1, ctr_x2, ctr_y2, end_x, end_y)`](/cells/python-net/ru/aspose.cells.drawing/shapepath/cubic_bezier_to/#float-float-float-float-float-float) | Добавляет кубическую кривую Безье к текущей фигуре. Начальной точкой является конечная точка текущей фигуры.|
| [`arc_to(self, w_r, h_r, st_ang, sw_ang)`](/cells/python-net/ru/aspose.cells.drawing/shapepath/arc_to/#float-float-float-float) | Добавляет эллиптическую дугу к текущей фигуре. Начальной точкой является конечная точка текущей фигуры.|
| [`close(self)`](/cells/python-net/ru/aspose.cells.drawing/shapepath/close/#) | Закрывает текущую фигуру и начинает новую. Если текущая фигура содержит последовательность соединённых линий и кривых, метод замыкает цикл, соединяя линию от конечной точки к начальной.|



###  Смотрите также
* модуль [`aspose.cells.drawing`](..)
* класс [`ShapePath`](/cells/python-net/ru/aspose.cells.drawing/shapepath)
* класс [`ShapeSegmentPathCollection`](/cells/python-net/ru/aspose.cells.drawing/shapesegmentpathcollection)
