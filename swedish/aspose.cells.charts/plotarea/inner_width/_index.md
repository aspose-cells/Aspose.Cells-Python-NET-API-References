---
title: inner_width fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 230
url: /sv/aspose.cells.charts/plotarea/inner_width/
is_root: false
---
##  inner_width fastighet

Hämtar eller ställer in bredden på plottarean i enheter om 1/4000 av diagramarean.

###  Anmärkningar

Avgränsningsrutan för plottområdet inkluderar plottområdet, skalmarkeringar (skaketiketter) och en liten ram runt skalmarkeringarna.
 Om värdet inte skapas av MS Excel, anropa metoden Chart.Calculate() innan du anropar den här metoden.


 De**X**, **Y** , **Bredd** och**Höjd** av**Tomtområde** representerar plot-arean
 en avgränsningsruta som inkluderar ritområdet, skalstreck (skaketiketter) och en liten ram runt skalstrecken.
 Om du vill få den faktiska storleken på tomtytan bör du ringa**InnerXRatioToDiagram** , **InnerY-förhållandeTillDiagram** , **InnerbreddförhållandeTillDiagram** och
**InnerhöjdförhållandeTillDiagram** egenskaper.


För Excel 2007 eller senare är standardvärdet noll. Du bör anropa `get the value` efter att ha anropat Chart.Calculate().
###  Definition:
```python
@property
def inner_width(self):
    ...
@inner_width.setter
def inner_width(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.charts`](../../)
* klass [`PlotArea`](/cells/python-net/sv/aspose.cells.charts/plotarea)
