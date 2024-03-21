---
title: método get_dependents_in_calculation
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 370
url: /es/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation {#int-int-bool}
Obtiene todas las celdas cuyo resultado calculado depende de una celda específica.


###  Devoluciones

Enumerador para enumerar todos los dependientes (Cell objetos)


```python
def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row | int | Índice de fila de la celda específica|
| column | int | Índice de columna de la celda específica.|
| recursive | bool | Si devuelve aquellos dependientes que no hacen referencia directamente a la celda específica<br/> pero referencia a otras hojas de esa celda.|
###  Observaciones

Para utilizar este método, asegúrese de que el libro de trabajo se haya configurado con el valor verdadero para
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/es/aspose.cells/formulasettings#enable_calculation_chain) y se ha calculado completamente con esta configuración.
Si no hay ninguna referencia de fórmula a esta celda, se devolverá nulo.
Para obtener más detalles y ejemplos, consulte [`Cell.get_dependents_in_calculation`](/cells/python-net/es/aspose.cells/cell/get_dependents_in_calculation)


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
