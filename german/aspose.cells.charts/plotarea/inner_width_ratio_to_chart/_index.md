---
title: inner_width_ratio_to_chart Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 240
url: /de/aspose.cells.charts/plotarea/inner_width_ratio_to_chart/
is_root: false
---
##  inner_width_ratio_to_chart Eigentum

Ruft die Breite des Zeichnungsbereichs in Einheiten des Verhältnisses zum Diagrammbereich ab oder legt sie fest.

###  Bemerkungen

Der Begrenzungsrahmen des Plotbereichs umfasst den Plotbereich, Teilstriche (Teilstrichbeschriftungen) und einen kleinen Rahmen um die Teilstriche.
 Wenn der Wert nicht von MS Excel erstellt wird, rufen Sie bitte die Methode Chart.Calculate() auf, bevor Sie diese Methode aufrufen.


 Der**XRatioToChart** , **YRatioToChart** , **Breitenverhältnis zum Diagramm** Und**Höhenverhältnis zum Diagramm** von**Grundstücksfläche** stellt die Grundstücksfläche dar
 Begrenzungsrahmen, der den Plotbereich, Teilstriche (Teilstrichbeschriftungen) und einen kleinen Rahmen um die Teilstriche enthält.
 Wenn Sie die tatsächliche Größe der Grundstücksfläche erfahren möchten, rufen Sie an**InnerXRatioToChart** , **InneresJahresverhältnisZumDiagramm** , **Verhältnis der inneren Breite zum Diagramm** Und
**Verhältnis der inneren Höhe zum Diagramm** Eigenschaften.


Für Excel 2007 oder höher ist der Standardwert Null. Sie sollten den Wert abrufen, nachdem Sie Chart.Calculate() aufgerufen haben.

 
InnerWidth in Pixel = InnerXRatioToChart * chart.ChartObject.Width.
###  Definition:
```python
@property
def inner_width_ratio_to_chart(self):
    ...
@inner_width_ratio_to_chart.setter
def inner_width_ratio_to_chart(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.charts`](../../)
* Klasse [`PlotArea`](/cells/python-net/de/aspose.cells.charts/plotarea)
