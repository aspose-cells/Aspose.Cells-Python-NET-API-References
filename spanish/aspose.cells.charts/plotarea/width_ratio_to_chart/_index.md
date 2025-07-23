---
title: width_ratio_to_chart propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 380
url: /es/aspose.cells.charts/plotarea/width_ratio_to_chart/
is_root: false
---
##  width_ratio_to_chart propiedad

Obtiene o establece el ancho del cuadro delimitador del área del gráfico en unidades de relación con el área del gráfico.

###  Observaciones

El cuadro delimitador del área de trazado incluye el área de trazado, marcas de verificación (etiquetas de verificación) y un pequeño borde alrededor de las marcas de verificación.
 Si MS Excel no crea el valor, llame al método Chart.Calculate() antes de llamar a este método.


 El**XRatioToChart** , **YRatioToChart** , **Relación de ancho al gráfico** y**Relación de altura con el gráfico** de**Área de la parcela** representa el área de la parcela
 cuadro delimitador que incluye el área de trazado, marcas de verificación (etiquetas de verificación) y un pequeño borde alrededor de las marcas de verificación.
 Si desea obtener el tamaño real del área de la parcela, debe llamar**RelaciónX interna al gráfico** , **Relación Y interna con el gráfico** , **RelaciónAnchoInteriorAlGráfico** y
**Relación de altura interior al gráfico** propiedades.


Para Excel 2007 o posterior, el valor predeterminado es cero. Debe llamar a obtener el valor después de llamar a Chart.Calculate().

 
WidthPixel = WidthRatioToChart * gráfico.ChartObject.Width.
###  Definición:
```python
@property
def width_ratio_to_chart(self):
    ...
@width_ratio_to_chart.setter
def width_ratio_to_chart(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.charts`](../../)
* clase [`PlotArea`](/cells/python-net/es/aspose.cells.charts/plotarea)
