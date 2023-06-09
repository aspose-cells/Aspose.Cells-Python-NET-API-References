---
title: get_dependents метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 90
url: /ru/aspose.cells/cell/get_dependents/
is_root: false
---
##  get_dependents(is_all) {#bool}
Получить все ячейки, формула которых напрямую ссылается на эту ячейку.



```python
def get_dependents(self, is_all):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| is_all | bool | Указывает, следует ли проверять формулы на других листах.|
###  Примечания

* Если одна ссылка, содержащая эту ячейку, появляется в формуле одной ячейки, эта ячейка будет восприниматься как

зависит от этой ячейки, независимо от того, используется ссылка или эта ячейка при расчете.
Например, хотя ячейка A2 в формуле «=ЕСЛИ(ИСТИНА,A1,A2)» не используется при расчете,
эта формула по-прежнему считается зависимой от A2.
Чтобы получить те формулы, результаты расчетов которых зависят от этой ячейки, используйте [Cell.get_dependents_in_calculation(recursive)](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation). При отслеживании зависимостей для одной ячейки все формулы в рабочей книге или рабочем листе будут проанализированы и проверены.
Так что это процесс, требующий времени. Если пользователю необходимо отследить иждивенцев для большого количества ячеек, использование этого метода
вызвать плохую работу. Из соображений производительности пользователь должен вместо этого использовать [Cell.get_dependents_in_calculation(recursive)](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation).
Или пользователь может сначала собрать карту прецедентов всех ячеек по номеру [Cell.get_precedents()](/cells/python-net/ru/aspose.cells/cell/get_precedents),
а затем построить карту иждивенцев в соответствии с картой прецедентов.

* Если одна ссылка, содержащая эту ячейку, появляется в формуле одной ячейки, эта ячейка будет восприниматься как
зависит от этой ячейки, независимо от того, используется ссылка или эта ячейка при расчете.
Например, хотя ячейка A2 в формуле «=ЕСЛИ(ИСТИНА,A1,A2)» не используется при расчете,
эта формула по-прежнему считается зависимой от A2.
Чтобы получить те формулы, результаты расчетов которых зависят от этой ячейки, используйте [Cell.get_dependents_in_calculation(recursive)](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation). При отслеживании зависимостей для одной ячейки все формулы в рабочей книге или рабочем листе будут проанализированы и проверены.
Так что это процесс, требующий времени. Если пользователю необходимо отследить иждивенцев для большого количества ячеек, использование этого метода
вызвать плохую работу. Из соображений производительности пользователь должен вместо этого использовать [Cell.get_dependents_in_calculation(recursive)](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation).
Или пользователь может сначала собрать карту прецедентов всех ячеек по номеру [Cell.get_precedents()](/cells/python-net/ru/aspose.cells/cell/get_precedents),
а затем построить карту иждивенцев в соответствии с картой прецедентов.

* Если одна ссылка, содержащая эту ячейку, появляется в формуле одной ячейки, эта ячейка будет восприниматься как
зависит от этой ячейки, независимо от того, используется ссылка или эта ячейка при расчете.
Например, хотя ячейка A2 в формуле «=ЕСЛИ(ИСТИНА,A1,A2)» не используется при расчете,
эта формула по-прежнему считается зависимой от A2.
Чтобы получить те формулы, результаты расчетов которых зависят от этой ячейки, используйте [Cell.get_dependents_in_calculation(recursive)](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation). При отслеживании зависимостей для одной ячейки все формулы в рабочей книге или рабочем листе будут проанализированы и проверены.
Так что это процесс, требующий времени. Если пользователю необходимо отследить иждивенцев для большого количества ячеек, использование этого метода
вызвать плохую работу. Из соображений производительности пользователь должен вместо этого использовать [Cell.get_dependents_in_calculation(recursive)](/cells/python-net/ru/aspose.cells/cell/get_dependents_in_calculation).
Или пользователь может сначала собрать карту прецедентов всех ячеек по номеру [Cell.get_precedents()](/cells/python-net/ru/aspose.cells/cell/get_precedents),
а затем построить карту иждивенцев в соответствии с картой прецедентов.
###  Пример

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
dependents = cells.get("B1").get_dependents(True)
for i in range(len(dependents)):
    print(dependents[i].name)

```



###  Смотрите также
* модуль [aspose.cells](../../)
* класс [Cell](/cells/python-net/ru/aspose.cells/cell)
