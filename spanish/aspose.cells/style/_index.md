---
title: Style clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1350
url: /es/aspose.cells/style/
is_root: false
---
##  Style clase
Representa el estilo de visualización del documento de Excel, como fuente, color, alineación, borde, etc.
El objeto Style contiene todos los atributos de estilo (fuente, formato de número, alineación, etc.) como propiedades.



El tipo Style expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/style/__init__/#) | Inicializa una nueva instancia de la clase [`Style`](/cells/python-net/es/aspose.cells/style).|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [background_theme_color](/cells/python-net/es/aspose.cells/style/background_theme_color) | Obtiene y establece el color del tema de fondo.|
| [foreground_theme_color](/cells/python-net/es/aspose.cells/style/foreground_theme_color) | Obtiene y establece el color del tema de primer plano.|
| [name](/cells/python-net/es/aspose.cells/style/name) | Obtiene o establece el nombre del estilo.|
| [pattern](/cells/python-net/es/aspose.cells/style/pattern) | Obtiene o establece el tipo de patrón de fondo de celda.|
| [borders](/cells/python-net/es/aspose.cells/style/borders) | Obtiene el [`BorderCollection`](/cells/python-net/es/aspose.cells/bordercollection) del estilo.|
| [background_color](/cells/python-net/es/aspose.cells/style/background_color) | Obtiene o establece el color de fondo de un estilo.|
| [background_argb_color](/cells/python-net/es/aspose.cells/style/background_argb_color) | Obtiene y establece el color de fondo con un valor ARGB de 32 bits.|
| [foreground_color](/cells/python-net/es/aspose.cells/style/foreground_color) | Obtiene o establece el color de primer plano de un estilo.|
| [foreground_argb_color](/cells/python-net/es/aspose.cells/style/foreground_argb_color) | Obtiene y establece el color de primer plano con un valor ARGB de 32 bits.|
| [has_borders](/cells/python-net/es/aspose.cells/style/has_borders) | Comprueba si se han establecido bordes para el estilo.|
| [parent_style](/cells/python-net/es/aspose.cells/style/parent_style) | Obtiene el estilo padre de este estilo.|
| [is_number_format_applied](/cells/python-net/es/aspose.cells/style/is_number_format_applied) | Indique si se debe aplicar el formato de número.|
| [is_font_applied](/cells/python-net/es/aspose.cells/style/is_font_applied) |Indique si se debe aplicar el formato de fuente.|
| [is_alignment_applied](/cells/python-net/es/aspose.cells/style/is_alignment_applied) | Indique si se debe aplicar el formato de alineación.|
| [is_border_applied](/cells/python-net/es/aspose.cells/style/is_border_applied) | Indique si se debe aplicar el formato del borde.|
| [is_fill_applied](/cells/python-net/es/aspose.cells/style/is_fill_applied) | Indique si se debe aplicar el formato de relleno.|
| [is_protection_applied](/cells/python-net/es/aspose.cells/style/is_protection_applied) | Indique si se debe aplicar el formato de protección.|
| [indent_level](/cells/python-net/es/aspose.cells/style/indent_level) | Representa el nivel de sangría de la celda o rango. Solo puede ser un número entero entre 0 y 250.|
| [font](/cells/python-net/es/aspose.cells/style/font) | Obtiene un objeto [`Style.font`](/cells/python-net/es/aspose.cells/style#font).|
| [rotation_angle](/cells/python-net/es/aspose.cells/style/rotation_angle) | Representa el ángulo de rotación del texto.|
| [horizontal_alignment](/cells/python-net/es/aspose.cells/style/horizontal_alignment) | Obtiene o establece el tipo de alineación horizontal del texto en una celda.|
| [vertical_alignment](/cells/python-net/es/aspose.cells/style/vertical_alignment) | Obtiene o establece el tipo de alineación vertical del texto en una celda.|
| [is_text_wrapped](/cells/python-net/es/aspose.cells/style/is_text_wrapped) | Obtiene o establece un valor que indica si el texto dentro de una celda está ajustado.|
| [number](/cells/python-net/es/aspose.cells/style/number) | Obtiene o establece el formato de visualización de números y fechas. Los patrones de formato varían según la región.|
| [is_locked](/cells/python-net/es/aspose.cells/style/is_locked) | Obtiene o establece un valor que indica si una celda se puede modificar o no.|
| [custom](/cells/python-net/es/aspose.cells/style/custom) | Representa la cadena de formato de número personalizado de este objeto de estilo.<br/>Si no se configura el formato de número personalizado (por ejemplo, el formato de número está incorporado), se devolverá "".|
| [culture_custom](/cells/python-net/es/aspose.cells/style/culture_custom) | Obtiene y establece la cadena de patrón dependiente de la cultura para el formato de número.<br/>Si no se ha establecido ningún formato de número para este objeto, se devolverá nulo.<br/> Si el formato de número está incorporado, se devolverá la cadena de patrón correspondiente al número incorporado.|
| [invariant_custom](/cells/python-net/es/aspose.cells/style/invariant_custom) | Obtiene la cadena de patrón independiente de la cultura para el formato de número.<br/>Si no se ha establecido ningún formato de número para este objeto, se devolverá nulo.<br/> Si el formato de número está incorporado, se devolverá la cadena de patrón correspondiente al número incorporado.|
| [is_formula_hidden](/cells/python-net/es/aspose.cells/style/is_formula_hidden) | Representa si la fórmula se ocultará cuando la hoja de cálculo esté protegida.|
| [shrink_to_fit](/cells/python-net/es/aspose.cells/style/shrink_to_fit) | Representa si el texto se contrae automáticamente para ajustarse al ancho de columna disponible.|
| [text_direction](/cells/python-net/es/aspose.cells/style/text_direction) | Representa el orden de lectura del texto.|
| [is_justify_distributed](/cells/python-net/es/aspose.cells/style/is_justify_distributed) | Indica si se debe utilizar la alineación de celdas justificadas o distribuidas en la última línea de texto.|
| [quote_prefix](/cells/python-net/es/aspose.cells/style/quote_prefix) | Indica si el valor de la celda comienza con comillas simples.|
| [is_gradient](/cells/python-net/es/aspose.cells/style/is_gradient) | Indica si el sombreado de celda es un patrón de degradado.|
| [is_percent](/cells/python-net/es/aspose.cells/style/is_percent) | Indica si el formato del número es un formato de porcentaje.|
| [is_date_time](/cells/python-net/es/aspose.cells/style/is_date_time) | Indica si el formato del número es un formato de fecha.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/es/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Establece los bordes del estilo.|
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/es/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Establece los bordes del estilo.|
| [`set_pattern_color(self, pattern, color1, color2)`](/cells/python-net/es/aspose.cells/style/set_pattern_color/#aspose.cells.backgroundtype-aspose.pydrawing.color-aspose.pydrawing.color) |Establece el color de fondo.|
| [`copy(self, style)`](/cells/python-net/es/aspose.cells/style/copy/#aspose.cells.style) | Copia datos de otro objeto de estilo|
| [`update(self)`](/cells/python-net/es/aspose.cells/style/update/#) | Aplicar el estilo nombrado a los estilos de las celdas que utilizan este estilo nombrado.<br/>Funciona como hacer clic en el botón "Aceptar" después de terminar de modificar el estilo.<br/> Sólo se aplica para estilos con nombre.|
| [`is_modified(self, modify_flag)`](/cells/python-net/es/aspose.cells/style/is_modified/#aspose.cells.stylemodifyflag) | Comprueba si se han modificado las propiedades especificadas del estilo.<br/> Se utiliza para el estilo de formatos condicionales para comprobar si las propiedades especificadas de este estilo deben utilizarse al aplicar formatos condicionales en una celda.|
| [`set_custom(self, custom, builtin_preference)`](/cells/python-net/es/aspose.cells/style/set_custom/#str-bool) | Establece la cadena de formato de número personalizado de una celda.|
| [`set_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/es/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Establece el relleno especificado en un degradado de dos colores.|
| [`get_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/es/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.color&-aspose.pydrawing.color&-any-any) | Obtenga la configuración de degradado de dos colores.|
| [`get_two_color_gradient_setting(self)`](/cells/python-net/es/aspose.cells/style/get_two_color_gradient_setting/#) | Obtenga la configuración de degradado de dos colores.|
| [`to_json(self)`](/cells/python-net/es/aspose.cells/style/to_json/#) | Convierte los datos de la estructura [`Style`](/cells/python-net/es/aspose.cells/style) en JSON.|



###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
style.font.name = "Times New Roman"
style.font.color = Color.blue
cell.set_style(style)

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`BorderCollection`](/cells/python-net/es/aspose.cells/bordercollection)
* clase [`Style`](/cells/python-net/es/aspose.cells/style)
