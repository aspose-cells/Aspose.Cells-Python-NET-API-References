---
title: update_linked_data_source метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 440
url: /ru/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source(self, external_workbooks) {#list}
Если эта рабочая книга содержит внешние ссылки на другие источники данных,
Aspose.Cells попытается получить последние данные из указанных источников.



```python

def update_linked_data_source(self, external_workbooks):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| external_workbooks | list | Рабочие книги, которые будут использоваться для обновления данных внешних ссылок, на которые ссылается эта рабочая книга.<br/>Соответствие этих рабочих книг внешним ссылкам определяется по [`Workbook.file_name`](/cells/python-net/ru/aspose.cells/workbook#file_name).<br/>и [`ExternalLink.data_source`](/cells/python-net/ru/aspose.cells/externallink#data_source). Поэтому, пожалуйста, убедитесь, что у [`Workbook.file_name`](/cells/python-net/ru/aspose.cells/workbook#file_name) есть<br/> были указаны правильные значения для каждой рабочей книги, чтобы их можно было связать с соответствующей внешней ссылкой.|
###  Примечания

Если для одной книги не удается найти соответствующую внешнюю ссылку, то эта книга будет проигнорирована.
Поэтому, когда вы позже зададите формулу с одной новой внешней ссылкой, которую вы собираетесь сделать игнорируемой рабочей книгой
если вы свяжетесь с ним, то связь не сможет быть выполнена до тех пор, пока вы снова не вызовете этот метод с этими рабочими книгами.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
