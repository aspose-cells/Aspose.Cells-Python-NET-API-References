---
title: update_linked_data_source метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 420
url: /ru/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source {#list}
Если эта книга содержит внешние ссылки на другой источник данных,
Aspose.Cells попытается получить последние данные из указанных источников.



```python
def update_linked_data_source(self, external_workbooks):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| external_workbooks | list | Книги, которые будут использоваться для обновления данных внешних ссылок, на которые ссылается эта книга.<br/>Соответствие этих книг внешним ссылкам определяется номером [`Workbook.file_name`](/cells/python-net/ru/aspose.cells/workbook#file_name).<br/>и [`ExternalLink.data_source`](/cells/python-net/ru/aspose.cells/externallink#data_source). Поэтому убедитесь, что [`Workbook.file_name`](/cells/python-net/ru/aspose.cells/workbook#file_name) имеет<br/> были указаны правильные значения для каждой книги, чтобы их можно было связать с соответствующей внешней ссылкой.|
###  Примечания

Если для одной книги не найдена соответствующая внешняя ссылка, то эта книга будет проигнорирована.
Поэтому, когда вы позже установите формулу с одной новой внешней ссылкой, которую вы намереваетесь сделать игнорируемой книгой
быть связан с ним, связь не может быть выполнена, пока вы не вызовете этот метод снова с этими книгами.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
