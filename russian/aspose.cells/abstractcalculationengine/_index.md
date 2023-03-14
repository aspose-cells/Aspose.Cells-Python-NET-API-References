---
title: AbstractCalculationEngine класс
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 20
url: /ru/aspose.cells/abstractcalculationengine/
is_root: false
---
##  AbstractCalculationEngine класс
Представляет пользовательский механизм вычислений для расширения механизма вычислений по умолчанию Aspose.Cells.



Тип AbstractCalculationEngine предоставляет следующие члены:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_param_literal_required](/cells/python-net/ru/aspose.cells/abstractcalculationengine/is_param_literal_required) | Указывает, нужен ли этому движку буквальный текст параметра при выполнении вычислений. Значение по умолчанию — ложь.|
| [process_built_in_functions](/cells/python-net/ru/aspose.cells/abstractcalculationengine/process_built_in_functions) | Должны ли встроенные функции, поддерживаемые встроенным механизмом, проверяться и обрабатываться этой реализацией.<br/>Значение по умолчанию — ложь.<br/> Если пользователю необходимо изменить логику расчета некоторых встроенных функций, это свойство должно быть установлено как true.|


###  Методы
| Метод| Описание|
| :- | :- |
| [calculate(data)](/cells/python-net/ru/aspose.cells/abstractcalculationengine/calculate/#CalculationData) | Вычисляет одну функцию с заданными данными.|



###  Примечания

Пользователь не должен изменять какую-либо часть рабочей книги непосредственно в этой реализации (кроме вычисляемого результата пользовательской функции, который можно задать с помощью свойства CalculationData.CalculatedValue).
В противном случае может быть вызван неожиданный результат или исключение.
Если пользователю необходимо изменить данные, отличные от расчетных, при реализации некоторых пользовательских функций,
например, изменить формулу ячейки, стиль и т. д., пользователь должен собрать эти данные в этой реализации и изменить их вне области расчета формулы.

###  Смотрите также
* модуль [aspose.cells](..)
