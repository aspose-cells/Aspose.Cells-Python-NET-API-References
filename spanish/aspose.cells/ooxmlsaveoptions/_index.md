---
title: OoxmlSaveOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1050
url: /es/aspose.cells/ooxmlsaveoptions/
is_root: false
---
##  OoxmlSaveOptions clase
Representa las opciones para guardar el archivo xml abierto de office.



**Herencia:** [`OoxmlSaveOptions`](/cells/python-net/aspose.cells/ooxmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)



El tipo OoxmlSaveOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/__init__/#) | Crea las opciones para guardar el archivo xml abierto de Office.|
| [`__init__(self, save_format)`](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/__init__/#aspose.cells.saveformat) | Crea las opciones para guardar el archivo xml abierto de Office.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [save_format](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/save_format) | Obtiene el formato del archivo guardado.|
| [clear_data](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/clear_data) | Vacíe el libro de trabajo después de guardar el archivo.|
| [cached_file_folder](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/cached_file_folder) | La carpeta para archivos temporales que pueden usarse como caché de datos.|
| [validate_merged_areas](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/validate_merged_areas) | Indica si se deben validar las celdas fusionadas antes de guardar el archivo.|
| [merge_areas](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/merge_areas) | Indica si se deben fusionar las áreas de formato condicional y validación antes de guardar el archivo.|
| [create_directory](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/create_directory) | Si es verdadero y el directorio no existe, el directorio se creará automáticamente antes de guardar el archivo.|
| [sort_names](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/sort_names) |Indica si se deben ordenar los nombres definidos antes de guardar el archivo.|
| [sort_external_names](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/sort_external_names) | Indica si se deben ordenar los nombres definidos externamente antes de guardar el archivo.|
| [refresh_chart_cache](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/refresh_chart_cache) | Indica si se actualizan los datos de caché del gráfico|
| [check_excel_restriction](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/check_excel_restriction) | Si verificar la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas.<br/>Por ejemplo, Excel no permite ingresar valores de cadena con una longitud mayor a 32K.<br/> Cuando ingrese un valor mayor a 32K, este se truncará.|
| [update_smart_art](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/update_smart_art) | Indica si se actualiza la configuración de arte inteligente.<br/> El valor predeterminado es falso.|
| [encrypt_document_properties](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/encrypt_document_properties) | Indica si se deben cifrar las propiedades del documento al guardarlo como archivo .xls.<br/> El valor predeterminado es verdadero.|
| [export_cell_name](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/export_cell_name) | Indica si se debe exportar el nombre de la celda a un archivo .xlsx (.xlsm, .xltx, .xltm) de Excel2007.<br/>Si SQL Server DTS puede acceder al archivo de salida, este valor debe ser verdadero.<br/>Establecer el valor en falso aumentará considerablemente el rendimiento y reducirá el tamaño del archivo al crear archivos grandes.<br/> El valor predeterminado es verdadero.|
| [update_zoom](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/update_zoom) | Indica si se debe actualizar el factor de escala antes de guardar el archivo<br/> si las propiedades PageSetup.FitToPagesWide y PageSetup.FitToPagesTall controlan cómo se escala la hoja de cálculo.|
| [enable_zip64](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/enable_zip64) | Utilice siempre extensiones ZIP64 al escribir archivos zip, incluso cuando no sea necesario.|
| [embed_ooxml_as_ole_object](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/embed_ooxml_as_ole_object) | Indica si se deben incrustar archivos Ooxml de OleObject como objeto ole.|
| [compression_type](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/compression_type) | Obtiene y establece el tipo de compresión para el archivo ooxml.|
| [wps_compatibility](/cells/python-net/es/aspose.cells/ooxmlsaveoptions/wps_compatibility) | Indica si se debe hacer que el xls sea más compatible con WPS.|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`OoxmlSaveOptions`](/cells/python-net/es/aspose.cells/ooxmlsaveoptions)
* clase [`SaveOptions`](/cells/python-net/es/aspose.cells/saveoptions)
