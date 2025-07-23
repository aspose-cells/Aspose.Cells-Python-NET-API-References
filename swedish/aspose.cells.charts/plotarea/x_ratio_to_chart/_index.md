---
title: x_ratio_to_chart fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 410
url: /sv/aspose.cells.charts/plotarea/x_ratio_to_chart/
is_root: false
---
##  x_ratio_to_chart fastighet

Hämtar eller hämtar x-koordinaten för det övre vänstra hörnet av avgränsningsrutan för plottarea i enheter som motsvarar diagramarean.

###  Anmärkningar

Avgränsningsrutan för plottområdet inkluderar plottområdet, skalmarkeringar (skaketiketter) och en liten ram runt skalmarkeringarna.
 Om värdet inte skapas av MS Excel, anropa metoden Chart.Calculate() innan du anropar den här metoden.


 De**XRatioToDiagram** , **Y-förhållande till diagram** , **BreddförhållandeTillDiagram** och**HöjdförhållandeTillDiagram** av**Tomtområde** representerar plot-arean
 en avgränsningsruta som inkluderar ritområdet, skalstreck (skaketiketter) och en liten ram runt skalstrecken.
 Om du vill få den faktiska storleken på tomtytan bör du ringa**InnerXRatioToDiagram** , **InnerY-förhållandeTillDiagram** , **InnerbreddförhållandeTillDiagram** och
**InnerhöjdförhållandeTillDiagram** egenskaper.


För Excel 2007 eller senare är standardvärdet noll. Du bör anropa `get the value` efter att ha anropat Chart.Calculate().

 
XPixel = XRatioToChart * diagram.DiagramObjekt.Bredd.
###  Definition:
```python
@property
def x_ratio_to_chart(self):
    ...
@x_ratio_to_chart.setter
def x_ratio_to_chart(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.charts`](../../)
* klass [`PlotArea`](/cells/python-net/sv/aspose.cells.charts/plotarea)
