---
title: set_embedded_object метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 190
url: /ru/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object {#bool-bytes-str-bool-str}
Устанавливает данные встроенного объекта.



```python
def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| link_to_file | bool | Указывает, связан ли объект с файлом. Если это правда, параметр objectData игнорируется.|
| object_data | bytes | Данные встроенного объекта.|
| source_file_name | str | Имя файла.|
| display_as_icon | bool | Указывает, отображается ли объект в виде значка.<br/> Если это правда, данные исходного изображения будут покрыты значком.|
| label | str | Метка значка. Работает только тогда, когда displayAsIcon имеет значение true.|


##  set_embedded_object {#bool-bytes-str-bool-str-bool}
Устанавливает данные встроенного объекта.



```python
def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| link_to_file | bool | Указывает, связан ли объект с файлом. Если это правда, параметр objectData игнорируется.|
| object_data | bytes | Данные встроенного объекта.|
| source_file_name | str | Имя файла.|
| display_as_icon | bool | Указывает, отображается ли объект в виде значка.<br/> Если это правда, данные исходного изображения будут покрыты значком.|
| label | str | Метка значка. Работает только тогда, когда displayAsIcon имеет значение true.|
| update_icon | bool |Указывает, обновляется ли значок автоматически.|
###  Примечания

Поскольку Aspose может обновить встраивание всех значков файлов, лучше добавить правильный значок с `update_icon` как ложный.


###  Смотрите также

* модуль [`aspose.cells.drawing`](../../)
* класс [`OleObject`](/cells/python-net/ru/aspose.cells.drawing/oleobject)
