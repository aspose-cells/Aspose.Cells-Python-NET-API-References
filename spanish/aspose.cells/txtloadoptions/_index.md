---
title: TxtLoadOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1490
url: /es/aspose.cells/txtloadoptions/
is_root: false
---
##  TxtLoadOptions clase
Representa las opciones para cargar el archivo de texto.



**Herencia:** [`TxtLoadOptions`](/cells/python-net/aspose.cells/txtloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)



El tipo TxtLoadOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/txtloadoptions/__init__/#) | Crea las opciones para cargar el archivo de texto.|
| [`__init__(self, load_format)`](/cells/python-net/es/aspose.cells/txtloadoptions/__init__/#aspose.cells.loadformat) | Crea las opciones para cargar el archivo de texto.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [load_format](/cells/python-net/es/aspose.cells/txtloadoptions/load_format) | Obtiene el formato de carga.|
| [password](/cells/python-net/es/aspose.cells/txtloadoptions/password) | Obtiene y establece la contraseña del libro de trabajo.|
| [parsing_formula_on_open](/cells/python-net/es/aspose.cells/txtloadoptions/parsing_formula_on_open) | Indica si se analiza la fórmula al leer el archivo.|
| [parsing_pivot_cached_records](/cells/python-net/es/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Indica si se analizan los registros en caché del pivote al cargar el archivo.<br/> El valor predeterminado es falso.|
| [language_code](/cells/python-net/es/aspose.cells/txtloadoptions/language_code) | Obtiene o establece el idioma de la interfaz de usuario de la versión del libro de trabajo según el código de país que ha guardado el archivo.|
| [region](/cells/python-net/es/aspose.cells/txtloadoptions/region) | Obtiene o establece la configuración regional utilizada para el libro de trabajo que se cargará.|
| [default_style_settings](/cells/python-net/es/aspose.cells/txtloadoptions/default_style_settings) | Obtiene la configuración de estilo predeterminada para inicializar los estilos del libro de trabajo.|
| [standard_font](/cells/python-net/es/aspose.cells/txtloadoptions/standard_font) | Establece el nombre de fuente estándar predeterminado|
| [standard_font_size](/cells/python-net/es/aspose.cells/txtloadoptions/standard_font_size) | Establece el tamaño de fuente estándar predeterminado.|
| [ignore_not_printed](/cells/python-net/es/aspose.cells/txtloadoptions/ignore_not_printed) | Ignore los datos que no se imprimen si imprime directamente el archivo|
| [check_data_valid](/cells/python-net/es/aspose.cells/txtloadoptions/check_data_valid) | Compruebe si los datos son válidos en el archivo de plantilla.|
| [check_excel_restriction](/cells/python-net/es/aspose.cells/txtloadoptions/check_excel_restriction) | Si verificar la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas.<br/>Por ejemplo, Excel no permite ingresar valores de cadena con una longitud mayor a 32K.<br/>Cuando ingresa un valor más largo que 32K, como por ejemplo Cell.PutValue(string), si esta propiedad es verdadera, obtendrá una excepción.<br/>Si esta propiedad es falsa, aceptaremos el valor de la cadena de entrada como el valor de la celda para que más adelante<br/>Puede generar el valor de cadena completo para otros formatos de archivo, como CSV.<br/>Sin embargo, si ha establecido un tipo de valor que no es válido para el formato de archivo de Excel,<br/>No guarde el libro de trabajo como archivo Excel posteriormente. De lo contrario, podría producirse un error inesperado en el archivo Excel generado.|
| [keep_unparsed_data](/cells/python-net/es/aspose.cells/txtloadoptions/keep_unparsed_data) | Si se conservan los datos no analizados en memoria para el libro de trabajo al cargarlo desde el archivo de plantilla. El valor predeterminado es "true".|
| [load_filter](/cells/python-net/es/aspose.cells/txtloadoptions/load_filter) | El filtro para indicar cómo cargar los datos.|
| [memory_setting](/cells/python-net/es/aspose.cells/txtloadoptions/memory_setting) | Obtiene o establece el modo de memoria para el libro cargado.|
| [auto_fitter_options](/cells/python-net/es/aspose.cells/txtloadoptions/auto_fitter_options) | Obtiene y establece las opciones de ajuste automático|
| [auto_filter](/cells/python-net/es/aspose.cells/txtloadoptions/auto_filter) | Indica si se filtrarán automáticamente los datos al cargar los archivos.|
| [font_configs](/cells/python-net/es/aspose.cells/txtloadoptions/font_configs) | Obtiene y establece configuraciones de fuentes individuales.<br/> Solo funciona para el [`Workbook`](/cells/python-net/es/aspose.cells/workbook) que usa este [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions) para cargar.|
| [ignore_useless_shapes](/cells/python-net/es/aspose.cells/txtloadoptions/ignore_useless_shapes) | Indica si se ignoran las formas inútiles.|
| [preserve_padding_spaces_in_formula](/cells/python-net/es/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | Indica si se conservan los espacios y saltos de línea que se rellenan entre los tokens de fórmula<br/>al obtener y configurar fórmulas.<br/> El valor predeterminado es falso.|
| [encoding](/cells/python-net/es/aspose.cells/txtloadoptions/encoding) | Obtiene y establece la codificación predeterminada. Solo se aplica a archivos CSV.|
| [load_style_strategy](/cells/python-net/es/aspose.cells/txtloadoptions/load_style_strategy) | Indica la estrategia para aplicar estilo a los valores analizados al convertir un valor de cadena en número o fecha y hora.|
| [convert_numeric_data](/cells/python-net/es/aspose.cells/txtloadoptions/convert_numeric_data) |Obtiene o establece un valor que indica si la cadena en el archivo de texto se convierte en datos numéricos.|
| [convert_date_time_data](/cells/python-net/es/aspose.cells/txtloadoptions/convert_date_time_data) | Obtiene o establece un valor que indica si la cadena en el archivo de texto se convierte a datos de fecha.|
| [keep_precision](/cells/python-net/es/aspose.cells/txtloadoptions/keep_precision) | Indica si no se analiza un valor de cadena si la longitud es 15.|
| [separator](/cells/python-net/es/aspose.cells/txtloadoptions/separator) | Obtiene y establece el separador de caracteres del archivo de texto.|
| [separator_string](/cells/python-net/es/aspose.cells/txtloadoptions/separator_string) | Obtiene y establece un valor de cadena como separador.|
| [is_multi_encoded](/cells/python-net/es/aspose.cells/txtloadoptions/is_multi_encoded) | Verdadero significa que el archivo contiene varias codificaciones.|
| [preferred_parsers](/cells/python-net/es/aspose.cells/txtloadoptions/preferred_parsers) | Obtiene y establece los analizadores de valores preferidos para cargar archivos de texto.|
| [has_formula](/cells/python-net/es/aspose.cells/txtloadoptions/has_formula) | Indica si el texto es una fórmula si comienza con "=".|
| [has_text_qualifier](/cells/python-net/es/aspose.cells/txtloadoptions/has_text_qualifier) | Si existe un calificador de texto para el valor de la celda. El valor predeterminado es verdadero.|
| [text_qualifier](/cells/python-net/es/aspose.cells/txtloadoptions/text_qualifier) | Especifica el calificador de texto para los valores de celda. El calificador predeterminado es "".|
| [treat_consecutive_delimiters_as_one](/cells/python-net/es/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Si los delimitadores consecutivos deben tratarse como uno solo.|
| [treat_quote_prefix_as_value](/cells/python-net/es/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Indica si el signo de comilla simple inicial debe tomarse como parte del valor de una celda.<br/>El valor predeterminado es verdadero. Si es falso, se eliminará la comilla simple inicial del valor de la celda correspondiente.<br/> y [`Style.quote_prefix`](/cells/python-net/es/aspose.cells/style#quote_prefix) se establecerá como verdadero para la celda.|
| [extend_to_next_sheet](/cells/python-net/es/aspose.cells/txtloadoptions/extend_to_next_sheet) | Si extiende los datos a la siguiente hoja cuando las filas o columnas de datos exceden el límite.<br/> El valor predeterminado es falso.|
| [header_rows_count](/cells/python-net/es/aspose.cells/txtloadoptions/header_rows_count) |El recuento de filas de encabezado que se repetirán para hojas extendidas.|
| [header_columns_count](/cells/python-net/es/aspose.cells/txtloadoptions/header_columns_count) | El recuento de columnas de encabezado que se repetirán para hojas extendidas.|
| [max_row_count](/cells/python-net/es/aspose.cells/txtloadoptions/max_row_count) | El recuento máximo de filas que se importarán para una hoja.|
| [max_column_count](/cells/python-net/es/aspose.cells/txtloadoptions/max_column_count) | El número máximo de columnas que se importarán para una hoja.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/es/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.papersizetype) | Establece el tamaño de papel de impresión predeterminado según la configuración predeterminada de la impresora.|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`AbstractTextLoadOptions`](/cells/python-net/es/aspose.cells/abstracttextloadoptions)
* clase [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)
* clase [`TxtLoadOptions`](/cells/python-net/es/aspose.cells/txtloadoptions)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
