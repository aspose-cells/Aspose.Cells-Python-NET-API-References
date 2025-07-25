---
title: x_ratio_to_chart Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 410
url: /de/aspose.cells.charts/plotarea/x_ratio_to_chart/
is_root: false
---
##  x_ratio_to_chart Eigentum

Ruft die x-Koordinate der oberen linken Ecke des Begrenzungsrahmens des Plotbereichs in Einheiten des Verhältnisses des Diagrammbereichs ab.

###  Bemerkungen

Der Begrenzungsrahmen des Plotbereichs umfasst den Plotbereich, Teilstriche (Teilstrichbeschriftungen) und einen kleinen Rahmen um die Teilstriche.
 Wenn der Wert nicht von MS Excel erstellt wird, rufen Sie bitte die Methode Chart.Calculate() auf, bevor Sie diese Methode aufrufen.


 Der**XRatioToChart** , **YRatioToChart** , **Breitenverhältnis zum Diagramm** Und**Höhenverhältnis zum Diagramm** von**Grundstücksfläche** stellt die Grundstücksfläche dar
 Begrenzungsrahmen, der den Plotbereich, Teilstriche (Teilstrichbeschriftungen) und einen kleinen Rahmen um die Teilstriche enthält.
 Wenn Sie die tatsächliche Größe der Grundstücksfläche erfahren möchten, rufen Sie an**InnerXRatioToChart** , **InneresJahresverhältnisZumDiagramm** , **Verhältnis der inneren Breite zum Diagramm** Und
**Verhältnis der inneren Höhe zum Diagramm** Eigenschaften.


Für Excel 2007 oder höher ist der Standardwert Null. Sie sollten den Wert abrufen, nachdem Sie Chart.Calculate() aufgerufen haben.

 
XPixel = XRatioToChart * chart.ChartObject.Width.
###  Definition:
```python
@property
def x_ratio_to_chart(self):
    ...
@x_ratio_to_chart.setter
def x_ratio_to_chart(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.charts`](../../)
* Klasse [`PlotArea`](/cells/python-net/de/aspose.cells.charts/plotarea)
