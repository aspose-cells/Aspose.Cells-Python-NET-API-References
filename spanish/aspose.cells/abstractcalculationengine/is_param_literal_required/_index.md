---
title: is_param_literal_required propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 50
url: /es/aspose.cells/abstractcalculationengine/is_param_literal_required/
is_root: false
---
##  is_param_literal_required propiedad

Indica si este motor necesita el texto literal del parámetro mientras realiza el cálculo. El valor predeterminado es falso.

###  Observaciones

Si este motor de cálculo personalizado necesita el texto literal del parámetro,
Se necesitarán más pilas para almacenar en caché el texto literal de los parámetros.
y el método Calculate() se puede llamar de forma recursiva para calcular el valor del parámetro.
Generalmente el texto literal no es necesario para calcular fórmulas.
y esta propiedad debe mantenerse como falsa en la mayoría de las implementaciones para obtener un mejor rendimiento.
###  Definición:
```python
@property
def is_param_literal_required(self):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`AbstractCalculationEngine`](/cells/python-net/es/aspose.cells/abstractcalculationengine)
