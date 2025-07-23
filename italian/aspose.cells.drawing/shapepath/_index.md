---
title: ShapePath classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 540
url: /it/aspose.cells.drawing/shapepath/
is_root: false
---
##  ShapePath classe
Rappresenta un percorso di creazione costituito da una serie di movimenti, linee e curve che, una volta combinati, formeranno una forma geometrica.



Il tipo ShapePath espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells.drawing/shapepath/__init__/#) | Inizializza una nuova istanza della classe [`ShapePath`](/cells/python-net/it/aspose.cells.drawing/shapepath).|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [path_segement_list](/cells/python-net/it/aspose.cells.drawing/shapepath/path_segement_list) | Ottiene l'elenco [`ShapeSegmentPathCollection`](/cells/python-net/it/aspose.cells.drawing/shapesegmentpathcollection)|
| [width_pixel](/cells/python-net/it/aspose.cells.drawing/shapepath/width_pixel) | Ottiene la larghezza di questo percorso in unità di pixel.|
| [height_pixel](/cells/python-net/it/aspose.cells.drawing/shapepath/height_pixel) | Ottiene l'altezza di questo percorso in unità di pixel.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`move_to(self, x, y)`](/cells/python-net/it/aspose.cells.drawing/shapepath/move_to/#float-float) |Inizia una nuova figura dal punto specificato senza chiudere la figura corrente. Tutti i punti successivi aggiunti al percorso vengono aggiunti a questa nuova figura.|
| [`line_to(self, x, y)`](/cells/python-net/it/aspose.cells.drawing/shapepath/line_to/#float-float) | Aggiunge un segmento di linea alla figura corrente.<br/> Il punto di partenza è il punto finale della figura corrente.|
| [`cubic_bezier_to(self, ctr_x1, ctr_y1, ctr_x2, ctr_y2, end_x, end_y)`](/cells/python-net/it/aspose.cells.drawing/shapepath/cubic_bezier_to/#float-float-float-float-float-float) | Aggiunge una curva di Bézier cubica alla figura corrente. Il punto iniziale è il punto finale della figura corrente.|
| [`arc_to(self, w_r, h_r, st_ang, sw_ang)`](/cells/python-net/it/aspose.cells.drawing/shapepath/arc_to/#float-float-float-float) | Aggiunge un arco ellittico alla figura corrente. Il punto iniziale è il punto finale della figura corrente.|
| [`close(self)`](/cells/python-net/it/aspose.cells.drawing/shapepath/close/#) | Chiude la figura corrente e ne inizia una nuova. Se la figura corrente contiene una sequenza di linee e curve connesse, il metodo chiude il ciclo collegando una linea dal punto finale al punto iniziale.|



###  Guarda anche
* modulo [`aspose.cells.drawing`](..)
* classe [`ShapePath`](/cells/python-net/it/aspose.cells.drawing/shapepath)
* classe [`ShapeSegmentPathCollection`](/cells/python-net/it/aspose.cells.drawing/shapesegmentpathcollection)
