---
title: TxtLoadOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1580
url: /es/aspose.cells/txtloadoptions/
is_root: false
---
##  TxtLoadOptions clase
Representa las opciones para cargar un archivo de texto.



**Herencia:** [`TxtLoadOptions`](/cells/python-net/aspose.cells/txtloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)



El tipo TxtLoadOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/txtloadoptions/__init__/#) | Crea las opciones para cargar archivos de texto.|
| [__init__](/cells/python-net/es/aspose.cells/txtloadoptions/__init__/#aspose.cells.LoadFormat) | Crea las opciones para cargar archivos de texto.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [load_format](/cells/python-net/es/aspose.cells/txtloadoptions/load_format) | Obtiene el formato de carga.|
| [password](/cells/python-net/es/aspose.cells/txtloadoptions/password) | Obtiene y establece la contraseña del libro de trabajo.|
| [parsing_formula_on_open](/cells/python-net/es/aspose.cells/txtloadoptions/parsing_formula_on_open) | Indica si se analiza la fórmula al leer el archivo.|
| [parsing_pivot_cached_records](/cells/python-net/es/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Indica si se analizan los registros en caché dinámicos al cargar el archivo.<br/> El valor predeterminado es falso.|
| [language_code](/cells/python-net/es/aspose.cells/txtloadoptions/language_code) | Obtiene o establece el idioma de la interfaz de usuario de la versión del libro de trabajo según el código de país que guardó el archivo.|
| [region](/cells/python-net/es/aspose.cells/txtloadoptions/region) |Obtiene o establece la configuración regional del sistema según el código de país en el momento en que se cargó el archivo.|
| [default_style_settings](/cells/python-net/es/aspose.cells/txtloadoptions/default_style_settings) | Obtiene la configuración de estilo predeterminada para inicializar estilos del libro.|
| [standard_font](/cells/python-net/es/aspose.cells/txtloadoptions/standard_font) | Establece el nombre de fuente estándar predeterminado|
| [standard_font_size](/cells/python-net/es/aspose.cells/txtloadoptions/standard_font_size) | Establece el tamaño de fuente estándar predeterminado.|
| [interrupt_monitor](/cells/python-net/es/aspose.cells/txtloadoptions/interrupt_monitor) | Obtiene y establece el monitor de interrupciones.|
| [ignore_not_printed](/cells/python-net/es/aspose.cells/txtloadoptions/ignore_not_printed) | Ignore los datos que no se imprimen si imprime directamente el archivo|
| [check_data_valid](/cells/python-net/es/aspose.cells/txtloadoptions/check_data_valid) | Compruebe si los datos son válidos en el archivo de plantilla.|
| [check_excel_restriction](/cells/python-net/es/aspose.cells/txtloadoptions/check_excel_restriction) | Si se verifica la restricción del archivo de Excel cuando el usuario modifica los objetos relacionados con las celdas.<br/>Por ejemplo, Excel no permite ingresar un valor de cadena de más de 32 K.<br/>Cuando ingresa un valor superior a 32 KB, como por ejemplo Cell.PutValue(cadena), si esta propiedad es verdadera, obtendrá una excepción.<br/>Si esta propiedad es falsa, aceptaremos el valor de su cadena de entrada como el valor de la celda para que más tarde<br/>puede generar el valor de cadena completo para otros formatos de archivo como CSV.<br/>Sin embargo, si ha establecido un tipo de valor que no es válido para el formato de archivo Excel,<br/> no debe guardar el libro como formato de archivo Excel más adelante. De lo contrario, puede haber un error inesperado en el archivo Excel generado.|
| [keep_unparsed_data](/cells/python-net/es/aspose.cells/txtloadoptions/keep_unparsed_data) | Si se mantienen los datos no analizados en la memoria para el libro de trabajo cuando se carga desde un archivo de plantilla. El valor predeterminado es verdadero.|
| [load_filter](/cells/python-net/es/aspose.cells/txtloadoptions/load_filter) | El filtro para indicar cómo cargar datos.|
| [light_cells_data_handler](/cells/python-net/es/aspose.cells/txtloadoptions/light_cells_data_handler) | El controlador de datos para procesar datos de celdas al leer el archivo de plantilla.|
| [memory_setting](/cells/python-net/es/aspose.cells/txtloadoptions/memory_setting) | Obtiene o establece las opciones de uso de memoria.|
| [warning_callback](/cells/python-net/es/aspose.cells/txtloadoptions/warning_callback) | Obtiene o establece una devolución de llamada de advertencia.|
| [auto_fitter_options](/cells/python-net/es/aspose.cells/txtloadoptions/auto_fitter_options) | Obtiene y establece las opciones del instalador automático.|
| [auto_filter](/cells/python-net/es/aspose.cells/txtloadoptions/auto_filter) | Indica si se filtran automáticamente los datos al cargar los archivos.|
| [font_configs](/cells/python-net/es/aspose.cells/txtloadoptions/font_configs) | Obtiene y establece configuraciones de fuentes individuales.<br/> Solo funciona para el [`Workbook`](/cells/python-net/es/aspose.cells/workbook) que usa este [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions) para cargar.|
| [ignore_useless_shapes](/cells/python-net/es/aspose.cells/txtloadoptions/ignore_useless_shapes) | Indica si se ignoran formas inútiles.|
| [preserve_padding_spaces_in_formula](/cells/python-net/es/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | Indica si se conservan los espacios y saltos de línea que se rellenan entre los tokens de fórmula.<br/>mientras obtiene y establece fórmulas.<br/> El valor predeterminado es falso.|
| [encoding](/cells/python-net/es/aspose.cells/txtloadoptions/encoding) |Obtiene y establece la codificación predeterminada. Sólo aplica para archivo csv.|
| [load_style_strategy](/cells/python-net/es/aspose.cells/txtloadoptions/load_style_strategy) | Indica la estrategia para aplicar estilo a los valores analizados al convertir un valor de cadena en número o fecha y hora.|
| [convert_numeric_data](/cells/python-net/es/aspose.cells/txtloadoptions/convert_numeric_data) | Obtiene o establece un valor que indica si la cadena del archivo de texto se convierte en datos numéricos.|
| [convert_date_time_data](/cells/python-net/es/aspose.cells/txtloadoptions/convert_date_time_data) | Obtiene o establece un valor que indica si la cadena del archivo de texto se convierte en datos de fecha.|
| [keep_precision](/cells/python-net/es/aspose.cells/txtloadoptions/keep_precision) | Indica si no se analiza un valor de cadena si la longitud es 15.|
| [separator](/cells/python-net/es/aspose.cells/txtloadoptions/separator) | Obtiene y establece el separador de caracteres del archivo de texto.|
| [separator_string](/cells/python-net/es/aspose.cells/txtloadoptions/separator_string) | Obtiene y establece un valor de cadena como separador.|
| [is_multi_encoded](/cells/python-net/es/aspose.cells/txtloadoptions/is_multi_encoded) |Verdadero significa que el archivo contiene varias codificaciones.|
| [preferred_parsers](/cells/python-net/es/aspose.cells/txtloadoptions/preferred_parsers) | Obtiene y establece analizadores de valores preferidos para cargar archivos de texto.|
| [has_formula](/cells/python-net/es/aspose.cells/txtloadoptions/has_formula) | Indica si el texto es fórmula si comienza con "=".|
| [has_text_qualifier](/cells/python-net/es/aspose.cells/txtloadoptions/has_text_qualifier) | Si hay un calificador de texto para el valor de la celda. El valor predeterminado es verdadero.|
| [text_qualifier](/cells/python-net/es/aspose.cells/txtloadoptions/text_qualifier) | Especifica el calificador de texto para los valores de celda. El calificador predeterminado es '"'.|
| [treat_consecutive_delimiters_as_one](/cells/python-net/es/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Si los delimitadores consecutivos deben tratarse como uno solo.|
| [treat_quote_prefix_as_value](/cells/python-net/es/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Indica si la comilla simple inicial debe tomarse como parte del valor de una celda.<br/>El valor predeterminado es verdadero. Si es falso, la comilla simple inicial se eliminará del valor de la celda correspondiente.<br/> y [`Style.quote_prefix`](/cells/python-net/es/aspose.cells/style#quote_prefix) se establecerá como verdadero para la celda.|
| [extend_to_next_sheet](/cells/python-net/es/aspose.cells/txtloadoptions/extend_to_next_sheet) | Si se extienden los datos a la siguiente hoja cuando las filas o columnas de datos exceden el límite.<br/> El valor predeterminado es falso.|
| [header_rows_count](/cells/python-net/es/aspose.cells/txtloadoptions/header_rows_count) | El recuento de filas de encabezado que se repetirán para las hojas extendidas.|
| [header_columns_count](/cells/python-net/es/aspose.cells/txtloadoptions/header_columns_count) | El recuento de columnas de encabezado que se repetirán para las hojas extendidas.|
| [max_row_count](/cells/python-net/es/aspose.cells/txtloadoptions/max_row_count) | El recuento máximo de filas que se importarán para una hoja.|
| [max_column_count](/cells/python-net/es/aspose.cells/txtloadoptions/max_column_count) | El recuento máximo de columnas que se importarán para una hoja.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [set_paper_size](/cells/python-net/es/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Establece el tamaño de papel de impresión predeterminado desde la configuración predeterminada de la impresora.|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`AbstractTextLoadOptions`](/cells/python-net/es/aspose.cells/abstracttextloadoptions)
* clase [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)
* clase [`TxtLoadOptions`](/cells/python-net/es/aspose.cells/txtloadoptions)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
