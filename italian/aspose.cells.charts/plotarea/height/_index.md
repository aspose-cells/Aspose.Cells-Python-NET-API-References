---
title: height proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 180
url: /it/aspose.cells.charts/plotarea/height/
is_root: false
---
##  height proprietà

Ottiene o imposta il valore height del riquadro di delimitazione dell'area del grafico in unità di 1/4000 dell'area del grafico.

###  Osservazioni

Il riquadro di delimitazione dell'area del tracciato include l'area del tracciato, i segni di spunta (etichette di spunta) e un piccolo bordo attorno ai segni di spunta.
 Se il valore non viene creato da MS Excel, chiamare il metodo Chart.Calculate() prima di chiamare questo metodo.


 IL**X** , **Y** , **Larghezza** E**Altezza** Di**Area del lotto** rappresenta l'area del lotto
 riquadro di delimitazione che comprende l'area del grafico, i segni di spunta (etichette di spunta) e un piccolo bordo attorno ai segni di spunta.
 Se vuoi ottenere la dimensione effettiva dell'area del grafico, dovresti chiamare**RapportoXInternoSuGrafico** , **RapportoYInternoSuGrafico** , **Rapporto larghezza interna rispetto al grafico** E
**Rapporto altezza interna rispetto al grafico** proprietà.


Per Excel 2007 o versioni successive, il valore predefinito è zero. Dovresti chiamare il metodo get dopo aver chiamato Chart.Calculate().
###  Definizione:
```python
@property
def height(self):
    ...
@height.setter
def height(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.charts`](../../)
* classe [`PlotArea`](/cells/python-net/it/aspose.cells.charts/plotarea)
