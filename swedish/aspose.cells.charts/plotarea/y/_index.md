---
title: y fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 420
url: /sv/aspose.cells.charts/plotarea/y/
is_root: false
---
##  y fastighet

Hämtar eller hämtar y-koordinaten för det övre hörnet av plotarea-begränsningsramen i enheter om 1/4000 av diagramarean.

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
def y(self):
    ...
@y.setter
def y(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.charts`](../../)
* klass [`PlotArea`](/cells/python-net/sv/aspose.cells.charts/plotarea)
