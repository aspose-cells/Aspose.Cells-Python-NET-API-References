---
title: método on_circular
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/abstractcalculationmonitor/on_circular/
is_root: false
---
##  on_circular {#collections.abc.Iterator}
Implemente este método para hacer negocios al calcular fórmulas con referencias circulares.


###  Devoluciones

Si el motor de fórmulas necesita calcular esas celdas en forma circular después de esta llamada.
True para permitir que el motor de fórmulas continúe haciendo cálculos por ellos.
Falso para permitir que el motor de fórmulas simplemente marque esas celdas como Calculadas.


```python
def on_circular(self, circular_cells_data):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| circular_cells_data | collections.abc.Iterator | IEnumerator con [`CalculationCell`](/cells/python-net/es/aspose.cells/calculationcell) elementos que representan celdas que<br/> dependen de referencias circulares.|
###  Observaciones

En la implementación, el usuario también puede establecer el valor esperado como resultado calculado.
para parte/todas esas celdas para que el motor de fórmulas no las calcule de forma recursiva.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`AbstractCalculationMonitor`](/cells/python-net/es/aspose.cells/abstractcalculationmonitor)
* clase [`CalculationCell`](/cells/python-net/es/aspose.cells/calculationcell)
