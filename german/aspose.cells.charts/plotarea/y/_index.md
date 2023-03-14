---
title: y Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 280
url: /de/aspose.cells.charts/plotarea/y/
is_root: false
---
##  y Eigentum

Ruft die Koordinate y der oberen oberen Ecke des Begrenzungsrahmens des Zeichnungsbereichs in Einheiten von 1/4000 des Diagrammbereichs ab oder ruft diese ab.

###  Bemerkungen

Der Zeichenbereich-Begrenzungsrahmen enthält den Zeichenbereich, Teilstriche (Teilstriche) und einen kleinen Rahmen um die Teilstriche.
 Wenn der Wert nicht von MS Excel erstellt wird, rufen Sie bitte die Methode Chart.Calculate() auf, bevor Sie diese Methode aufrufen.


 Der**X**, **Y** , **Breite** Und**Höhe** von**Grundstücksfläche** stellt den Grundstücksbereich dar
 Begrenzungsrahmen, der den Plotbereich, Teilstriche (Teilstriche) und einen kleinen Rahmen um die Teilstriche enthält.
 Wenn Sie die tatsächliche Größe der Grundstücksfläche erfahren möchten, sollten Sie anrufen**InnerX** , **InnerY** , **Innere Breite** Und
**InnereHöhe** Eigenschaften.


Für Excel 2007 oder höher ist der Standardwert Null. Sie sollten get the value aufrufen, nachdem Sie Chart.Calculate() aufgerufen haben.
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
* Modul [aspose.cells.charts](../../)
* Klasse [PlotArea](/cells/python-net/de/aspose.cells.charts/plotarea)
