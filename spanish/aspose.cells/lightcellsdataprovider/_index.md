---
title: LightCellsDataProvider clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1040
url: /es/aspose.cells/lightcellsdataprovider/
is_root: false
---
##  LightCellsDataProvider clase
Representa el proveedor de datos para guardar archivos de hojas de cálculo grandes en modo liviano.



El tipo LightCellsDataProvider expone los siguientes miembros:

###  Métodos
| Método| Descripción|
| :- | :- |
| [start_sheet](/cells/python-net/es/aspose.cells/lightcellsdataprovider/start_sheet/#int) | Comienza a guardar una hoja de trabajo.|
| [next_row](/cells/python-net/es/aspose.cells/lightcellsdataprovider/next_row/#) | Obtiene la siguiente fila que se guardará.|
| [start_row](/cells/python-net/es/aspose.cells/lightcellsdataprovider/start_row/#aspose.cells.Row) | Comienza a guardar datos de una fila.|
| [next_cell](/cells/python-net/es/aspose.cells/lightcellsdataprovider/next_cell/#) | Obtiene la siguiente celda que se guardará.|
| [start_cell](/cells/python-net/es/aspose.cells/lightcellsdataprovider/start_cell/#aspose.cells.Cell) | Comienza a guardar datos de una celda.|
| [is_gather_string](/cells/python-net/es/aspose.cells/lightcellsdataprovider/is_gather_string/#) |Comprueba si el valor de cadena actual de la celda debe recopilarse en un grupo global.|



###  Observaciones

Al guardar un libro de trabajo mediante este modo, se marcará [`LightCellsDataProvider.start_sheet`](/cells/python-net/es/aspose.cells/lightcellsdataprovider/start_sheet) al guardar cada hoja de trabajo del libro de trabajo.
Para una hoja, si [`LightCellsDataProvider.start_sheet`](/cells/python-net/es/aspose.cells/lightcellsdataprovider/start_sheet) es verdadero, entonces todos los datos y propiedades se guardarán para las filas/celdas de esta hoja.
será proporcionado por la implementación de esta interfaz.
En primer lugar, se llamará a [`LightCellsDataProvider.next_row`](/cells/python-net/es/aspose.cells/lightcellsdataprovider/next_row) para guardar el índice de la siguiente fila.
Si se devuelve un índice de fila válido (el índice de fila debe estar en orden ascendente para que se guarden las filas),
luego, [`LightCellsDataProvider.start_row`](/cells/python-net/es/aspose.cells/lightcellsdataprovider/start_row) proporcionará un objeto Row que representa esta fila para que la implementación establezca sus propiedades.
Para una fila, primero se comprobará [`LightCellsDataProvider.next_cell`](/cells/python-net/es/aspose.cells/lightcellsdataprovider/next_cell).
Si se devuelve un índice de columna válido (el índice de la columna debe estar en orden ascendente para todas las celdas de la fila actual),
luego, [`LightCellsDataProvider.start_cell`](/cells/python-net/es/aspose.cells/lightcellsdataprovider/start_cell) proporcionará un objeto Cell que representa esta celda para que la implementación establezca sus datos y propiedades.
Después de [`LightCellsDataProvider.start_cell`](/cells/python-net/es/aspose.cells/lightcellsdataprovider/start_cell), la celda se guardará directamente en el archivo de hoja de cálculo resultante.
Luego se verificará y procesará la siguiente celda.


Tenga en cuenta que el usuario solo debe actualizar los valores y propiedades del objeto Fila/Cell actual proporcionado por el método correspondiente.
Debido a que los datos de las celdas se escriben en el archivo resultante en forma de transmisión, es posible que la mayoría de los demás objetos se hayan escrito
al archivo resultante, o se han recopilado y escrito algunos datos globales para ellos. Entonces, cuando el usuario actualiza otros objetos
Al guardar datos de celdas, es posible que esas operaciones no afecten los datos guardados. O peor aún, esas operaciones pueden
causar que los datos inconsistentes se guarden en el archivo resultante y finalmente dañar el archivo.
Entonces, para todos los demás objetos como formas, ancho de columna y estilos, formatos condicionales, etc.,
no los opere en ningún método de esta implementación.
En su lugar, adminístrelos y ajústelos al estado final antes de llamar al método "Guardar" del Libro de trabajo.

###  Ver también
* módulo [`aspose.cells`](..)
