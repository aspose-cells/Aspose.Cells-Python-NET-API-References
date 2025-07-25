---
title: Workbook clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1570
url: /es/aspose.cells/workbook/
is_root: false
---
##  Workbook clase
Representa un objeto raíz para crear una hoja de cálculo de Excel.



El tipo Workbook expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/workbook/__init__/#) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook).|
| [`__init__(self, file_format_type)`](/cells/python-net/es/aspose.cells/workbook/__init__/#aspose.cells.fileformattype) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook).|
| [`__init__(self, file)`](/cells/python-net/es/aspose.cells/workbook/__init__/#str) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre un archivo.|
| [`__init__(self, stream)`](/cells/python-net/es/aspose.cells/workbook/__init__/#io.rawiobase) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre un flujo.|
| [`__init__(self, file, load_options)`](/cells/python-net/es/aspose.cells/workbook/__init__/#str-aspose.cells.loadoptions) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre un archivo.|
| [`__init__(self, stream, load_options)`](/cells/python-net/es/aspose.cells/workbook/__init__/#io.rawiobase-aspose.cells.loadoptions) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre el flujo.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [settings](/cells/python-net/es/aspose.cells/workbook/settings) | Representa la configuración del libro.|
| [worksheets](/cells/python-net/es/aspose.cells/workbook/worksheets) | Obtiene la colección [`WorksheetCollection`](/cells/python-net/es/aspose.cells/worksheetcollection) en la hoja de cálculo.|
| [is_licensed](/cells/python-net/es/aspose.cells/workbook/is_licensed) | Indica si la licencia está establecida.|
| [colors](/cells/python-net/es/aspose.cells/workbook/colors) | Devuelve colores en la paleta de la hoja de cálculo.|
| [count_of_styles_in_pool](/cells/python-net/es/aspose.cells/workbook/count_of_styles_in_pool) | Obtiene el número de estilos en el grupo de estilos.|
| [default_style](/cells/python-net/es/aspose.cells/workbook/default_style) | Obtiene o establece el objeto [`Style`](/cells/python-net/es/aspose.cells/style) predeterminado del libro de trabajo.|
| [is_digitally_signed](/cells/python-net/es/aspose.cells/workbook/is_digitally_signed) | Indica si esta hoja de cálculo está firmada digitalmente.|
| [is_workbook_protected_with_password](/cells/python-net/es/aspose.cells/workbook/is_workbook_protected_with_password) | Indica si la estructura o ventana está protegida con contraseña.|
| [vba_project](/cells/python-net/es/aspose.cells/workbook/vba_project) |Obtiene el [`Workbook.vba_project`](/cells/python-net/es/aspose.cells/workbook#vba_project) en una hoja de cálculo.|
| [has_macro](/cells/python-net/es/aspose.cells/workbook/has_macro) | Indica si esta hoja de cálculo contiene macro/VBA.|
| [has_revisions](/cells/python-net/es/aspose.cells/workbook/has_revisions) | Obtiene si el libro de trabajo tiene algún cambio registrado|
| [file_name](/cells/python-net/es/aspose.cells/workbook/file_name) | Obtiene y establece el nombre del archivo actual.|
| [cells_data_table_factory](/cells/python-net/es/aspose.cells/workbook/cells_data_table_factory) | Obtiene la fábrica para crear ICellsDataTable a partir de objetos personalizados|
| [data_sorter](/cells/python-net/es/aspose.cells/workbook/data_sorter) | Obtiene un objeto DataSorter para ordenar datos.|
| [theme](/cells/python-net/es/aspose.cells/workbook/theme) | Obtiene el nombre del tema.|
| [built_in_document_properties](/cells/python-net/es/aspose.cells/workbook/built_in_document_properties) | Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades de documento integradas de la hoja de cálculo.|
| [custom_document_properties](/cells/python-net/es/aspose.cells/workbook/custom_document_properties) | Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades del documento personalizado de la hoja de cálculo.|
| [file_format](/cells/python-net/es/aspose.cells/workbook/file_format) | Obtiene y establece el formato de archivo.|
| [has_custom_function](/cells/python-net/es/aspose.cells/workbook/has_custom_function) | Detecta si se utiliza una función personalizada en este libro de trabajo.<br/> como por ejemplo en la fórmula de la celda, en los nombres definidos...|
| [content_type_properties](/cells/python-net/es/aspose.cells/workbook/content_type_properties) | Obtiene la lista de [`ContentTypeProperty`](/cells/python-net/es/aspose.cells.properties/contenttypeproperty) objetos en el libro de trabajo.|
| [custom_xml_parts](/cells/python-net/es/aspose.cells/workbook/custom_xml_parts) | Representa una parte de almacenamiento de datos XML personalizado (datos XML personalizados dentro de un paquete).|
| [data_mashup](/cells/python-net/es/aspose.cells/workbook/data_mashup) | Obtiene datos combinados.|
| [ribbon_xml](/cells/python-net/es/aspose.cells/workbook/ribbon_xml) | Obtiene y establece el archivo XML que define la interfaz de usuario de la cinta.|
| [absolute_path](/cells/python-net/es/aspose.cells/workbook/absolute_path) | Obtiene y establece la ruta absoluta del archivo.|
| [data_connections](/cells/python-net/es/aspose.cells/workbook/data_connections) |Obtiene la colección ExternalConnection.|
| [data_model](/cells/python-net/es/aspose.cells/workbook/data_model) | Obtiene el modelo de datos en el libro de trabajo.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`save(self, file_name, save_format)`](/cells/python-net/es/aspose.cells/workbook/save/#str-aspose.cells.saveformat) | Guarda el libro de trabajo en el disco.|
| [`save(self, file_name)`](/cells/python-net/es/aspose.cells/workbook/save/#str) | Guarde el libro de trabajo en el disco.|
| [`save(self, file_name, save_options)`](/cells/python-net/es/aspose.cells/workbook/save/#str-aspose.cells.saveoptions) | Guarda el libro de trabajo en el disco.|
| [`save(self, stream, save_format)`](/cells/python-net/es/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveformat) | Guarda el libro de trabajo en la secuencia.|
| [`save(self, stream, save_options)`](/cells/python-net/es/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveoptions) | Guarda el libro de trabajo en la secuencia.|
| [`create_style(self)`](/cells/python-net/es/aspose.cells/workbook/create_style/#) | Crea un nuevo estilo.|
| [`create_style(self, clone_default_style)`](/cells/python-net/es/aspose.cells/workbook/create_style/#bool) | Crea un nuevo estilo.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/es/aspose.cells/workbook/replace/#str-str) | Reemplaza el valor de una celda con una nueva cadena.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/es/aspose.cells/workbook/replace/#str-int) | Reemplaza el valor de una celda con un nuevo entero.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/es/aspose.cells/workbook/replace/#str-float) | Reemplaza el valor de una celda con un nuevo doble.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/es/aspose.cells/workbook/replace/#str-list-bool) | Reemplaza el valor de una celda con una nueva matriz de cadenas.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/es/aspose.cells/workbook/replace/#str-list-bool) | Reemplaza los valores de las celdas con una matriz de números enteros.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/es/aspose.cells/workbook/replace/#str-list-bool) | Reemplaza los valores de las celdas con una matriz doble.|
| [`replace(self, bool_value, new_value)`](/cells/python-net/es/aspose.cells/workbook/replace/#bool-any) | Reemplaza los valores de las celdas con datos nuevos.|
| [`replace(self, int_value, new_value)`](/cells/python-net/es/aspose.cells/workbook/replace/#int-any) | Reemplaza los valores de las celdas con datos nuevos.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/es/aspose.cells/workbook/replace/#str-str-aspose.cells.replaceoptions) | Reemplaza el valor de una celda con una nueva cadena.|
| [`copy(self, source, copy_options)`](/cells/python-net/es/aspose.cells/workbook/copy/#aspose.cells.workbook-aspose.cells.copyoptions) | Copia otro objeto de libro de trabajo.|
| [`copy(self, source)`](/cells/python-net/es/aspose.cells/workbook/copy/#aspose.cells.workbook) | Copia datos de un objeto de libro de trabajo de origen.|
| [`calculate_formula(self)`](/cells/python-net/es/aspose.cells/workbook/calculate_formula/#) | Calcula el resultado de fórmulas.|
| [`calculate_formula(self, ignore_error)`](/cells/python-net/es/aspose.cells/workbook/calculate_formula/#bool) | Calcula el resultado de fórmulas.|
| [`calculate_formula(self, options)`](/cells/python-net/es/aspose.cells/workbook/calculate_formula/#aspose.cells.calculationoptions) | Cálculo de fórmulas en este libro de trabajo.|
| [`refresh_dynamic_array_formulas(self, calculate)`](/cells/python-net/es/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Actualiza fórmulas de matriz dinámica (se extienden a un nuevo rango de celdas vecinas según los datos actuales)<br/> Otras fórmulas del libro de trabajo no se calcularán de forma recursiva incluso si se utilizan mediante fórmulas de matriz dinámica.|
| [`refresh_dynamic_array_formulas(self, calculate, copts)`](/cells/python-net/es/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.calculationoptions) |Actualiza fórmulas de matriz dinámica (se extienden a un nuevo rango de celdas vecinas según los datos actuales)|
| [`import_xml(self, url, sheet_name, row, col)`](/cells/python-net/es/aspose.cells/workbook/import_xml/#str-str-int-int) | Importa/actualiza un archivo de datos XML en el libro de trabajo.|
| [`import_xml(self, stream, sheet_name, row, col)`](/cells/python-net/es/aspose.cells/workbook/import_xml/#io.rawiobase-str-int-int) | Importa/actualiza un archivo de datos XML en el libro de trabajo.|
| [`export_xml(self, map_name, path)`](/cells/python-net/es/aspose.cells/workbook/export_xml/#str-str) | Exportar datos XML vinculados por el mapa XML especificado.|
| [`export_xml(self, map_name, stream)`](/cells/python-net/es/aspose.cells/workbook/export_xml/#str-io.rawiobase) | Exportar datos XML.|
| [`parse_formulas(self, ignore_error)`](/cells/python-net/es/aspose.cells/workbook/parse_formulas/#bool) | Analiza todas las fórmulas que no se analizaron cuando se cargaron desde un archivo de plantilla o se establecieron en una celda.|
| [`start_access_cache(self, opts)`](/cells/python-net/es/aspose.cells/workbook/start_access_cache/#aspose.cells.accesscacheoptions) | Inicia la sesión que utiliza cachés para acceder a los datos.|
| [`close_access_cache(self, opts)`](/cells/python-net/es/aspose.cells/workbook/close_access_cache/#aspose.cells.accesscacheoptions) | Cierra la sesión que utiliza cachés para acceder a los datos.|
| [`remove_unused_styles(self)`](/cells/python-net/es/aspose.cells/workbook/remove_unused_styles/#) | Eliminar todos los estilos no utilizados.|
| [`create_builtin_style(self, type)`](/cells/python-net/es/aspose.cells/workbook/create_builtin_style/#aspose.cells.builtinstyletype) | Crea un estilo integrado según el tipo dado.|
| [`create_cells_color(self)`](/cells/python-net/es/aspose.cells/workbook/create_cells_color/#) | Crea un objeto [`CellsColor`](/cells/python-net/es/aspose.cells/cellscolor).|
| [`combine(self, second_workbook)`](/cells/python-net/es/aspose.cells/workbook/combine/#aspose.cells.workbook) | Combina otro objeto de libro de trabajo.|
| [`get_style_in_pool(self, index)`](/cells/python-net/es/aspose.cells/workbook/get_style_in_pool/#int) | Obtiene el estilo en el grupo de estilos.<br/>Todos los estilos del libro de trabajo se reunirán en un grupo.<br/> Sólo hay un índice de referencia simple en las celdas.|
| [`get_fonts(self)`](/cells/python-net/es/aspose.cells/workbook/get_fonts/#) | Obtiene todas las fuentes en el grupo de estilos.|
| [`get_named_style(self, name)`](/cells/python-net/es/aspose.cells/workbook/get_named_style/#str) | Obtiene el estilo nombrado en el grupo de estilos.|
| [`merge_named_styles(self, source)`](/cells/python-net/es/aspose.cells/workbook/merge_named_styles/#aspose.cells.workbook) | Fusiona estilos con nombre del otro archivo Excel.|
| [`change_palette(self, color, index)`](/cells/python-net/es/aspose.cells/workbook/change_palette/#aspose.pydrawing.color-int) | Cambia la paleta de la hoja de cálculo en el índice especificado.|
| [`is_color_in_palette(self, color)`](/cells/python-net/es/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.color) | Comprueba si un color está en la paleta de la hoja de cálculo.|
| [`get_matching_color(self, raw_color)`](/cells/python-net/es/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.color) |Encuentre el color que mejor coincida en la paleta actual.|
| [`set_encryption_options(self, encryption_type, key_length)`](/cells/python-net/es/aspose.cells/workbook/set_encryption_options/#aspose.cells.encryptiontype-int) | Establecer opciones de cifrado.|
| [`protect(self, protection_type, password)`](/cells/python-net/es/aspose.cells/workbook/protect/#aspose.cells.protectiontype-str) | Protege un libro de trabajo.|
| [`protect_shared_workbook(self, password)`](/cells/python-net/es/aspose.cells/workbook/protect_shared_workbook/#str) | Protege un libro de trabajo compartido.|
| [`unprotect(self, password)`](/cells/python-net/es/aspose.cells/workbook/unprotect/#str) | Desprotege un libro de trabajo.|
| [`unprotect_shared_workbook(self, password)`](/cells/python-net/es/aspose.cells/workbook/unprotect_shared_workbook/#str) | Desprotege un libro de trabajo compartido.|
| [`remove_macro(self)`](/cells/python-net/es/aspose.cells/workbook/remove_macro/#) | Elimina VBA/macro de esta hoja de cálculo.|
| [`remove_digital_signature(self)`](/cells/python-net/es/aspose.cells/workbook/remove_digital_signature/#) | Elimina la firma digital de esta hoja de cálculo.|
| [`accept_all_revisions(self)`](/cells/python-net/es/aspose.cells/workbook/accept_all_revisions/#) | Acepta todos los cambios rastreados en el libro de trabajo.|
| [`remove_external_links(self)`](/cells/python-net/es/aspose.cells/workbook/remove_external_links/#) | Elimina todos los enlaces externos en el libro de trabajo.|
| [`get_theme_color(self, type)`](/cells/python-net/es/aspose.cells/workbook/get_theme_color/#aspose.cells.themecolortype) | Obtiene el color del tema.|
| [`set_theme_color(self, type, color)`](/cells/python-net/es/aspose.cells/workbook/set_theme_color/#aspose.cells.themecolortype-aspose.pydrawing.color) | Establece el color del tema|
| [`custom_theme(self, theme_name, colors)`](/cells/python-net/es/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.color[]) | Costumbres del tema.|
| [`copy_theme(self, source)`](/cells/python-net/es/aspose.cells/workbook/copy_theme/#aspose.cells.workbook) | Copia el tema de otro libro de trabajo.|
| [`has_exernal_links(self)`](/cells/python-net/es/aspose.cells/workbook/has_exernal_links/#) | Indica si este libro de trabajo contiene enlaces externos a otras fuentes de datos.|
| [`update_custom_function_definition(self, definition)`](/cells/python-net/es/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.customfunctiondefinition) | Actualiza la definición de funciones personalizadas.|
| [`update_linked_data_source(self, external_workbooks)`](/cells/python-net/es/aspose.cells/workbook/update_linked_data_source/#list) | Si este libro de trabajo contiene enlaces externos a otras fuentes de datos,<br/> Aspose.Cells intentará recuperar los datos más recientes de las fuentes proporcionadas.|
| [`set_digital_signature(self, digital_signature_collection)`](/cells/python-net/es/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Establece una firma digital en un archivo de hoja de cálculo (Excel 2007 y posterior).|
| [`add_digital_signature(self, digital_signature_collection)`](/cells/python-net/es/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Agrega una firma digital a un archivo de hoja de cálculo OOXML (Excel2007 y posteriores).|
| [`get_digital_signature(self)`](/cells/python-net/es/aspose.cells/workbook/get_digital_signature/#) |Obtiene la firma digital del archivo.|
| [`remove_personal_information(self)`](/cells/python-net/es/aspose.cells/workbook/remove_personal_information/#) | Elimina información personal.|
| [`close(self)`](/cells/python-net/es/aspose.cells/workbook/close/#) | Dispose() es omitido por el contenedor desde el protocolo Python|



###  Observaciones

La clase Workbook corresponde a una hoja de cálculo de Excel. Cada hoja de cálculo puede contener varias hojas de cálculo.
La característica básica de la clase es abrir y guardar archivos nativos de Excel.
La clase tiene algunas funciones avanzadas como copiar datos de otros libros de trabajo, combinar dos libros de trabajo, convertir Excel a PDF, convertir Excel a imagen y proteger la hoja de cálculo de Excel.

###  Ejemplo

El siguiente ejemplo carga un Workbook desde un archivo Excel llamado designer.xls y hace invisibles las barras de desplazamiento horizontal y vertical.
 Luego reemplaza dos valores de cadena con un valor entero y un valor de cadena respectivamente dentro de la hoja de cálculo y finalmente guarda el libro como archivo xlsx de Excel.

```python
from aspose.cells import Workbook

# Open a designer file
designerFile = "designer.xls"
workbook = Workbook(designerFile)
# Set scroll bars
workbook.settings.is_h_scroll_bar_visible = False
workbook.settings.is_v_scroll_bar_visible = False
# Replace the placeholder string with new values
newInt = 100
workbook.replace("OldInt", newInt)
newString = "Hello!"
workbook.replace("OldString", newString)
workbook.save("result.xlsx")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`CellsColor`](/cells/python-net/es/aspose.cells/cellscolor)
* clase [`ContentTypeProperty`](/cells/python-net/es/aspose.cells.properties/contenttypeproperty)
* clase [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty)
* clase [`Style`](/cells/python-net/es/aspose.cells/style)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
* clase [`WorksheetCollection`](/cells/python-net/es/aspose.cells/worksheetcollection)
