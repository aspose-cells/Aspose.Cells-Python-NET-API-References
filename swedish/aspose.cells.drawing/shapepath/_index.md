---
title: ShapePath klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 540
url: /sv/aspose.cells.drawing/shapepath/
is_root: false
---
##  ShapePath klass
Representerar en skapandeväg bestående av en serie rörelser, linjer och kurvor som när de kombineras bildar en geometrisk form.



Typen ShapePath avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells.drawing/shapepath/__init__/#) | Initierar en ny instans av klassen [`ShapePath`](/cells/python-net/sv/aspose.cells.drawing/shapepath).|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [path_segement_list](/cells/python-net/sv/aspose.cells.drawing/shapepath/path_segement_list) | Hämtar [`ShapeSegmentPathCollection`](/cells/python-net/sv/aspose.cells.drawing/shapesegmentpathcollection)-listan|
| [width_pixel](/cells/python-net/sv/aspose.cells.drawing/shapepath/width_pixel) | Hämtar bredden på den här banan i pixlar.|
| [height_pixel](/cells/python-net/sv/aspose.cells.drawing/shapepath/height_pixel) | Hämtar höjden på denna sökväg i pixlar.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`move_to(self, x, y)`](/cells/python-net/sv/aspose.cells.drawing/shapepath/move_to/#float-float) |Startar en ny figur från den angivna punkten utan att stänga den aktuella figuren. Alla efterföljande punkter som läggs till banan läggs till i den nya figuren.|
| [`line_to(self, x, y)`](/cells/python-net/sv/aspose.cells.drawing/shapepath/line_to/#float-float) | Lägger till ett linjesegment till den aktuella figuren.<br/> Utgångspunkten är slutpunkten för den aktuella figuren.|
| [`cubic_bezier_to(self, ctr_x1, ctr_y1, ctr_x2, ctr_y2, end_x, end_y)`](/cells/python-net/sv/aspose.cells.drawing/shapepath/cubic_bezier_to/#float-float-float-float-float-float) | Lägger till en kubisk Bézier-kurva till den aktuella figuren. Startpunkten är slutpunkten för den aktuella figuren.|
| [`arc_to(self, w_r, h_r, st_ang, sw_ang)`](/cells/python-net/sv/aspose.cells.drawing/shapepath/arc_to/#float-float-float-float) | Lägger till en elliptisk båge till den aktuella figuren. Startpunkten är slutpunkten för den aktuella figuren.|
| [`close(self)`](/cells/python-net/sv/aspose.cells.drawing/shapepath/close/#) | Stänger den aktuella figuren och påbörjar en ny figur. Om den aktuella figuren innehåller en sekvens av sammanhängande linjer och kurvor, stänger metoden loopen genom att ansluta en linje från slutpunkten till startpunkten.|



###  Se även
* modul [`aspose.cells.drawing`](..)
* klass [`ShapePath`](/cells/python-net/sv/aspose.cells.drawing/shapepath)
* klass [`ShapeSegmentPathCollection`](/cells/python-net/sv/aspose.cells.drawing/shapesegmentpathcollection)
