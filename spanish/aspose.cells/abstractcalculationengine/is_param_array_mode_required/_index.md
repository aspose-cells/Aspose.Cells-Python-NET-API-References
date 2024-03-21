---
title: is_param_array_mode_required propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---
##  is_param_array_mode_required propiedad

Indica si este motor necesita que el parámetro se calcule en modo matriz. El valor predeterminado es falso.
Si se requiere [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/es/aspose.cells/calculationdata/get_param_value_in_array_mode) al calcular el valor personalizado
funciones y el usuario no ha actualizado la definición para ellas
(por [`Workbook.update_custom_function_definition`](/cells/python-net/es/aspose.cells/workbook/update_custom_function_definition)),
esta propiedad debe establecerse como verdadera.

###  Observaciones

Si este motor de cálculo personalizado necesita que el parámetro se calcule en modo matriz,
Se necesitarán más pilas para almacenar en caché el árbol para los parámetros.
y el método Calculate() se puede llamar de forma recursiva para calcular el valor del parámetro.
Para considerar el rendimiento, mantenga esta propiedad como valor predeterminado (falso)
si no hay ningún requisito especial.
###  Definición:
```python
@property
def is_param_array_mode_required(self):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`AbstractCalculationEngine`](/cells/python-net/es/aspose.cells/abstractcalculationengine)
