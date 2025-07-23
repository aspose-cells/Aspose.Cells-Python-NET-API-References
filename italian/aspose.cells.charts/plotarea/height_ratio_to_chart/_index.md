---
title: height_ratio_to_chart proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 200
url: /it/aspose.cells.charts/plotarea/height_ratio_to_chart/
is_root: false
---
##  height_ratio_to_chart proprietà

Ottiene o imposta l'altezza del riquadro di delimitazione dell'area del grafico in unità di rapporto dell'area del grafico.

###  Osservazioni

Il riquadro di delimitazione dell'area del tracciato include l'area del tracciato, i segni di spunta (etichette di spunta) e un piccolo bordo attorno ai segni di spunta.
 Se il valore non viene creato da MS Excel, chiamare il metodo Chart.Calculate() prima di chiamare questo metodo.


 IL**XRatioToChart** , **RapportoY su grafico** , **Rapporto larghezza-grafico** E**Rapporto altezza-grafico** Di**Area del lotto** rappresenta l'area del lotto
 riquadro di delimitazione che comprende l'area del grafico, i segni di spunta (etichette di spunta) e un piccolo bordo attorno ai segni di spunta.
 Se vuoi ottenere la dimensione effettiva dell'area del grafico, dovresti chiamare**RapportoXInternoSuGrafico** , **RapportoYInternoSuGrafico** , **Rapporto larghezza interna rispetto al grafico** E
**Rapporto altezza interna rispetto al grafico** proprietà.


Per Excel 2007 o versioni successive, il valore predefinito è zero. Dovresti chiamare il metodo get dopo aver chiamato Chart.Calculate().

 
HeightPixel = HeightRatioToChart * chart.ChartObject.Width.
###  Definizione:
```python
@property
def height_ratio_to_chart(self):
    ...
@height_ratio_to_chart.setter
def height_ratio_to_chart(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.charts`](../../)
* classe [`PlotArea`](/cells/python-net/it/aspose.cells.charts/plotarea)
