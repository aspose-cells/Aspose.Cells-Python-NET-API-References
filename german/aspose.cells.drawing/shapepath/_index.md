---
title: ShapePath Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 540
url: /de/aspose.cells.drawing/shapepath/
is_root: false
---
##  ShapePath Klasse
Stellt einen Erstellungspfad dar, der aus einer Reihe von Bewegungen, Linien und Kurven besteht, die in ihrer Kombination eine geometrische Form ergeben.



Der Typ ShapePath macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells.drawing/shapepath/__init__/#) | Initialisiert eine neue Instanz der Klasse [`ShapePath`](/cells/python-net/de/aspose.cells.drawing/shapepath).|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [path_segement_list](/cells/python-net/de/aspose.cells.drawing/shapepath/path_segement_list) | Ruft die Liste [`ShapeSegmentPathCollection`](/cells/python-net/de/aspose.cells.drawing/shapesegmentpathcollection) ab|
| [width_pixel](/cells/python-net/de/aspose.cells.drawing/shapepath/width_pixel) | Ruft die Breite dieses Pfads in Pixeln ab.|
| [height_pixel](/cells/python-net/de/aspose.cells.drawing/shapepath/height_pixel) | Ruft die Höhe dieses Pfads in Pixeln ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`move_to(self, x, y)`](/cells/python-net/de/aspose.cells.drawing/shapepath/move_to/#float-float) |Beginnt eine neue Figur vom angegebenen Punkt aus, ohne die aktuelle Figur zu schließen. Alle nachfolgenden Punkte, die dem Pfad hinzugefügt werden, werden dieser neuen Figur hinzugefügt.|
| [`line_to(self, x, y)`](/cells/python-net/de/aspose.cells.drawing/shapepath/line_to/#float-float) | Fügt der aktuellen Abbildung ein Liniensegment hinzu.<br/> Der Startpunkt ist der Endpunkt der aktuellen Figur.|
| [`cubic_bezier_to(self, ctr_x1, ctr_y1, ctr_x2, ctr_y2, end_x, end_y)`](/cells/python-net/de/aspose.cells.drawing/shapepath/cubic_bezier_to/#float-float-float-float-float-float) | Fügt der aktuellen Figur eine kubische Bézierkurve hinzu. Der Startpunkt ist der Endpunkt der aktuellen Figur.|
| [`arc_to(self, w_r, h_r, st_ang, sw_ang)`](/cells/python-net/de/aspose.cells.drawing/shapepath/arc_to/#float-float-float-float) | Fügt der aktuellen Figur einen elliptischen Bogen hinzu. Der Startpunkt ist gleichzeitig der Endpunkt der aktuellen Figur.|
| [`close(self)`](/cells/python-net/de/aspose.cells.drawing/shapepath/close/#) | Schließt die aktuelle Figur und beginnt eine neue Figur. Enthält die aktuelle Figur eine Folge verbundener Linien und Kurven, schließt die Methode die Schleife, indem sie eine Linie vom Endpunkt zum Startpunkt verbindet.|



###  Siehe auch
* Modul [`aspose.cells.drawing`](..)
* Klasse [`ShapePath`](/cells/python-net/de/aspose.cells.drawing/shapepath)
* Klasse [`ShapeSegmentPathCollection`](/cells/python-net/de/aspose.cells.drawing/shapesegmentpathcollection)
