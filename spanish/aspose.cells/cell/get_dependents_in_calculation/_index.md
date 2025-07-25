---
title: método get_dependents_in_calculation
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 100
url: /es/aspose.cells/cell/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, recursive) {#bool}
Obtiene todas las celdas cuyo resultado calculado depende de esta celda.


###  Devoluciones

Enumerador para enumerar todos los dependientes (Cell objetos)


```python

def get_dependents_in_calculation(self, recursive):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| recursive | bool | Si devuelve aquellos dependientes que no hacen referencia a esta celda directamente<br/> pero referencia a otras hojas de esta celda|
###  Observaciones

Para utilizar este método, asegúrese de que el libro de trabajo se haya configurado con el valor verdadero para
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/es/aspose.cells/formulasettings#enable_calculation_chain) y se ha calculado completamente con esta configuración.
Si no hay ninguna referencia de fórmula a esta celda, se devolverá nulo.
###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("B1").get_dependents_in_calculation(False)
print("B1's calculation dependents:")
for c in en:
    print(c.name)
en = cells.get("B2").get_dependents_in_calculation(False)
print("B2's calculation dependents:")
for c in en:
    print(c.name)

```



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
