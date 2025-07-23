---
title: y Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 420
url: /de/aspose.cells.charts/plotarea/y/
is_root: false
---
##  y Eigentum

Ruft die Koordinate y der oberen Ecke des Begrenzungsrahmens des Plotbereichs in Einheiten von 1/4000 des Diagrammbereichs ab.

###  Bemerkungen

Der Begrenzungsrahmen des Plotbereichs umfasst den Plotbereich, Teilstriche (Teilstrichbeschriftungen) und einen kleinen Rahmen um die Teilstriche.
 Wenn der Wert nicht von MS Excel erstellt wird, rufen Sie bitte die Methode Chart.Calculate() auf, bevor Sie diese Methode aufrufen.


 Der**X** , **Y** , **Breite** Und**Höhe** von**Grundstücksfläche** stellt die Grundstücksfläche dar
 Begrenzungsrahmen, der den Plotbereich, Teilstriche (Teilstrichbeschriftungen) und einen kleinen Rahmen um die Teilstriche enthält.
 Wenn Sie die tatsächliche Größe der Grundstücksfläche erfahren möchten, rufen Sie an**InnerXRatioToChart** , **InneresJahresverhältnisZumDiagramm** , **Verhältnis der inneren Breite zum Diagramm** Und
**Verhältnis der inneren Höhe zum Diagramm** Eigenschaften.


Für Excel 2007 oder höher ist der Standardwert Null. Sie sollten den Wert abrufen, nachdem Sie Chart.Calculate() aufgerufen haben.
###  Definition:
```python
@property
def y(self):
    ...
@y.setter
def y(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.charts`](../../)
* Klasse [`PlotArea`](/cells/python-net/de/aspose.cells.charts/plotarea)
