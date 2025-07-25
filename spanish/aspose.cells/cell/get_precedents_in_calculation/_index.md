---
title: método get_precedents_in_calculation
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 190
url: /es/aspose.cells/cell/get_precedents_in_calculation/
is_root: false
---
##  get_precedents_in_calculation(self) {#}
Obtiene todos los precedentes (referencias a las celdas en el libro actual) utilizados por la fórmula de esta celda al calcularla.


###  Devoluciones

Enumerador para enumerar todas las referencias (ReferredArea)


```python

def get_precedents_in_calculation(self):
    ...
```


###  Observaciones

Este método sólo puede funcionar en la situación [`FormulaSettings.enable_calculation_chain`](/cells/python-net/es/aspose.cells/formulasettings#enable_calculation_chain)
es verdadero para el libro de trabajo y el libro de trabajo ha sido calculado completamente.
Si esta celda no es una fórmula o no hace referencia a ninguna otra celda, se devolverá nulo.
###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("A2").get_precedents_in_calculation()
print("A2's calculation precedents:")
for r in en:
    print(r)

```



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
