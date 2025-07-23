---
title: to_printer метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 60
url: /ru/aspose.cells.rendering/workbookrender/to_printer/
is_root: false
---
##  to_printer(self, printer_name) {#str}
Распечатать книгу на принтере



```python

def to_printer(self, printer_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_name | str | имя принтера, например: «Microsoft Office Document Image Writer»|


##  to_printer(self, printer_settings) {#aspose.pydrawing.printing.PrinterSettings}
Распечатать книгу на принтере



```python

def to_printer(self, printer_settings):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | настройки принтера, например PrinterName, Duplex|


##  to_printer(self, printer_name, job_name) {#str-str}
Распечатать книгу на принтере



```python

def to_printer(self, printer_name, job_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_name | str | имя принтера, например: «Microsoft Office Document Image Writer»|
| job_name | str | задать имя задания печати|


##  to_printer(self, printer_settings, job_name) {#aspose.pydrawing.printing.PrinterSettings-str}
Распечатать книгу на принтере



```python

def to_printer(self, printer_settings, job_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_settings | aspose.pydrawing.printing.PrinterSettings | настройки принтера, например PrinterName, Duplex|
| job_name | str | задать имя задания печати|


##  to_printer(self, printer_name, print_page_index, print_page_count) {#str-int-int}
Распечатать книгу на принтере



```python

def to_printer(self, printer_name, print_page_index, print_page_count):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| printer_name | str | имя принтера, например: «Microsoft Office Document Image Writer»|
| print_page_index | int | индекс первой страницы для печати (начиная с 0), должен находиться в диапазоне [0, WorkbookRender.PageCount-1]|
| print_page_count | int | количество страниц для печати, оно должно быть больше нуля|
###  Примечания

ПРИМЕЧАНИЕ: Этот метод уже устарел.
Вместо этого используйте ToPrinter(string PrinterName) и ImageOrPrintOptions.PageIndex, PageCount, чтобы задать первую страницу и количество страниц для печати.
 Данная недвижимость будет снесена через 12 месяцев с декабря 2021 года.
Aspose приносит извинения за любые причиненные вам неудобства.


###  Смотрите также
* модуль [`aspose.cells.rendering`](../../)
* класс [`WorkbookRender`](/cells/python-net/ru/aspose.cells.rendering/workbookrender)
