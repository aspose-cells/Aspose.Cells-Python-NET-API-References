---
title: is_param_array_mode_required недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 40
url: /ru/aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---
##  is_param_array_mode_required недвижимость

Указывает, нужен ли этому механизму параметр для вычисления в режиме массива. Значение по умолчанию — ложь.
Если [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/ru/aspose.cells/calculationdata/get_param_value_in_array_mode) требуется при расчете пользовательских
функции, и пользователь не обновил их определение
(по номеру [`Workbook.update_custom_function_definition`](/cells/python-net/ru/aspose.cells/workbook/update_custom_function_definition)),
это свойство должно быть установлено как true.

###  Примечания

Если этому пользовательскому механизму вычислений требуется, чтобы параметр вычислялся в режиме массива,
для кэширования дерева параметров потребуется больше стеков
и метод Calculate() можно вызывать рекурсивно для вычисления значения параметра.
Из соображений производительности оставьте для этого свойства значение по умолчанию (false).
если нет особых требований.
###  Определение:
```python
@property
def is_param_array_mode_required(self):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`AbstractCalculationEngine`](/cells/python-net/ru/aspose.cells/abstractcalculationengine)
