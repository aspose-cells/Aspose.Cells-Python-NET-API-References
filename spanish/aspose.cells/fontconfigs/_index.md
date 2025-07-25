---
title: FontConfigs clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 670
url: /es/aspose.cells/fontconfigs/
is_root: false
---
##  FontConfigs clase
Especifica la configuración de fuente



El tipo FontConfigs expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/fontconfigs/__init__/#) | Construye una nueva instancia de FontConfigs|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [default_font_name](/cells/python-net/es/aspose.cells/fontconfigs/default_font_name) | Obtiene o establece el nombre de fuente predeterminado.|
| [prefer_system_font_substitutes](/cells/python-net/es/aspose.cells/fontconfigs/prefer_system_font_substitutes) | Indique si se deben utilizar primero los sustitutos de fuentes del sistema o no cuando no se presenta una fuente y el sustituto de esta fuente no está configurado.<br/>Por ejemplo en Ubuntu, la fuente "Arial" generalmente se sustituye por "Liberation Sans".<br/> El valor predeterminado es falso.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`is_font_available(, font_name)`](/cells/python-net/es/aspose.cells/fontconfigs/is_font_available/#str) | Indique si la fuente está disponible.|
| [`get_font_file_data_info(, font_name, is_bold, is_italic, is_exact_style)`](/cells/python-net/es/aspose.cells/fontconfigs/get_font_file_data_info/#str-bool-bool-bool) | Obtener información de datos del archivo de fuente.|
| [`set_font_substitutes(, original_font_name, substitute_font_names)`](/cells/python-net/es/aspose.cells/fontconfigs/set_font_substitutes/#str-list) | Nombres sustitutos de fuentes para el nombre de fuente original dado.|
| [`get_font_substitutes(, original_font_name)`](/cells/python-net/es/aspose.cells/fontconfigs/get_font_substitutes/#str) |Devuelve una matriz que contiene nombres de fuentes sustitutas que se utilizarán si no se presenta la fuente original.|
| [`set_font_folder(, font_folder, recursive)`](/cells/python-net/es/aspose.cells/fontconfigs/set_font_folder/#str-bool) | Establece la carpeta de fuentes|
| [`set_font_folders(, font_folders, recursive)`](/cells/python-net/es/aspose.cells/fontconfigs/set_font_folders/#list-bool) | Establece las carpetas de fuentes.|
| [`set_font_sources(, sources)`](/cells/python-net/es/aspose.cells/fontconfigs/set_font_sources/#list) |  |
| [`get_font_sources()`](/cells/python-net/es/aspose.cells/fontconfigs/get_font_sources/#) | Obtiene una copia de la matriz que contiene la lista de fuentes|



###  Ver también
* módulo [`aspose.cells`](..)
