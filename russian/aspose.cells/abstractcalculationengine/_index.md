---
title: AbstractCalculationEngine класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 20
url: /ru/aspose.cells/abstractcalculationengine/
is_root: false
---
##  AbstractCalculationEngine класс
Представляет пользовательский механизм вычислений, расширяющий механизм вычислений по умолчанию Aspose.Cells.



Тип AbstractCalculationEngine предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_param_literal_required](/cells/python-net/ru/aspose.cells/abstractcalculationengine/is_param_literal_required) |Указывает, нужен ли этому механизму буквальный текст параметра при выполнении вычислений. Значение по умолчанию — ложь.|
| [is_param_array_mode_required](/cells/python-net/ru/aspose.cells/abstractcalculationengine/is_param_array_mode_required) | Указывает, нужен ли этому механизму параметр для вычисления в режиме массива. Значение по умолчанию — ложь.<br/>Если [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/ru/aspose.cells/calculationdata/get_param_value_in_array_mode) требуется при расчете пользовательских<br/>функции, и пользователь не обновил их определение<br/>(по номеру [`Workbook.update_custom_function_definition`](/cells/python-net/ru/aspose.cells/workbook/update_custom_function_definition)),<br/> это свойство должно быть установлено как true.|
| [process_built_in_functions](/cells/python-net/ru/aspose.cells/abstractcalculationengine/process_built_in_functions) | Поддерживаются ли встроенные функции встроенным движком<br/>должны быть проверены и обработаны этой реализацией.<br/> По умолчанию — ложь.|


###  Методы
| Метод| Описание|
| :- | :- |
| [calculate](/cells/python-net/ru/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) | Вычисляет одну функцию с заданными данными.|



###  Примечания

Пользователь не должен изменять какую-либо часть книги непосредственно в этой реализации (кроме
вычисленный результат пользовательской функции, который можно задать свойством CalculationData.CalculatedValue).
В противном случае может возникнуть непредвиденный результат или исключение.
Если пользователю необходимо изменить данные, отличные от рассчитанного результата, при реализации некоторых пользовательских функций,
например, изменить формулу ячейки, стиль и т. д., пользователь должен собрать эти данные в этой реализации.
и измените их за пределами расчета формулы.

###  Смотрите также
* модуль [`aspose.cells`](..)
