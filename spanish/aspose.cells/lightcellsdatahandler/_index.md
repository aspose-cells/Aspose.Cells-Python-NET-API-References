---
title: LightCellsDataHandler clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1030
url: /es/aspose.cells/lightcellsdatahandler/
is_root: false
---
##  LightCellsDataHandler clase
Representa el controlador de datos de celdas para leer archivos de hojas de cálculo grandes en modo liviano.



El tipo LightCellsDataHandler expone los siguientes miembros:

###  Métodos
| Método| Descripción|
| :- | :- |
| [start_sheet](/cells/python-net/es/aspose.cells/lightcellsdatahandler/start_sheet/#aspose.cells.Worksheet) | Comienza a procesar una hoja de trabajo.|
| [start_row](/cells/python-net/es/aspose.cells/lightcellsdatahandler/start_row/#int) | Se prepara para procesar una fila.|
| [process_row](/cells/python-net/es/aspose.cells/lightcellsdatahandler/process_row/#aspose.cells.Row) | Comienza a procesar una fila.|
| [start_cell](/cells/python-net/es/aspose.cells/lightcellsdatahandler/start_cell/#int) | Se prepara para procesar una celda.|
| [process_cell](/cells/python-net/es/aspose.cells/lightcellsdatahandler/process_cell/#aspose.cells.Cell) | Comienza a procesar una celda.|



###  Observaciones

Al leer un libro de trabajo mediante este modo, se marcará [`LightCellsDataHandler.start_sheet`](/cells/python-net/es/aspose.cells/lightcellsdatahandler/start_sheet) al leer cada hoja de trabajo del libro de trabajo.
Para una hoja, si [`LightCellsDataHandler.start_sheet`](/cells/python-net/es/aspose.cells/lightcellsdatahandler/start_sheet) es verdadero, se verificarán todos los datos y propiedades de las filas/celdas de esta hoja.
y procesado por la implementación de esta interfaz. Para cada fila, se llamará al [`LightCellsDataHandler.start_row`](/cells/python-net/es/aspose.cells/lightcellsdatahandler/start_row) para comprobar si es necesario procesarla.
Si es necesario procesar una fila, las propiedades de esta fila se leerán primero y el usuario podrá acceder a sus propiedades mediante [`LightCellsDataHandler.process_row`](/cells/python-net/es/aspose.cells/lightcellsdatahandler/process_row).
Si las celdas de la fila también deben procesarse, entonces [`LightCellsDataHandler.process_row`](/cells/python-net/es/aspose.cells/lightcellsdatahandler/process_row) debería devolver verdadero y luego [`LightCellsDataHandler.start_cell`](/cells/python-net/es/aspose.cells/lightcellsdatahandler/start_cell) será
solicitó que cada celda existente en esta fila verifique si es necesario procesar una celda. Si es necesario procesar una celda,
luego se llamará a [`LightCellsDataHandler.process_cell`](/cells/python-net/es/aspose.cells/lightcellsdatahandler/process_cell) para procesar la celda mediante la implementación de esta interfaz.


Tenga en cuenta que el usuario solo debe operar con los valores y propiedades del objeto Fila/Cell actual proporcionado por el método correspondiente.
Debido a que los datos de las celdas se leen desde el archivo de plantilla en forma de transmisión, la mayoría de los demás objetos pueden restablecerse o actualizarse más adelante.
después de que se hayan cargado los datos de las celdas. Entonces, cuando el usuario opera otros objetos en esta implementación,
Es posible que esas operaciones no puedan afectar los objetos existentes en el libro de trabajo. O peor aún, esas operaciones pueden
causar datos inconsistentes en el libro de trabajo y luego causar problemas o excepciones inesperados más adelante.
Entonces, para todos los demás objetos como formas, ancho de columna y estilos, formatos condicionales, etc.,
no los opere en ningún método de esta implementación.
En su lugar, adminístrelos después de que se haya creado el libro de trabajo.

###  Ver también
* módulo [`aspose.cells`](..)
