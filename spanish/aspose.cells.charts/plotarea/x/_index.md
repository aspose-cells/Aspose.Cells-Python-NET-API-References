---
title: x propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 390
url: /es/aspose.cells.charts/plotarea/x/
is_root: false
---
##  x propiedad

Obtiene u obtiene la coordenada x de la esquina superior izquierda del cuadro delimitador del área del gráfico en unidades de 1/4000 del área del gráfico.

###  Observaciones

El cuadro delimitador del área de trazado incluye el área de trazado, marcas de verificación (etiquetas de verificación) y un pequeño borde alrededor de las marcas de verificación.
 Si MS Excel no crea el valor, llame al método Chart.Calculate() antes de llamar a este método.


 El**X**, **Y** , **Ancho** y**Altura** de**Área de la parcela** representa el área de la parcela
 cuadro delimitador que incluye el área de trazado, marcas de verificación (etiquetas de verificación) y un pequeño borde alrededor de las marcas de verificación.
 Si desea obtener el tamaño real del área de la parcela, debe llamar**RelaciónX interna al gráfico** , **Relación Y interna con el gráfico** , **RelaciónAnchoInteriorAlGráfico** y
**Relación de altura interior al gráfico** propiedades.


Para Excel 2007 o posterior, el valor predeterminado es cero. Debe llamar a obtener el valor después de llamar a Chart.Calculate().
###  Definición:
```python
@property
def x(self):
    ...
@x.setter
def x(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.charts`](../../)
* clase [`PlotArea`](/cells/python-net/es/aspose.cells.charts/plotarea)
