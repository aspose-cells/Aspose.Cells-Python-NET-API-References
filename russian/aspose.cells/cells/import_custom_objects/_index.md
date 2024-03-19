---
title: import_custom_objects метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 630
url: /ru/aspose.cells/cells/import_custom_objects/
is_root: false
---
##  import_custom_objects {#list-int-int-aspose.cells.ImportTableOptions}
Импортирует пользовательские объекты.


###  Возврат

Общее количество импортированных строк.


```python
def import_custom_objects(self, list, first_row, first_column, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| list | list | Пользовательский объект|
| first_row | int | Номер строки первой ячейки для импорта.|
| first_column | int | Номер столбца первой ячейки для импорта.|
| options | [`ImportTableOptions`](/cells/python-net/ru/aspose.cells/importtableoptions) | Варианты импорта.|
###  Примечания

Пользовательские объекты должны быть одного типа.

##  import_custom_objects {#list-list-bool-int-int-int-bool-str-bool}

Импортирует пользовательские объекты.


###  Возврат

Общее количество импортированных строк.


```python
def import_custom_objects(self, list, property_names, is_property_name_shown, first_row, first_column, row_number, insert_rows, date_format_string, convert_string_to_number):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| list | list | Пользовательский объект|
| property_names | list | Имена свойств. Если оно равно нулю, мы импортируем все свойства объекта.|
| is_property_name_shown | bool | Указывает, будет ли имя свойства импортировано в первую строку.|
| first_row | int | Номер строки первой ячейки для импорта.|
| first_column | int | Номер столбца первой ячейки для импорта.|
| row_number | int | Количество строк, которые необходимо импортировать.|
| insert_rows | bool | Указывает, добавляются ли дополнительные строки для соответствия данным.|
| date_format_string | str | Строка формата даты для ячеек.|
| convert_string_to_number | bool | Указывает, попытается ли этот метод преобразовать строку в число.|
###  Примечания

Пользовательские объекты должны быть одного типа.


###  Смотрите также

* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
