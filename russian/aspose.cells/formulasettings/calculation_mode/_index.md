---
title: calculation_mode недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 60
url: /ru/aspose.cells/formulasettings/calculation_mode/
is_root: false
---
##  calculation_mode недвижимость

Возвращает или задает режим расчета рабочей книги в MS Excel.

###  Примечания

Это свойство предназначено только для сохранения настроек в результирующем файле электронной таблицы.
чтобы другие приложения (например, MS Excel) могли действовать соответствующим образом при загрузке и обработке полученного файла.
Для повышения производительности большинства пользовательских приложений мы не вычисляем автоматически никакие формулы в рабочей книге,
независимо от того, какой режим установлен для этого свойства.
Если пользователю необходимо вычислить формулы, всегда вызывайте методы для разных объектов в соответствии с требованиями:
[`Workbook.calculate_formula`](/cells/python-net/aspose.cells/workbook/calculate_formula), [`Worksheet.calculate_formula`](/cells/python-net/aspose.cells/worksheet/calculate_formula),
[`Cell.calculate`](/cells/python-net/ru/aspose.cells/cell/calculate), ...и т.д.
###  Определение:
```python
@property
def calculation_mode(self):
    ...
@calculation_mode.setter
def calculation_mode(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CalcModeType`](/cells/python-net/ru/aspose.cells/calcmodetype)
* класс [`FormulaSettings`](/cells/python-net/ru/aspose.cells/formulasettings)
