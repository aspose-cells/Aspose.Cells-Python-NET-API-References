---
title: método refresh_dynamic_array_formulas
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 270
url: /es/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas {#bool}
Actualiza las fórmulas de matriz dinámica (se extiende a un nuevo rango de celdas vecinas según los datos actuales)
Otras fórmulas del libro de trabajo no se calcularán de forma recursiva incluso si fueron utilizadas por fórmulas de matriz dinámica.



```python
def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| calculate | bool | Si calcula y actualiza los valores de celda para esas fórmulas de matriz dinámica|


##  refresh_dynamic_array_formulas {#bool-aspose.cells.CalculationOptions}
Actualiza las fórmulas de matriz dinámica (se extiende a un nuevo rango de celdas vecinas según los datos actuales)



```python
def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| calculate | bool | Si calcula y actualiza los valores de celda para esas fórmulas de matriz dinámica|
| copts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Las opciones para calcular fórmulas.|
###  Observaciones

Por consideraciones de rendimiento, no actualizamos todas las fórmulas de matriz dinámica automáticamente
cuando la fórmula en sí o los datos a los que hace referencia cambiaron.
Por lo tanto, el usuario debe llamar a este método manualmente después de aquellas operaciones que pueden influir en las fórmulas de matriz dinámica.
como importar/configurar valores de celda, insertar/eliminar filas/columnas/rangos, etc.

Para la mayoría de las fórmulas con funciones, para calcular el rango de derrame también es necesario calcular la fórmula.
por lo que, en general, se prefiere el valor verdadero para el indicador "calcular".
Si la fórmula es simple, como una referencia de rango o una matriz (por ejemplo "=C1:E5", "={1,2;3,4}", ...),
función simple en un rango o matriz (por ejemplo "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
y todas las fórmulas se calcularán más tarde (como por [`Workbook.calculate_formula`](/cells/python-net/es/aspose.cells/workbook/calculate_formula)),
luego, utilizar un valor falso para el indicador "calcular" puede evitar el cálculo duplicado en beneficio del rendimiento.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
