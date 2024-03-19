---
title: to_image метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 50
url: /ru/aspose.cells.rendering/workbookrender/to_image/
is_root: false
---
##  to_image {#io.RawIOBase}
Отобразите всю книгу как изображение Tiff для потоковой передачи.



```python
def to_image(self, stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | поток выходного изображения|


##  to_image {#str}
Отобразите всю книгу как изображение Tiff в файл.



```python
def to_image(self, filename):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| filename | str | имя файла выходного изображения|


##  to_image {#int-str}
Преобразовать определенную страницу в файл.



```python
def to_image(self, page_index, file_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| page_index | int | укажите, какую страницу нужно конвертировать|
| file_name | str | имя файла выходного изображения|


##  to_image {#int-io.RawIOBase}
Рендеринг определенной страницы в поток.



```python
def to_image(self, page_index, stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| page_index | int | укажите, какую страницу нужно конвертировать|
| stream | io.RawIOBase | поток выходного изображения|



###  Смотрите также
* модуль [`aspose.cells.rendering`](../../)
* класс [`WorkbookRender`](/cells/python-net/ru/aspose.cells.rendering/workbookrender)
