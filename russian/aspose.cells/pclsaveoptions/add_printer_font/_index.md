---
title: add_printer_font метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/pclsaveoptions/add_printer_font/
is_root: false
---
##  add_printer_font(self, font_full_name, font_pcl_name) {#str-str}
Добавляет информацию о шрифте, который уже добавлен в принтер производителем.



```python

def add_printer_font(self, font_full_name, font_pcl_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| font_full_name | str | Полное название шрифта (например, «Times New Roman Bold Italic»), используемого в исходном файле.|
| font_pcl_name | str | Имя шрифта, который будет использоваться в выходном документе Pcl.|
###  Примечания

Согласно спецификации Pcl, в любой принтер должно быть встроено 52 шрифта.
Однако производители могут добавлять в свои устройства и другие шрифты.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`PclSaveOptions`](/cells/python-net/ru/aspose.cells/pclsaveoptions)
