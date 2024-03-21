---
title: NumbersLoadOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.numbers/numbersloadoptions/
is_root: false
---
##  NumbersLoadOptions clase
Representa las opciones de carga de archivos Apple Numbers.



**Herencia:** [`NumbersLoadOptions`](/cells/python-net/aspose.cells.numbers/numbersloadoptions) → 
[`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)



El tipo NumbersLoadOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/__init__/#) | Constructor.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [load_format](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/load_format) | Obtiene el formato de carga.|
| [password](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/password) | Obtiene y establece la contraseña del libro de trabajo.|
| [parsing_formula_on_open](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/parsing_formula_on_open) | Indica si se analiza la fórmula al leer el archivo.|
| [parsing_pivot_cached_records](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/parsing_pivot_cached_records) | Indica si se analizan los registros en caché dinámicos al cargar el archivo.<br/> El valor predeterminado es falso.|
| [language_code](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/language_code) | Obtiene o establece el idioma de la interfaz de usuario de la versión del libro de trabajo según el código de país que guardó el archivo.|
| [region](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/region) |Obtiene o establece la configuración regional del sistema según el código de país en el momento en que se cargó el archivo.|
| [default_style_settings](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/default_style_settings) | Obtiene la configuración de estilo predeterminada para inicializar estilos del libro.|
| [standard_font](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/standard_font) | Establece el nombre de fuente estándar predeterminado|
| [standard_font_size](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/standard_font_size) | Establece el tamaño de fuente estándar predeterminado.|
| [interrupt_monitor](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/interrupt_monitor) | Obtiene y establece el monitor de interrupciones.|
| [ignore_not_printed](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/ignore_not_printed) | Ignore los datos que no se imprimen si imprime directamente el archivo|
| [check_data_valid](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/check_data_valid) | Compruebe si los datos son válidos en el archivo de plantilla.|
| [check_excel_restriction](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/check_excel_restriction) | Si se verifica la restricción del archivo de Excel cuando el usuario modifica los objetos relacionados con las celdas.<br/>Por ejemplo, Excel no permite ingresar un valor de cadena de más de 32 K.<br/>Cuando ingresa un valor superior a 32 KB, como por ejemplo Cell.PutValue(cadena), si esta propiedad es verdadera, obtendrá una excepción.<br/>Si esta propiedad es falsa, aceptaremos el valor de su cadena de entrada como el valor de la celda para que más tarde<br/>puede generar el valor de cadena completo para otros formatos de archivo como CSV.<br/>Sin embargo, si ha establecido un tipo de valor que no es válido para el formato de archivo Excel,<br/> no debe guardar el libro como formato de archivo Excel más adelante. De lo contrario, puede haber un error inesperado en el archivo Excel generado.|
| [keep_unparsed_data](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/keep_unparsed_data) | Si se mantienen los datos no analizados en la memoria para el libro de trabajo cuando se carga desde un archivo de plantilla. El valor predeterminado es verdadero.|
| [load_filter](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/load_filter) | El filtro para indicar cómo cargar datos.|
| [light_cells_data_handler](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/light_cells_data_handler) | El controlador de datos para procesar datos de celdas al leer el archivo de plantilla.|
| [memory_setting](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/memory_setting) | Obtiene o establece las opciones de uso de memoria.|
| [warning_callback](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/warning_callback) | Obtiene o establece una devolución de llamada de advertencia.|
| [auto_fitter_options](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/auto_fitter_options) | Obtiene y establece las opciones del instalador automático.|
| [auto_filter](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/auto_filter) | Indica si se filtran automáticamente los datos al cargar los archivos.|
| [font_configs](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/font_configs) | Obtiene y establece configuraciones de fuentes individuales.<br/> Solo funciona para el [`Workbook`](/cells/python-net/es/aspose.cells/workbook) que usa este [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions) para cargar.|
| [ignore_useless_shapes](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/ignore_useless_shapes) | Indica si se ignoran formas inútiles.|
| [preserve_padding_spaces_in_formula](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/preserve_padding_spaces_in_formula) | Indica si se conservan los espacios y saltos de línea que se rellenan entre los tokens de fórmula.<br/>mientras obtiene y establece fórmulas.<br/> El valor predeterminado es falso.|
| [load_table_type](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/load_table_type) | Obtiene y establece el tipo de carga de varias tablas en una hoja de cálculo.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [set_paper_size](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Establece el tamaño de papel de impresión predeterminado desde la configuración predeterminada de la impresora.|



###  Ver también
* módulo [`aspose.cells.numbers`](..)
* clase [`LoadOptions`](/cells/python-net/es/aspose.cells/loadoptions)
* clase [`NumbersLoadOptions`](/cells/python-net/es/aspose.cells.numbers/numbersloadoptions)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
