---
title: HtmlLoadOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 800
url: /es/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions clase
Representa opciones al importar un archivo html.



**Herencia:** [`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)



El tipo HtmlLoadOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/htmlloadoptions/__init__/#) | Crea una opción para cargar el archivo.|
| [__init__](/cells/python-net/es/aspose.cells/htmlloadoptions/__init__/#aspose.cells.LoadFormat) | Crea una opción para cargar el archivo.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [load_format](/cells/python-net/es/aspose.cells/htmlloadoptions/load_format) | Obtiene el formato de carga.|
| [password](/cells/python-net/es/aspose.cells/htmlloadoptions/password) | Obtiene y establece la contraseña del libro de trabajo.|
| [parsing_formula_on_open](/cells/python-net/es/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Indica si se analiza la fórmula al leer el archivo.|
| [parsing_pivot_cached_records](/cells/python-net/es/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Indica si se analizan los registros en caché dinámicos al cargar el archivo.<br/> El valor predeterminado es falso.|
| [language_code](/cells/python-net/es/aspose.cells/htmlloadoptions/language_code) | Obtiene o establece el idioma de la interfaz de usuario de la versión del libro de trabajo según el código de país que guardó el archivo.|
| [region](/cells/python-net/es/aspose.cells/htmlloadoptions/region) |Obtiene o establece la configuración regional del sistema según el código de país en el momento en que se cargó el archivo.|
| [default_style_settings](/cells/python-net/es/aspose.cells/htmlloadoptions/default_style_settings) | Obtiene la configuración de estilo predeterminada para inicializar estilos del libro.|
| [standard_font](/cells/python-net/es/aspose.cells/htmlloadoptions/standard_font) | Establece el nombre de fuente estándar predeterminado|
| [standard_font_size](/cells/python-net/es/aspose.cells/htmlloadoptions/standard_font_size) | Establece el tamaño de fuente estándar predeterminado.|
| [interrupt_monitor](/cells/python-net/es/aspose.cells/htmlloadoptions/interrupt_monitor) | Obtiene y establece el monitor de interrupciones.|
| [ignore_not_printed](/cells/python-net/es/aspose.cells/htmlloadoptions/ignore_not_printed) | Ignore los datos que no se imprimen si imprime directamente el archivo|
| [check_data_valid](/cells/python-net/es/aspose.cells/htmlloadoptions/check_data_valid) | Compruebe si los datos son válidos en el archivo de plantilla.|
| [check_excel_restriction](/cells/python-net/es/aspose.cells/htmlloadoptions/check_excel_restriction) | Si se verifica la restricción del archivo de Excel cuando el usuario modifica los objetos relacionados con las celdas.<br/>Por ejemplo, Excel no permite ingresar un valor de cadena de más de 32 K.<br/>Cuando ingresa un valor superior a 32 KB, como por ejemplo Cell.PutValue(cadena), si esta propiedad es verdadera, obtendrá una excepción.<br/>Si esta propiedad es falsa, aceptaremos el valor de su cadena de entrada como el valor de la celda para que más tarde<br/>puede generar el valor de cadena completo para otros formatos de archivo como CSV.<br/>Sin embargo, si ha establecido un tipo de valor que no es válido para el formato de archivo Excel,<br/> no debe guardar el libro como formato de archivo Excel más adelante. De lo contrario, puede haber un error inesperado en el archivo Excel generado.|
| [keep_unparsed_data](/cells/python-net/es/aspose.cells/htmlloadoptions/keep_unparsed_data) | Si se mantienen los datos no analizados en la memoria para el libro de trabajo cuando se carga desde un archivo de plantilla. El valor predeterminado es verdadero.|
| [load_filter](/cells/python-net/es/aspose.cells/htmlloadoptions/load_filter) | El filtro para indicar cómo cargar datos.|
| [light_cells_data_handler](/cells/python-net/es/aspose.cells/htmlloadoptions/light_cells_data_handler) | El controlador de datos para procesar datos de celdas al leer el archivo de plantilla.|
| [memory_setting](/cells/python-net/es/aspose.cells/htmlloadoptions/memory_setting) | Obtiene o establece las opciones de uso de memoria.|
| [warning_callback](/cells/python-net/es/aspose.cells/htmlloadoptions/warning_callback) | Obtiene o establece una devolución de llamada de advertencia.|
| [auto_fitter_options](/cells/python-net/es/aspose.cells/htmlloadoptions/auto_fitter_options) | Obtiene y establece las opciones del instalador automático.|
| [auto_filter](/cells/python-net/es/aspose.cells/htmlloadoptions/auto_filter) | Indica si se filtran automáticamente los datos al cargar los archivos.|
| [font_configs](/cells/python-net/es/aspose.cells/htmlloadoptions/font_configs) | Obtiene y establece configuraciones de fuentes individuales.<br/> Solo funciona para el [`Workbook`](/cells/python-net/es/aspose.cells/workbook) que usa este [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions) para cargar.|
| [ignore_useless_shapes](/cells/python-net/es/aspose.cells/htmlloadoptions/ignore_useless_shapes) | Indica si se ignoran formas inútiles.|
| [preserve_padding_spaces_in_formula](/cells/python-net/es/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | Indica si se conservan los espacios y saltos de línea que se rellenan entre los tokens de fórmula.<br/>mientras obtiene y establece fórmulas.<br/> El valor predeterminado es falso.|
| [encoding](/cells/python-net/es/aspose.cells/htmlloadoptions/encoding) |Obtiene y establece la codificación predeterminada. Sólo aplica para archivo csv.|
| [load_style_strategy](/cells/python-net/es/aspose.cells/htmlloadoptions/load_style_strategy) | Indica la estrategia para aplicar estilo a los valores analizados al convertir un valor de cadena en número o fecha y hora.|
| [convert_numeric_data](/cells/python-net/es/aspose.cells/htmlloadoptions/convert_numeric_data) | Obtiene o establece un valor que indica si la cadena del archivo de texto se convierte en datos numéricos.|
| [convert_date_time_data](/cells/python-net/es/aspose.cells/htmlloadoptions/convert_date_time_data) | Obtiene o establece un valor que indica si la cadena del archivo de texto se convierte en datos de fecha.|
| [keep_precision](/cells/python-net/es/aspose.cells/htmlloadoptions/keep_precision) | Indica si no se analiza un valor de cadena si la longitud es 15.|
| [attached_files_directory](/cells/python-net/es/aspose.cells/htmlloadoptions/attached_files_directory) | El directorio en el que se guardarán los archivos adjuntos.|
| [load_formulas](/cells/python-net/es/aspose.cells/htmlloadoptions/load_formulas) | Indica si se importan fórmulas si el archivo html original contiene fórmulas|
| [support_div_tag](/cells/python-net/es/aspose.cells/htmlloadoptions/support_div_tag) |Indica si se admite el diseño de la etiqueta `<div>` cuando el archivo html la contiene.<br/> El valor predeterminado es falso.|
| [delete_redundant_spaces](/cells/python-net/es/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Indica si se eliminan los espacios redundantes cuando el texto ajusta líneas usando la etiqueta `<br>`.<br/> El valor predeterminado es falso.|
| [auto_fit_cols_and_rows](/cells/python-net/es/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Indica si las columnas y filas se ajustan automáticamente. El valor predeterminado es falso.|
| [convert_formulas_data](/cells/python-net/es/aspose.cells/htmlloadoptions/convert_formulas_data) | si es verdadero, convierta la cadena en fórmula cuando el valor de la cadena comience con el carácter '=', el valor predeterminado es falso.|
| [has_formula](/cells/python-net/es/aspose.cells/htmlloadoptions/has_formula) | Indica si el texto es fórmula si comienza con "=".|
| [stream_provider](/cells/python-net/es/aspose.cells/htmlloadoptions/stream_provider) | Obtiene o establece StreamProviderImportHtmlFile para importar objetos.|
| [prog_id](/cells/python-net/es/aspose.cells/htmlloadoptions/prog_id) | Obtiene la identificación del programa para crear el archivo.<br/> Sólo para archivos MHT.|
| [table_load_options](/cells/python-net/es/aspose.cells/htmlloadoptions/table_load_options) | Obtenga la instancia de HtmlTableLoadOptionCollection|


###  Métodos
| Método| Descripción|
| :- | :- |
| [set_paper_size](/cells/python-net/es/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Establece el tamaño de papel de impresión predeterminado desde la configuración predeterminada de la impresora.|



###  Ver también
* módulo [`aspose.cells`](..)
* clase [`AbstractTextLoadOptions`](/cells/python-net/es/aspose.cells/abstracttextloadoptions)
* clase [`HtmlLoadOptions`](/cells/python-net/es/aspose.cells/htmlloadoptions)
* clase [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
