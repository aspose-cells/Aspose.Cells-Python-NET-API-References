---
title: to_printer метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 60
url: /ru/aspose.cells.rendering/workbookrender/to_printer/
is_root: false
---
##  to_printer {#str}
Отобразить книгу на принтере



```python
def to_printer(self, printer_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_name | str | имя принтера, например: «Microsoft Office Document Image Writer»|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings}
Отобразить книгу на принтере



```python
def to_printer(self, printer_settings):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | настройки принтера, например PrinterName, Duplex|


##  to_printer {#str-str}
Отобразить книгу на принтере



```python
def to_printer(self, printer_name, job_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_name | str | имя принтера, например: «Microsoft Office Document Image Writer»|
| job_name | str | задать имя задания печати|


##  to_printer {#aspose.pydrawing.printing.PrinterSettings-str}
Отобразить книгу на принтере



```python
def to_printer(self, printer_settings, job_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | настройки принтера, например PrinterName, Duplex|
| job_name | str | задать имя задания печати|


##  to_printer {#str-int-int}
Отобразить книгу на принтере



```python
def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_name | str | имя принтера, например: «Microsoft Office Document Image Writer»|
| print_page_index | int | индекс первой страницы для печати, отсчитываемый от 0, он должен находиться в диапазоне [0, WorkbookRender.PageCount-1]|
| print_page_count | int | количество страниц для печати, оно должно быть больше нуля|
###  Примечания

ПРИМЕЧАНИЕ. Этот метод устарел.
Вместо этого используйте ToPrinter(string PrinterName) и ImageOrPrintOptions.PageIndex, PageCount, чтобы установить первую страницу и количество страниц для печати.
 Этот объект недвижимости будет удален через 12 месяцев, начиная с декабря 2021 года.
Aspose приносит извинения за возможные неудобства.


###  Смотрите также
* модуль [`aspose.cells.rendering`](../../)
* класс [`WorkbookRender`](/cells/python-net/ru/aspose.cells.rendering/workbookrender)
