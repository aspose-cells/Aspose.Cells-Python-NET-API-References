---
title: ShapePath classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 540
url: /fr/aspose.cells.drawing/shapepath/
is_root: false
---
##  ShapePath classe
Représente un chemin de création composé d'une série de mouvements, de lignes et de courbes qui, une fois combinés, formeront une forme géométrique.



Le type ShapePath expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells.drawing/shapepath/__init__/#) | Initialise une nouvelle instance de la classe [`ShapePath`](/cells/python-net/fr/aspose.cells.drawing/shapepath).|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [path_segement_list](/cells/python-net/fr/aspose.cells.drawing/shapepath/path_segement_list) | Obtient la liste [`ShapeSegmentPathCollection`](/cells/python-net/fr/aspose.cells.drawing/shapesegmentpathcollection)|
| [width_pixel](/cells/python-net/fr/aspose.cells.drawing/shapepath/width_pixel) | Obtient la largeur de ce chemin en unité de pixels.|
| [height_pixel](/cells/python-net/fr/aspose.cells.drawing/shapepath/height_pixel) | Obtient la hauteur de ce chemin en unité de pixels.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`move_to(self, x, y)`](/cells/python-net/fr/aspose.cells.drawing/shapepath/move_to/#float-float) |Commence une nouvelle figure à partir du point spécifié sans fermer la figure actuelle. Tous les points ajoutés ultérieurement au chemin sont ajoutés à cette nouvelle figure.|
| [`line_to(self, x, y)`](/cells/python-net/fr/aspose.cells.drawing/shapepath/line_to/#float-float) | Ajoute un segment de ligne à la figure actuelle.<br/> Le point de départ est le point final de la figure actuelle.|
| [`cubic_bezier_to(self, ctr_x1, ctr_y1, ctr_x2, ctr_y2, end_x, end_y)`](/cells/python-net/fr/aspose.cells.drawing/shapepath/cubic_bezier_to/#float-float-float-float-float-float) | Ajoute une courbe de Bézier cubique à la figure actuelle. Le point de départ est le point d'arrivée de la figure actuelle.|
| [`arc_to(self, w_r, h_r, st_ang, sw_ang)`](/cells/python-net/fr/aspose.cells.drawing/shapepath/arc_to/#float-float-float-float) | Ajoute un arc elliptique à la figure actuelle. Le point de départ est le point d'arrivée de la figure actuelle.|
| [`close(self)`](/cells/python-net/fr/aspose.cells.drawing/shapepath/close/#) | Ferme la figure actuelle et en crée une nouvelle. Si la figure actuelle contient une séquence de lignes et de courbes connectées, la méthode ferme la boucle en reliant une ligne du point d'arrivée au point de départ.|



###  Voir également
* module [`aspose.cells.drawing`](..)
* classe [`ShapePath`](/cells/python-net/fr/aspose.cells.drawing/shapepath)
* classe [`ShapeSegmentPathCollection`](/cells/python-net/fr/aspose.cells.drawing/shapesegmentpathcollection)
