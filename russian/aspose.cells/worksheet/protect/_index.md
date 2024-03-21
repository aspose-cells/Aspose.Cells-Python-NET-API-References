---
title: protect метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 200
url: /ru/aspose.cells/worksheet/protect/
is_root: false
---
##  protect {#aspose.cells.ProtectionType}
Защищает рабочий лист.



```python
def protect(self, type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/ru/aspose.cells/protectiontype) | Тип защиты.|
###  Примечания

Этот метод защищает лист без пароля. Он может использовать рабочий лист protect во всех версиях файла Excel.

##  protect {#aspose.cells.ProtectionType-str-str}

Защищает рабочий лист.



```python
def protect(self, type, password, old_password):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/ru/aspose.cells/protectiontype) | Тип защиты.|
| password | str | Пароль.|
| old_password | str | Если рабочий лист уже защищен паролем, укажите старый пароль.<br/> В противном случае вы можете установить для этого параметра нулевое значение или пустую строку.|
###  Примечания

Этот метод позволяет создать рабочий лист protect во всех версиях файла Excel.
###  Пример


```python
from aspose.cells import ProtectionType, Workbook

# Instantiating a Workbook object
excel = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = excel.worksheets[0]
# Protecting the worksheet with a password
worksheet.protect(ProtectionType.ALL, "aspose", None)
# Saving the modified Excel file in default (that is Excel 20003) format
excel.save("output.xls")

```



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
