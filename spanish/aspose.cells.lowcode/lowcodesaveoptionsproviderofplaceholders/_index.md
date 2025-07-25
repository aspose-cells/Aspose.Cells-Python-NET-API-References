---
title: LowCodeSaveOptionsProviderOfPlaceHolders clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 120
url: /es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---
##  LowCodeSaveOptionsProviderOfPlaceHolders clase
Implementación para proporcionar opciones de guardado que guardan partes divididas en archivos
y la ruta del archivo resultante se define con marcadores de posición.



**Herencia:** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)



El tipo LowCodeSaveOptionsProviderOfPlaceHolders expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) |Crea una instancia para proporcionar opciones de guardado según plantillas especificadas.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [sheet_index_offset](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) | Desplazamiento del índice de la hoja entre lo utilizado en la ruta del archivo<br/> y su valor real([`SplitPartInfo.sheet_index`](/cells/python-net/es/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) | Desplazamiento del índice de la parte dividida entre lo utilizado en la ruta del archivo<br/> y su valor real([`SplitPartInfo.part_index`](/cells/python-net/es/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) | Si desea agregar el índice de la hoja o el nombre a la ruta del archivo siempre.<br/>El valor predeterminado es falso, es decir, cuando solo hay una hoja,<br/>el índice de la hoja y el nombre y el prefijo correspondiente ([`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix))<br/> no se agregará a la ruta del archivo.|
| [build_path_with_split_part_always](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) | Si desea agregar el índice de la parte dividida a la ruta del archivo siempre.<br/>El valor predeterminado es falso, es decir, cuando solo hay una parte dividida,<br/>el índice de la parte dividida y el prefijo correspondiente ([`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix))<br/> no se agregará a la ruta del archivo.|
| [sheet_name_prefix](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) |Prefijo para el índice de la hoja de cálculo.|
| [sheet_index_prefix](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) |Prefijo para el índice de la hoja de cálculo.|
| [split_part_prefix](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) | Prefijo para el índice de la parte dividida.|
| [save_options_template](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | La plantilla para crear una instancia de opciones de guardado en [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options).|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Obtiene las opciones de guardado desde las cuales obtener las configuraciones de salida para la parte dividida actualmente.|
| [`finish(self, part)`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Ver también
* módulo [`aspose.cells.lowcode`](..)
* clase [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/es/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
