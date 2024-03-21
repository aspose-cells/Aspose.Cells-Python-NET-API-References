---
title: CalculationOptions класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 130
url: /ru/aspose.cells/calculationoptions/
is_root: false
---
##  CalculationOptions класс
Представляет параметры для расчета.



Тип CalculationOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/calculationoptions/__init__/#) | Создает новый экземпляр CalculationOptions.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [ignore_error](/cells/python-net/ru/aspose.cells/calculationoptions/ignore_error) | Указывает, следует ли игнорировать ошибки, возникшие при вычислении формул.<br/>Ошибка может быть в неподдерживаемой функции, внешних ссылках и т. д.<br/> Значение по умолчанию верно.|
| [recursive](/cells/python-net/ru/aspose.cells/calculationoptions/recursive) | Указывает, нужно ли вычислять зависимые ячейки рекурсивно при вычислении одной ячейки и зависимости от других ячеек.<br/> Значение по умолчанию верно.|
| [custom_engine](/cells/python-net/ru/aspose.cells/calculationoptions/custom_engine) | Пользовательский механизм расчета формул, расширяющий механизм вычислений по умолчанию Aspose.Cells.|
| [calculation_monitor](/cells/python-net/ru/aspose.cells/calculationoptions/calculation_monitor) | Монитор, позволяющий пользователю отслеживать ход расчета формулы.|
| [calc_stack_size](/cells/python-net/ru/aspose.cells/calculationoptions/calc_stack_size) | Размер стека для рекурсивного вычисления ячеек. Значение по умолчанию — 200.|
| [precision_strategy](/cells/python-net/ru/aspose.cells/calculationoptions/precision_strategy) | Указывает стратегию обработки точности вычислений.|
| [linked_data_sources](/cells/python-net/ru/aspose.cells/calculationoptions/linked_data_sources) | Указывает источники данных для внешних ссылок, используемых в формулах.|
| [character_encoding](/cells/python-net/ru/aspose.cells/calculationoptions/character_encoding) | Указывает кодировку, используемую для кодирования/декодирования символов при вычислении формул.<br/>Для таких функций, как CHAR, CODE, вычисленный результат зависит от настроек региона и кодировки среды по умолчанию.<br/> С помощью этого свойства пользователь может указать правильную кодировку, используемую для этой функции, чтобы получить ожидаемый результат.|



###  Смотрите также
* модуль [`aspose.cells`](..)
