---
title: insert_image метод
second_title: Aspose.Cells.GridJs for Python via .NET API
description:
type: docs
weight: 130
url: /ru/aspose.cellsgridjs/gridjsworkbook/insert_image/
is_root: false
---
##  insert_image {#str-str-io.RawIOBase-str}

Вставляет изображение в рабочий лист из файлового потока или URL-адреса (должен быть указан либо файловый поток, либо URL-адрес).
 или
Вставляет фигуру, если p.type является одним из AutoShapeType.


###  Возврат


Строка формата JSON вставленного изображения.


```python
def insert_image(self, uid, p, s, image_url):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| uid | str | Уникальный идентификатор файлового кэша.|
| p | str | Строка формата JSON для операции, которая определяет местоположение ячейки, имя листа, верхнюю левую строку, верхний левый столбец для изображения и т. д. {name:'sheet1',ri:1,ci:1} |
| s | io.RawIOBase | Файловый поток файла изображения|
| image_url | str | URL-адрес файла изображения|



###  Смотрите также
* модуль [`aspose.cellsgridjs`](../../)
* класс [`GridJsWorkbook`](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook)
