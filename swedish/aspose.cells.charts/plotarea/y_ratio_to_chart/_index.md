---
title: y_ratio_to_chart fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 440
url: /sv/aspose.cells.charts/plotarea/y_ratio_to_chart/
is_root: false
---
##  y_ratio_to_chart fastighet

Hämtar eller hämtar y-koordinaten för det övre hörnet av begränsningsrutan för plotarea i enheter som motsvarar diagramarean.

###  Anmärkningar

Avgränsningsrutan för plottområdet inkluderar plottområdet, skalmarkeringar (skaketiketter) och en liten ram runt skalmarkeringarna.
 Om värdet inte skapas av MS Excel, anropa metoden Chart.Calculate() innan du anropar den här metoden.


 De**XRatioToDiagram** , **Y-förhållande till diagram** , **BreddförhållandeTillDiagram** och**HöjdförhållandeTillDiagram** av**Tomtområde** representerar plot-arean
 en avgränsningsruta som inkluderar ritområdet, skalstreck (skaketiketter) och en liten ram runt skalstrecken.
 Om du vill få den faktiska storleken på tomtytan bör du ringa**InnerXRatioToDiagram** , **InnerY-förhållandeTillDiagram** , **InnerbreddförhållandeTillDiagram** och
**InnerhöjdförhållandeTillDiagram** egenskaper.


För Excel 2007 eller senare är standardvärdet noll. Du bör anropa `get the value` efter att ha anropat Chart.Calculate().

 
YPixel = YRatioTillDiagram * diagram.DiagramObjekt.Bredd.
###  Definition:
```python
@property
def y_ratio_to_chart(self):
    ...
@y_ratio_to_chart.setter
def y_ratio_to_chart(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.charts`](../../)
* klass [`PlotArea`](/cells/python-net/sv/aspose.cells.charts/plotarea)
