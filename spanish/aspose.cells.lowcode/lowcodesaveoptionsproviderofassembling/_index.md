---
title: LowCodeSaveOptionsProviderOfAssembling clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 110
url: /es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/
is_root: false
---
##  LowCodeSaveOptionsProviderOfAssembling clase
Implementación para proporcionar opciones de guardado que guardan partes divididas en archivos
y la ruta del archivo resultante se nombra como (puede contener directorios):
[`LowCodeSaveOptionsProviderOfAssembling.path_header`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_header)+[`LowCodeSaveOptionsProviderOfAssembling.sheet_prefix`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#sheet_prefix)+ÍndiceHoja(o NombreHoja)
+[`LowCodeSaveOptionsProviderOfAssembling.split_part_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#split_part_prefix)+SplitPartIndex+[`LowCodeSaveOptionsProviderOfAssembling.path_tail`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_tail).



**Herencia:** [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)



El tipo LowCodeSaveOptionsProviderOfAssembling expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/__init__/#) | Construye una nueva instancia de LowCodeSaveOptionsProviderOfAssembling|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [path_header](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_header) | Parte del encabezado (antes de agregar el contenido de la hoja y la parte dividida) de la ruta del archivo.|
| [path_tail](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_tail) | Parte final (después de los números de secuencia) de la ruta del archivo.<br/> Debe incluir la extensión del nombre del archivo.|
| [use_sheet_name](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/use_sheet_name) | Si se crea la ruta del archivo con el nombre de la hoja en lugar del índice. El valor predeterminado es falso.|
| [sheet_prefix](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_prefix) |Prefijo para el índice de la hoja de cálculo.|
| [split_part_prefix](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_prefix) | Prefijo para el índice de la parte dividida.|
| [sheet_index_offset](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_index_offset) | Desplazamiento del índice de la hoja entre lo utilizado en la ruta del archivo<br/> y su valor real([`SplitPartInfo.sheet_index`](/cells/python-net/es/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_index_offset) | Desplazamiento del índice de la parte dividida entre lo utilizado en la ruta del archivo<br/> y su valor real([`SplitPartInfo.part_index`](/cells/python-net/es/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_sheet_always) | Si desea agregar el índice de la hoja o el nombre a la ruta del archivo siempre.<br/>El valor predeterminado es falso, es decir, cuando solo hay una hoja,<br/> El índice de la hoja (o nombre) y el prefijo correspondiente no se agregarán a la ruta del archivo.|
| [build_path_with_split_part_always](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_split_part_always) | Si desea agregar el índice de la parte dividida a la ruta del archivo siempre.<br/>El valor predeterminado es falso, es decir, cuando solo hay una parte dividida,<br/> El índice de la parte dividida y el prefijo correspondiente no se agregarán a la ruta del archivo.|
| [save_options_template](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/save_options_template) | La plantilla para crear una instancia de opciones de guardado en [`LowCodeSaveOptionsProviderOfAssembling.get_save_options`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options).|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Obtiene las opciones de guardado desde las cuales obtener las configuraciones de salida para la parte dividida actualmente.|
| [`finish(self, part)`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Ver también
* módulo [`aspose.cells.lowcode`](..)
* clase [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)
