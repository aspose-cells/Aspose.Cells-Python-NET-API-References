---
title: calculated_value propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells/calculationdata/calculated_value/
is_root: false
---
##  calculated_value propiedad

Obtiene o establece el valor calculado para esta función.

###  Observaciones

El usuario debe establecer esta propiedad en su motor de cálculo personalizado para aquellas funciones que admite el motor.
y el valor establecido se devolverá cuando se obtenga esta propiedad más adelante.
El valor establecido puede ser de posibles tipos de [`Cell.value`](/cells/python-net/es/aspose.cells/cell#value),
o matriz de ese tipo de valores, o un Rango, Nombre, Área Referenciada.
Obtener esta propiedad antes de establecerle un valor hará que la función se calcule
por el motor de cálculo predeterminado de Aspose.Cells y luego el valor calculado
ser devuelto (generalmente debería ser #¿NOMBRE? para funciones definidas por el usuario).
###  Definición:
```python
@property
def calculated_value(self):
    ...
@calculated_value.setter
def calculated_value(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CalculationData`](/cells/python-net/es/aspose.cells/calculationdata)
