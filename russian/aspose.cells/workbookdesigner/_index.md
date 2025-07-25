---
title: WorkbookDesigner класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1580
url: /ru/aspose.cells/workbookdesigner/
is_root: false
---
##  WorkbookDesigner класс
Инкапсулирует объект, представляющий собой электронную таблицу дизайнера.



Тип WorkbookDesigner предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/workbookdesigner/__init__/#) | Инициализирует новый экземпляр класса [`WorkbookDesigner`](/cells/python-net/ru/aspose.cells/workbookdesigner).|
| [`__init__(self, workbook)`](/cells/python-net/ru/aspose.cells/workbookdesigner/__init__/#aspose.cells.workbook) | Инициализирует новый экземпляр класса [`WorkbookDesigner`](/cells/python-net/ru/aspose.cells/workbookdesigner).|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [workbook](/cells/python-net/ru/aspose.cells/workbookdesigner/workbook) | Получает и задает объект [`WorkbookDesigner.workbook`](/cells/python-net/ru/aspose.cells/workbookdesigner#workbook).|
| [repeat_formulas_with_subtotal](/cells/python-net/ru/aspose.cells/workbookdesigner/repeat_formulas_with_subtotal) | Указывает, повторяются ли формулы со строкой промежуточных итогов.|
| [update_empty_string_as_null](/cells/python-net/ru/aspose.cells/workbookdesigner/update_empty_string_as_null) |Если TRUE, будет вставлен Null, если значение равно "";|
| [update_reference](/cells/python-net/ru/aspose.cells/workbookdesigner/update_reference) | Указывает, будут ли обновлены ссылки на других листах.|
| [calculate_formula](/cells/python-net/ru/aspose.cells/workbookdesigner/calculate_formula) | Указывает, следует ли рассчитывать формулы.|
| [line_by_line](/cells/python-net/ru/aspose.cells/workbookdesigner/line_by_line) | Указывает, обрабатывается ли смарт-маркер построчно.|
| [contains_variables](/cells/python-net/ru/aspose.cells/workbookdesigner/contains_variables) | Указывает, содержит ли первый рабочий лист пользовательские переменные.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_data_source(self, data_source, cells_data_table)`](/cells/python-net/ru/aspose.cells/workbookdesigner/set_data_source/#str-icellsdatatable) |  |
| [`set_data_source(self, variable, data)`](/cells/python-net/ru/aspose.cells/workbookdesigner/set_data_source/#str-any) | Устанавливает привязку данных к переменной.|
| [`process(self, range, is_preserved)`](/cells/python-net/ru/aspose.cells/workbookdesigner/process/#aspose.cells.range-bool) | Обрабатывает интеллектуальные маркеры и заполняет значения источника данных.|
| [`process(self)`](/cells/python-net/ru/aspose.cells/workbookdesigner/process/#) | Обрабатывает интеллектуальные маркеры и заполняет значения источника данных.|
| [`process(self, is_preserved)`](/cells/python-net/ru/aspose.cells/workbookdesigner/process/#bool) | Обрабатывает интеллектуальные маркеры и заполняет значения источника данных.|
| [`process(self, sheet_index, is_preserved)`](/cells/python-net/ru/aspose.cells/workbookdesigner/process/#int-bool) | Обрабатывает интеллектуальные маркеры и заполняет значения источника данных.|
| [`clear_data_source(self)`](/cells/python-net/ru/aspose.cells/workbookdesigner/clear_data_source/#) | Очищает все источники данных.|
| [`set_json_data_source(self, variable, data)`](/cells/python-net/ru/aspose.cells/workbookdesigner/set_json_data_source/#str-str) |  |
| [`get_smart_markers(self)`](/cells/python-net/ru/aspose.cells/workbookdesigner/get_smart_markers/#) | Возвращает коллекцию смарт-маркеров в электронной таблице.|



###  Пример

```python
from aspose.cells import Workbook, WorkbookDesigner

# Create WorkbookDesigner object.
wd = WorkbookDesigner()
# Open the template file (which contains smart markers).
wd.workbook = Workbook("SmartMarker_Designer.xls")
# Initialize your data from data source
# DataSet ds = new DataSet();
# ...
# Set the datatable as the data source.
# wd.SetDataSource(dt);
# Process the smart markers to fill the data into the worksheets.
wd.process(True)
# Save the excel file.
wd.workbook.save("outSmartMarker_Designer.xls")

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`WorkbookDesigner`](/cells/python-net/ru/aspose.cells/workbookdesigner)
