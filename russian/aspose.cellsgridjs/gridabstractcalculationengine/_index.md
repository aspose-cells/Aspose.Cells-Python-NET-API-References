---
title: GridAbstractCalculationEngine класс
second_title: Aspose.Cells.GridJs for Python via .NET API
description:
type: docs
weight: 20
url: /ru/aspose.cellsgridjs/gridabstractcalculationengine/
is_root: false
---
##  GridAbstractCalculationEngine класс

Представляет пользовательский механизм вычислений, расширяющий механизм вычислений по умолчанию Aspose.Cells.



Тип GridAbstractCalculationEngine предоставляет следующие элементы:

###  Методы
| Метод| Описание|
| :- | :- |
| [calculate](/cells/python-net/ru/aspose.cellsgridjs/gridabstractcalculationengine/calculate/#aspose.cellsgridjs.GridCalculationData) | Вычисляет одну функцию с заданными данными.|



###  Примечания


Пользователь не должен изменять какую-либо часть книги непосредственно в этой реализации (кроме вычисленного результата пользовательской функции, который может быть установлен свойством GridCalculationData.CalculatedValue).
В противном случае может возникнуть непредвиденный результат или исключение.
Если пользователю необходимо изменить данные, отличные от рассчитанного результата, при реализации некоторых пользовательских функций,
Например, измените формулу, стиль и т. д. ячейки, пользователь должен собрать эти данные в этой реализации и изменить их за пределами расчета формулы.

###  Смотрите также
* модуль [`aspose.cellsgridjs`](..)
