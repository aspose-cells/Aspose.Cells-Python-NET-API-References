---
title: CalculationOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 100
url: /ru/aspose.cells/calculationoptions/
is_root: false
---
##  CalculationOptions класс
Представляет собой варианты для расчета.



Тип CalculationOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/calculationoptions/__init__/#) | Создает новый экземпляр CalculationOptions|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [ignore_error](/cells/python-net/ru/aspose.cells/calculationoptions/ignore_error) | Указывает, следует ли игнорировать ошибки, возникающие при расчете формул.<br/>Ошибка может быть связана с неподдерживаемой функцией, внешними ссылками и т. д.<br/> Значение по умолчанию — true.|
| [recursive](/cells/python-net/ru/aspose.cells/calculationoptions/recursive) | Указывает, следует ли рекурсивно вычислять зависимые ячейки, если вычисление одной ячейки зависит от других ячеек.<br/> Значение по умолчанию — true.|
| [calc_stack_size](/cells/python-net/ru/aspose.cells/calculationoptions/calc_stack_size) | Размер стека для рекурсивного вычисления ячеек. Значение по умолчанию — 200.|
| [precision_strategy](/cells/python-net/ru/aspose.cells/calculationoptions/precision_strategy) | Задает стратегию обработки точности расчетов.|
| [linked_data_sources](/cells/python-net/ru/aspose.cells/calculationoptions/linked_data_sources) | Указывает источники данных для внешних ссылок, используемых в формулах.|
| [character_encoding](/cells/python-net/ru/aspose.cells/calculationoptions/character_encoding) | Указывает кодировку, используемую для кодирования/декодирования символов при вычислении формул.<br/>Для таких функций, как CHAR, CODE, рассчитанный результат зависит от настроек региона и кодировки среды по умолчанию.<br/>С помощью этого свойства пользователь может указать правильную кодировку, используемую для этих функций, чтобы получить ожидаемый результат.|



###  Смотрите также
* модуль [`aspose.cells`](..)
