---
title: inner_y proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 270
url: /it/aspose.cells.charts/plotarea/inner_y/
is_root: false
---
##  inner_y proprietà

Ottiene o ottiene la coordinata x dell'angolo superiore destro dell'area del grafico in unità di 1/4000 dell'area del grafico.

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
def inner_y(self):
    ...
@inner_y.setter
def inner_y(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.charts`](../../)
* classe [`PlotArea`](/cells/python-net/it/aspose.cells.charts/plotarea)
