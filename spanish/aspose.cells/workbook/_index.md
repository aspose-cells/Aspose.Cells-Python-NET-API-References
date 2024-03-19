---
title: Workbook clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1660
url: /es/aspose.cells/workbook/
is_root: false
---
##  Workbook clase
Representa un objeto raíz para crear una hoja de cálculo de Excel.



El tipo Workbook expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/workbook/__init__/#) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook).|
| [__init__](/cells/python-net/es/aspose.cells/workbook/__init__/#aspose.cells.FileFormatType) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook).|
| [__init__](/cells/python-net/es/aspose.cells/workbook/__init__/#str) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre un archivo.|
| [__init__](/cells/python-net/es/aspose.cells/workbook/__init__/#io.RawIOBase) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre una secuencia.|
| [__init__](/cells/python-net/es/aspose.cells/workbook/__init__/#str-aspose.cells.LoadOptions) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre un archivo.|
| [__init__](/cells/python-net/es/aspose.cells/workbook/__init__/#io.RawIOBase-aspose.cells.LoadOptions) | Inicializa una nueva instancia de la clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook) y abre una secuencia.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [settings](/cells/python-net/es/aspose.cells/workbook/settings) | Representa la configuración del libro.|
| [worksheets](/cells/python-net/es/aspose.cells/workbook/worksheets) | Obtiene la colección [`WorksheetCollection`](/cells/python-net/es/aspose.cells/worksheetcollection) en la hoja de cálculo.|
| [is_licensed](/cells/python-net/es/aspose.cells/workbook/is_licensed) | Indica si la licencia está configurada.|
| [colors](/cells/python-net/es/aspose.cells/workbook/colors) | Devuelve colores en la paleta de la hoja de cálculo.|
| [count_of_styles_in_pool](/cells/python-net/es/aspose.cells/workbook/count_of_styles_in_pool) | Obtiene el número de estilos en el grupo de estilos.|
| [default_style](/cells/python-net/es/aspose.cells/workbook/default_style) |Obtiene o establece el objeto [`Style`](/cells/python-net/es/aspose.cells/style) predeterminado del libro.|
| [is_digitally_signed](/cells/python-net/es/aspose.cells/workbook/is_digitally_signed) | Indica si esta hoja de cálculo está firmada digitalmente.|
| [is_workbook_protected_with_password](/cells/python-net/es/aspose.cells/workbook/is_workbook_protected_with_password) | Indica si la estructura o ventana está protegida con contraseña.|
| [vba_project](/cells/python-net/es/aspose.cells/workbook/vba_project) | Obtiene el [`Workbook.vba_project`](/cells/python-net/es/aspose.cells/workbook#vba_project) en una hoja de cálculo.|
| [has_macro](/cells/python-net/es/aspose.cells/workbook/has_macro) | Indica si esta hoja de cálculo contiene macro/VBA.|
| [has_revisions](/cells/python-net/es/aspose.cells/workbook/has_revisions) | Obtiene si el libro tiene algún cambio registrado|
| [file_name](/cells/python-net/es/aspose.cells/workbook/file_name) | Obtiene y establece el nombre del archivo actual.|
| [cells_data_table_factory](/cells/python-net/es/aspose.cells/workbook/cells_data_table_factory) | Obtiene la fábrica para construir ICellsDataTable a partir de objetos personalizados.|
| [data_sorter](/cells/python-net/es/aspose.cells/workbook/data_sorter) | Obtiene un objeto DataSorter para ordenar datos.|
| [theme](/cells/python-net/es/aspose.cells/workbook/theme) | Obtiene el nombre del tema.|
| [built_in_document_properties](/cells/python-net/es/aspose.cells/workbook/built_in_document_properties) | Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades del documento integrado de la hoja de cálculo.|
| [custom_document_properties](/cells/python-net/es/aspose.cells/workbook/custom_document_properties) | Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades del documento personalizado de la hoja de cálculo.|
| [file_format](/cells/python-net/es/aspose.cells/workbook/file_format) | Obtiene y establece el formato del archivo.|
| [interrupt_monitor](/cells/python-net/es/aspose.cells/workbook/interrupt_monitor) | Obtiene y establece el monitor de interrupciones.|
| [content_type_properties](/cells/python-net/es/aspose.cells/workbook/content_type_properties) | Obtiene la lista de [`ContentTypeProperty`](/cells/python-net/es/aspose.cells.properties/contenttypeproperty) objetos del libro.|
| [custom_xml_parts](/cells/python-net/es/aspose.cells/workbook/custom_xml_parts) | Representa una parte de almacenamiento de datos XML personalizado (datos XML personalizados dentro de un paquete).|
| [data_mashup](/cells/python-net/es/aspose.cells/workbook/data_mashup) | Obtiene datos de combinación.|
| [ribbon_xml](/cells/python-net/es/aspose.cells/workbook/ribbon_xml) |Obtiene y establece el archivo XML que define la interfaz de usuario de la cinta.|
| [absolute_path](/cells/python-net/es/aspose.cells/workbook/absolute_path) | Obtiene y establece la ruta absoluta del archivo.|
| [data_connections](/cells/python-net/es/aspose.cells/workbook/data_connections) | Obtiene la colección [`ExternalConnection`](/cells/python-net/es/aspose.cells.externalconnections/externalconnection).|


###  Métodos
| Método| Descripción|
| :- | :- |
| [save](/cells/python-net/es/aspose.cells/workbook/save/#str-aspose.cells.SaveFormat) | Guarda el libro de trabajo en el disco.|
| [save](/cells/python-net/es/aspose.cells/workbook/save/#str) | Guarde el libro en el disco.|
| [save](/cells/python-net/es/aspose.cells/workbook/save/#str-aspose.cells.SaveOptions) | Guarda el libro de trabajo en el disco.|
| [save](/cells/python-net/es/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveFormat) | Guarda el libro de trabajo en la secuencia.|
| [save](/cells/python-net/es/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveOptions) | Guarda el libro de trabajo en la secuencia.|
| [replace](/cells/python-net/es/aspose.cells/workbook/replace/#str-str) | Reemplaza el valor de una celda con una nueva cadena.|
| [replace](/cells/python-net/es/aspose.cells/workbook/replace/#str-int) | Reemplaza el valor de una celda con un nuevo número entero.|
| [replace](/cells/python-net/es/aspose.cells/workbook/replace/#str-float) | Reemplaza el valor de una celda con un nuevo doble.|
| [replace](/cells/python-net/es/aspose.cells/workbook/replace/#str-list-bool) | Reemplaza el valor de una celda con una nueva matriz de cadenas.|
| [replace](/cells/python-net/es/aspose.cells/workbook/replace/#str-list-bool) | Reemplaza los valores de las celdas con una matriz de números enteros.|
| [replace](/cells/python-net/es/aspose.cells/workbook/replace/#str-list-bool) | Reemplaza los valores de las celdas con una matriz doble.|
| [replace](/cells/python-net/es/aspose.cells/workbook/replace/#bool-any) | Reemplaza los valores de las celdas con nuevos datos.|
| [replace](/cells/python-net/es/aspose.cells/workbook/replace/#int-any) | Reemplaza los valores de las celdas con nuevos datos.|
| [replace](/cells/python-net/es/aspose.cells/workbook/replace/#str-str-aspose.cells.ReplaceOptions) | Reemplaza el valor de una celda con una nueva cadena.|
| [copy](/cells/python-net/es/aspose.cells/workbook/copy/#aspose.cells.Workbook-aspose.cells.CopyOptions) | Copia otro objeto de libro de trabajo.|
| [copy](/cells/python-net/es/aspose.cells/workbook/copy/#aspose.cells.Workbook) | Copia datos de un objeto Libro de trabajo de origen.|
| [calculate_formula](/cells/python-net/es/aspose.cells/workbook/calculate_formula/#) | Calcula el resultado de fórmulas.|
| [calculate_formula](/cells/python-net/es/aspose.cells/workbook/calculate_formula/#bool) | Calcula el resultado de fórmulas.|
| [calculate_formula](/cells/python-net/es/aspose.cells/workbook/calculate_formula/#aspose.cells.CalculationOptions) | Calcular fórmulas en este libro de trabajo.|
| [refresh_dynamic_array_formulas](/cells/python-net/es/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Actualiza las fórmulas de matriz dinámica (se extiende a un nuevo rango de celdas vecinas según los datos actuales)<br/>Otras fórmulas del libro de trabajo no se calcularán de forma recursiva incluso si fueron utilizadas por fórmulas de matriz dinámica.|
| [refresh_dynamic_array_formulas](/cells/python-net/es/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.CalculationOptions) | Actualiza las fórmulas de matriz dinámica (se extiende a un nuevo rango de celdas vecinas según los datos actuales)|
| [import_xml](/cells/python-net/es/aspose.cells/workbook/import_xml/#str-str-int-int) | Importa/actualiza un archivo de datos XML en el libro de trabajo.|
| [import_xml](/cells/python-net/es/aspose.cells/workbook/import_xml/#io.RawIOBase-str-int-int) | Importa/actualiza un archivo de datos XML en el libro de trabajo.|
| [export_xml](/cells/python-net/es/aspose.cells/workbook/export_xml/#str-str) | Exporte datos XML vinculados por el mapa XML especificado.|
| [export_xml](/cells/python-net/es/aspose.cells/workbook/export_xml/#str-io.RawIOBase) | Exportar datos XML.|
| [parse_formulas](/cells/python-net/es/aspose.cells/workbook/parse_formulas/#bool) | Analiza todas las fórmulas que no se analizaron cuando se cargaron desde un archivo de plantilla o se configuraron en una celda.|
| [start_access_cache](/cells/python-net/es/aspose.cells/workbook/start_access_cache/#aspose.cells.AccessCacheOptions) | Inicia la sesión que utiliza cachés para acceder a los datos.|
| [close_access_cache](/cells/python-net/es/aspose.cells/workbook/close_access_cache/#aspose.cells.AccessCacheOptions) | Cierra la sesión que utiliza cachés para acceder a los datos.|
| [remove_unused_styles](/cells/python-net/es/aspose.cells/workbook/remove_unused_styles/#) | Elimine todos los estilos no utilizados.|
| [create_style](/cells/python-net/es/aspose.cells/workbook/create_style/#) | Crea un nuevo estilo.|
| [create_builtin_style](/cells/python-net/es/aspose.cells/workbook/create_builtin_style/#aspose.cells.BuiltinStyleType) | Crea un estilo integrado por tipo determinado.|
| [create_cells_color](/cells/python-net/es/aspose.cells/workbook/create_cells_color/#) | Crea un objeto [`CellsColor`](/cells/python-net/es/aspose.cells/cellscolor).|
| [combine](/cells/python-net/es/aspose.cells/workbook/combine/#aspose.cells.Workbook) | Combina otro objeto de libro de trabajo.|
| [get_style_in_pool](/cells/python-net/es/aspose.cells/workbook/get_style_in_pool/#int) | Obtiene el estilo en el grupo de estilos.<br/>Todos los estilos del libro de trabajo se reunirán en un grupo.<br/> Sólo hay un índice de referencia simple en las celdas.|
| [get_fonts](/cells/python-net/es/aspose.cells/workbook/get_fonts/#) | Obtiene todas las fuentes del grupo de estilos.|
| [get_named_style](/cells/python-net/es/aspose.cells/workbook/get_named_style/#str) | Obtiene el estilo con nombre en el grupo de estilos.|
| [change_palette](/cells/python-net/es/aspose.cells/workbook/change_palette/#aspose.pydrawing.Color-int) |Cambia la paleta de la hoja de cálculo en el índice especificado.|
| [is_color_in_palette](/cells/python-net/es/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.Color) | Comprueba si un color está en la paleta de la hoja de cálculo.|
| [get_matching_color](/cells/python-net/es/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.Color) | Encuentre el color que mejor combine en la paleta actual.|
| [set_encryption_options](/cells/python-net/es/aspose.cells/workbook/set_encryption_options/#aspose.cells.EncryptionType-int) | Establezca las opciones de cifrado.|
| [protect](/cells/python-net/es/aspose.cells/workbook/protect/#aspose.cells.ProtectionType-str) | Protege un libro de trabajo.|
| [protect_shared_workbook](/cells/python-net/es/aspose.cells/workbook/protect_shared_workbook/#str) | Protege un libro compartido.|
| [unprotect](/cells/python-net/es/aspose.cells/workbook/unprotect/#str) | Desprotege un libro de trabajo.|
| [unprotect_shared_workbook](/cells/python-net/es/aspose.cells/workbook/unprotect_shared_workbook/#str) | Desprotege un libro compartido.|
| [remove_macro](/cells/python-net/es/aspose.cells/workbook/remove_macro/#) | Elimina VBA/macro de esta hoja de cálculo.|
| [remove_digital_signature](/cells/python-net/es/aspose.cells/workbook/remove_digital_signature/#) | Elimina la firma digital de esta hoja de cálculo.|
| [accept_all_revisions](/cells/python-net/es/aspose.cells/workbook/accept_all_revisions/#) | Acepta todos los cambios rastreados en el libro de trabajo.|
| [remove_external_links](/cells/python-net/es/aspose.cells/workbook/remove_external_links/#) | Elimina todos los enlaces externos del libro de trabajo.|
| [get_theme_color](/cells/python-net/es/aspose.cells/workbook/get_theme_color/#aspose.cells.ThemeColorType) | Obtiene el color del tema.|
| [set_theme_color](/cells/python-net/es/aspose.cells/workbook/set_theme_color/#aspose.cells.ThemeColorType-aspose.pydrawing.Color) | Establece el color del tema|
| [custom_theme](/cells/python-net/es/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.Color[]) | Aduana el tema.|
| [copy_theme](/cells/python-net/es/aspose.cells/workbook/copy_theme/#aspose.cells.Workbook) | Copia el tema de otro libro de trabajo.|
| [has_exernal_links](/cells/python-net/es/aspose.cells/workbook/has_exernal_links/#) | Indica si este libro contiene enlaces externos a otras fuentes de datos.|
| [update_custom_function_definition](/cells/python-net/es/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.CustomFunctionDefinition) | Actualiza la definición de funciones personalizadas.|
| [update_linked_data_source](/cells/python-net/es/aspose.cells/workbook/update_linked_data_source/#list) | Si este libro contiene enlaces externos a otras fuentes de datos,<br/> Aspose.Cells intentará recuperar los datos más recientes de las fuentes proporcionadas.|
| [set_digital_signature](/cells/python-net/es/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) |Establece la firma digital en un archivo de hoja de cálculo (Excel2007 y posterior).|
| [add_digital_signature](/cells/python-net/es/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) | Agrega firma digital a un archivo de hoja de cálculo OOXML (Excel2007 y posterior).|
| [get_digital_signature](/cells/python-net/es/aspose.cells/workbook/get_digital_signature/#) | Obtiene la firma digital del archivo.|
| [remove_personal_information](/cells/python-net/es/aspose.cells/workbook/remove_personal_information/#) | Elimina información personal.|



###  Observaciones

La clase Workbook denota una hoja de cálculo de Excel. Cada hoja de cálculo puede contener varias hojas de trabajo.
La característica básica de la clase es abrir y guardar archivos nativos de Excel.
La clase tiene algunas funciones avanzadas como copiar datos de otros libros de trabajo, combinar dos libros de trabajo, convertir Excel a PDF, representar Excel en imágenes y proteger la hoja de cálculo de Excel.

###  Ejemplo

El siguiente ejemplo carga un Workbook desde un archivo de Excel llamado designer.xls y hace que las barras de desplazamiento horizontal y vertical sean invisibles.
 Luego reemplaza dos valores de cadena con un valor entero y un valor de cadena respectivamente dentro de la hoja de cálculo y finalmente guarda el libro como un archivo Excel xlsx.

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
* clase [`ExternalConnection`](/cells/python-net/es/aspose.cells.externalconnections/externalconnection)
* clase [`Style`](/cells/python-net/es/aspose.cells/style)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
* clase [`WorksheetCollection`](/cells/python-net/es/aspose.cells/worksheetcollection)
