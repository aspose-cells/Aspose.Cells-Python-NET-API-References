---
title: height fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 140
url: /sv/aspose.cells.charts/plotarea/height/
is_root: false
---
##  height fastighet

Hämtar eller ställer in height för plot-area avgränsningsruta i enheter på 1/4000 av sjökortsytan.

###  Anmärkningar

Avgränsningsrutan för plottarea inkluderar tomtområdet, bockmarkeringar (tick-etiketter) och en liten ram runt bockmarkeringarna.
 Om värdet inte skapas av MS Excel, anropa metoden Chart.Calculate() innan du anropar den här metoden.


 De**X** , **Y** , **Bredd** och**Höjd** av**PlotArea** representerar tomtområdet
 begränsningsruta som inkluderar tomtområdet, bockmarkeringar (tick-etiketter) och en liten kant runt bockmarkeringarna.
 Vill du få verklig storlek på tomtarea ska du ringa**InnerX** , **InreY** , **InnerWidth** och
**Innerhöjd** egenskaper.


För excel 2007 eller senare är standardvärdet noll. du bör anropa få värdet efter att ha anropat Chart.Calculate().
###  Definition:
```python
@property
def height(self):
    ...
@height.setter
def height(self, value):
    ...
```

###  Se även
* modul [aspose.cells.charts](../../)
* klass [PlotArea](/cells/python-net/sv/aspose.cells.charts/plotarea)
