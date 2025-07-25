---
title: set_desired_size метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.rendering/imageorprintoptions/set_desired_size/
is_root: false
---
##  set_desired_size(self, desired_width, desired_height) {#int-int}
Устанавливает желаемую ширину и высоту изображения.



```python

def set_desired_size(self, desired_width, desired_height):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| desired_width | int | желаемая ширина в пикселях|
| desired_height | int | желаемая высота в пикселях|
###  Примечания

ПРИМЕЧАНИЕ: Этот элемент устарел. Вместо этого,
используйте [`ImageOrPrintOptions.set_desired_size`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions/set_desired_size), установив параметр keepAspectRatio на false.
 Эта недвижимость будет снесена через 12 месяцев, с мая 2023 года.
Aspose приносит извинения за любые причиненные вам неудобства.

##  set_desired_size(self, desired_width, desired_height, keep_aspect_ratio) {#int-int-bool}
Устанавливает желаемую ширину и высоту изображения.



```python

def set_desired_size(self, desired_width, desired_height, keep_aspect_ratio):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| desired_width | int | желаемая ширина в пикселях|
| desired_height | int | желаемая высота в пикселях|
| keep_aspect_ratio | bool | сохранять ли соотношение сторон исходного изображения|
###  Примечания

Ширина и высота выходного изображения в пикселях будут зависеть только от
задайте желаемую ширину и высоту.


[`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) и [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
В этом случае это не повлияет на ширину и высоту выходного изображения.


###  Смотрите также
* модуль [`aspose.cells.rendering`](../../)
* класс [`ImageOrPrintOptions`](/cells/python-net/ru/aspose.cells.rendering/imageorprintoptions)
