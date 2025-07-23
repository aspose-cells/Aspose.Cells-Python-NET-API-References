---
title: método is_chart_data_changed
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells.charts/chart/is_chart_data_changed/
is_root: false
---
##  is_chart_data_changed(self) {#}
Detecta si la fuente de datos de un gráfico ha cambiado.


###  Devoluciones

Devuelve verdadero si el gráfico ha cambiado; de lo contrario, devuelve falso.


```python

def is_chart_data_changed(self):
    ...
```


###  Observaciones

El método detecta los cambios en la fuente de datos del gráfico antes de representar el gráfico en formato de imagen.
En la primera llamada a Chart.toImage, se registrarán los datos de origen del gráfico (por ejemplo, XValuesParseData, ValuesParseData).
Antes de llamar nuevamente al método Chart.toImage, llame al método IsChartDataChanged para verificar si es necesario volver a renderizar el gráfico.


###  Ver también
* módulo [`aspose.cells.charts`](../../)
* clase [`Chart`](/cells/python-net/es/aspose.cells.charts/chart)
