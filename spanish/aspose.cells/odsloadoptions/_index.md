---
title: OdsLoadOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1030
url: /es/aspose.cells/odsloadoptions/
is_root: false
---
##  OdsLoadOptions clase
Representa las opciones de carga del archivo ods.



**Herencia:** [`OdsLoadOptions`](/cells/python-net/aspose.cells/odsloadoptions) → 
[`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)



El tipo OdsLoadOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/odsloadoptions/__init__/#) | Representa las opciones de carga del archivo ods.|
| [`__init__(self, type)`](/cells/python-net/es/aspose.cells/odsloadoptions/__init__/#aspose.cells.loadformat) | Representa las opciones de carga del archivo ods.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [load_format](/cells/python-net/es/aspose.cells/odsloadoptions/load_format) | Obtiene el formato de carga.|
| [password](/cells/python-net/es/aspose.cells/odsloadoptions/password) | Obtiene y establece la contraseña del libro de trabajo.|
| [parsing_formula_on_open](/cells/python-net/es/aspose.cells/odsloadoptions/parsing_formula_on_open) | Indica si se analiza la fórmula al leer el archivo.|
| [parsing_pivot_cached_records](/cells/python-net/es/aspose.cells/odsloadoptions/parsing_pivot_cached_records) | Indica si se analizan los registros en caché del pivote al cargar el archivo.<br/> El valor predeterminado es falso.|
| [language_code](/cells/python-net/es/aspose.cells/odsloadoptions/language_code) | Obtiene o establece el idioma de la interfaz de usuario de la versión del libro de trabajo según el código de país que ha guardado el archivo.|
| [region](/cells/python-net/es/aspose.cells/odsloadoptions/region) | Obtiene o establece la configuración regional utilizada para el libro de trabajo que se cargará.|
| [default_style_settings](/cells/python-net/es/aspose.cells/odsloadoptions/default_style_settings) | Obtiene la configuración de estilo predeterminada para inicializar los estilos del libro de trabajo.|
| [standard_font](/cells/python-net/es/aspose.cells/odsloadoptions/standard_font) | Establece el nombre de fuente estándar predeterminado|
| [standard_font_size](/cells/python-net/es/aspose.cells/odsloadoptions/standard_font_size) | Establece el tamaño de fuente estándar predeterminado.|
| [ignore_not_printed](/cells/python-net/es/aspose.cells/odsloadoptions/ignore_not_printed) | Ignore los datos que no se imprimen si imprime directamente el archivo|
| [check_data_valid](/cells/python-net/es/aspose.cells/odsloadoptions/check_data_valid) | Compruebe si los datos son válidos en el archivo de plantilla.|
| [check_excel_restriction](/cells/python-net/es/aspose.cells/odsloadoptions/check_excel_restriction) | Si verificar la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas.<br/>Por ejemplo, Excel no permite ingresar valores de cadena con una longitud mayor a 32K.<br/>Cuando ingresa un valor más largo que 32K, como por ejemplo Cell.PutValue(string), si esta propiedad es verdadera, obtendrá una excepción.<br/>Si esta propiedad es falsa, aceptaremos el valor de la cadena de entrada como el valor de la celda para que más adelante<br/>Puede generar el valor de cadena completo para otros formatos de archivo, como CSV.<br/>Sin embargo, si ha establecido un tipo de valor que no es válido para el formato de archivo de Excel,<br/>No guarde el libro de trabajo como archivo Excel posteriormente. De lo contrario, podría producirse un error inesperado en el archivo Excel generado.|
| [keep_unparsed_data](/cells/python-net/es/aspose.cells/odsloadoptions/keep_unparsed_data) | Si se conservan los datos no analizados en memoria para el libro de trabajo al cargarlo desde el archivo de plantilla. El valor predeterminado es "true".|
| [load_filter](/cells/python-net/es/aspose.cells/odsloadoptions/load_filter) | El filtro para indicar cómo cargar los datos.|
| [memory_setting](/cells/python-net/es/aspose.cells/odsloadoptions/memory_setting) | Obtiene o establece el modo de memoria para el libro cargado.|
| [auto_fitter_options](/cells/python-net/es/aspose.cells/odsloadoptions/auto_fitter_options) | Obtiene y establece las opciones de ajuste automático|
| [auto_filter](/cells/python-net/es/aspose.cells/odsloadoptions/auto_filter) | Indica si se filtrarán automáticamente los datos al cargar los archivos.|
| [font_configs](/cells/python-net/es/aspose.cells/odsloadoptions/font_configs) | Obtiene y establece configuraciones de fuentes individuales.<br/> Solo funciona para el [`Workbook`](/cells/python-net/es/aspose.cells/workbook) que usa este [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions) para cargar.|
| [ignore_useless_shapes](/cells/python-net/es/aspose.cells/odsloadoptions/ignore_useless_shapes) | Indica si se ignoran las formas inútiles.|
| [preserve_padding_spaces_in_formula](/cells/python-net/es/aspose.cells/odsloadoptions/preserve_padding_spaces_in_formula) | Indica si se conservan los espacios y saltos de línea que se rellenan entre los tokens de fórmula<br/>al obtener y configurar fórmulas.<br/> El valor predeterminado es falso.|
| [apply_excel_default_style_to_hyperlink](/cells/python-net/es/aspose.cells/odsloadoptions/apply_excel_default_style_to_hyperlink) | Indica si se aplica el estilo predeterminado de Excel al hipervínculo.|
| [refresh_pivot_tables](/cells/python-net/es/aspose.cells/odsloadoptions/refresh_pivot_tables) | Indica si se deben actualizar las tablas dinámicas al cargar el archivo.|
| [is_classic_pivot_table](/cells/python-net/es/aspose.cells/odsloadoptions/is_classic_pivot_table) | Indica si la tabla dinámica es clásica.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/es/aspose.cells/odsloadoptions/set_paper_size/#aspose.cells.papersizetype) | Establece el tamaño de papel de impresión predeterminado según la configuración predeterminada de la impresora.|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)
* clase [`OdsLoadOptions`](/cells/python-net/es/aspose.cells/odsloadoptions)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
