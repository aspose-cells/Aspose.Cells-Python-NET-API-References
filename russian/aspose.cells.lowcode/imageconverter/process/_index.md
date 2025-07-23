---
title: process метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.lowcode/imageconverter/process/
is_root: false
---
##  process(, файл_шаблона, файл_результата){#str-str}
Конвертирует файл шаблона в изображения.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| template_file | str | Файл шаблона для преобразования в изображения.|
| result_file | str | Результирующий файл (шаблон имени) для сгенерированных изображений.|
###  Примечания

Выходные файлы будут созданы из указанного файла результата.
путем добавления порядкового номера листа и разделенной части.
Например, если указан выходной файл Image.png, то сгенерированное изображение
файлы будут Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, load_options, save_options){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}
Преобразует файл шаблона в изображения



```python

@staticmethod
def process(load_options, save_options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodeloadoptions) | Варианты ввода и загрузки|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptions) | Варианты вывода и сохранения|
###  Примечания

При конвертации в изображение формата, поддерживающего несколько страниц (например, tiff),
указанный [`LowCodeSaveOptions.output_file`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptions#output_file)
или [`LowCodeSaveOptions.output_stream`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptions#output_stream) будет использоваться непосредственно для результирующего изображения.


Для других типов изображений, если в параметрах сохранения в качестве выходного параметра указан Поток,
то все полученные изображения будут сохранены в одном потоке.
В противном случае выходные файлы будут созданы из указанного выходного файла.
из вариантов сохранения путем добавления порядкового номера листа и разделенной части.
Например, если указан выходной файл Image.png, то сгенерированное изображение
файлы будут Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, load_options, save_options, provider){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-AbstractLowCodeSaveOptionsProvider}




```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodeloadoptions) |  |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptions) |  |
| provider | AbstractLowCodeSaveOptionsProvider |  |



###  Смотрите также
* модуль [`aspose.cells.lowcode`](../../)
* класс [`ImageConverter`](/cells/python-net/ru/aspose.cells.lowcode/imageconverter)
