---
title: ShapePath clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 540
url: /es/aspose.cells.drawing/shapepath/
is_root: false
---
##  ShapePath clase
Representa una ruta de creación que consta de una serie de movimientos, líneas y curvas que al combinarse formarán una forma geométrica.



El tipo ShapePath expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells.drawing/shapepath/__init__/#) | Inicializa una nueva instancia de la clase [`ShapePath`](/cells/python-net/es/aspose.cells.drawing/shapepath).|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [path_segement_list](/cells/python-net/es/aspose.cells.drawing/shapepath/path_segement_list) | Obtiene la lista [`ShapeSegmentPathCollection`](/cells/python-net/es/aspose.cells.drawing/shapesegmentpathcollection)|
| [width_pixel](/cells/python-net/es/aspose.cells.drawing/shapepath/width_pixel) | Obtiene el ancho de esta ruta en unidades de píxeles.|
| [height_pixel](/cells/python-net/es/aspose.cells.drawing/shapepath/height_pixel) | Obtiene la altura de esta ruta en unidades de píxeles.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`move_to(self, x, y)`](/cells/python-net/es/aspose.cells.drawing/shapepath/move_to/#float-float) |Inicia una nueva figura desde el punto especificado sin cerrar la figura actual. Todos los puntos posteriores añadidos a la ruta se añaden a esta nueva figura.|
| [`line_to(self, x, y)`](/cells/python-net/es/aspose.cells.drawing/shapepath/line_to/#float-float) | Añade un segmento de línea a la figura actual.<br/> El punto de partida es el punto final de la figura actual.|
| [`cubic_bezier_to(self, ctr_x1, ctr_y1, ctr_x2, ctr_y2, end_x, end_y)`](/cells/python-net/es/aspose.cells.drawing/shapepath/cubic_bezier_to/#float-float-float-float-float-float) | Añade una curva Bézier cúbica a la figura actual. El punto inicial es el punto final de la figura actual.|
| [`arc_to(self, w_r, h_r, st_ang, sw_ang)`](/cells/python-net/es/aspose.cells.drawing/shapepath/arc_to/#float-float-float-float) | Añade un arco elíptico a la figura actual. El punto inicial es el punto final de la figura actual.|
| [`close(self)`](/cells/python-net/es/aspose.cells.drawing/shapepath/close/#) | Cierra la figura actual e inicia una nueva. Si la figura actual contiene una secuencia de líneas y curvas conectadas, el método cierra el bucle conectando una línea desde el punto final hasta el punto inicial.|



###  Ver también
* módulo [`aspose.cells.drawing`](..)
* clase [`ShapePath`](/cells/python-net/es/aspose.cells.drawing/shapepath)
* clase [`ShapeSegmentPathCollection`](/cells/python-net/es/aspose.cells.drawing/shapesegmentpathcollection)
