---
title: inner_height_ratio_to_chart propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 220
url: /es/aspose.cells.charts/plotarea/inner_height_ratio_to_chart/
is_root: false
---
##  inner_height_ratio_to_chart propiedad

Obtiene o establece la altura del área del gráfico en unidades de proporción del área del gráfico.

###  Observaciones

El cuadro delimitador del área de trazado incluye el área de trazado, marcas de verificación (etiquetas de verificación) y un pequeño borde alrededor de las marcas de verificación.
 Si MS Excel no crea el valor, llame al método Chart.Calculate() antes de llamar a este método.


 El**XRatioToChart** , **YRatioToChart** , **Relación de ancho al gráfico** y**Relación de altura con el gráfico** de**Área de la parcela** representa el área de la parcela
 cuadro delimitador que incluye el área de trazado, marcas de verificación (etiquetas de verificación) y un pequeño borde alrededor de las marcas de verificación.
 Si desea obtener el tamaño real del área de la parcela, debe llamar**RelaciónX interna al gráfico** , **Relación Y interna con el gráfico** , **RelaciónAnchoInteriorAlGráfico** y
**Relación de altura interior al gráfico** propiedades.


Para Excel 2007 o posterior, el valor predeterminado es cero. Debe llamar a obtener el valor después de llamar a Chart.Calculate().

 
InnerHeight en píxeles = InnerXRatioToChart * chart.ChartObject.Width.
###  Definición:
```python
@property
def inner_height_ratio_to_chart(self):
    ...
@inner_height_ratio_to_chart.setter
def inner_height_ratio_to_chart(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.charts`](../../)
* clase [`PlotArea`](/cells/python-net/es/aspose.cells.charts/plotarea)
