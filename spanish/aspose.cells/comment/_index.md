---
title: Comment clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 260
url: /es/aspose.cells/comment/
is_root: false
---
##  Comment clase
Encapsula el objeto que representa un comentario de celda.



El tipo Comment expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [author](/cells/python-net/es/aspose.cells/comment/author) | Obtiene y establece el nombre del autor del comentario original.|
| [comment_shape](/cells/python-net/es/aspose.cells/comment/comment_shape) | Obtenga un objeto Shape que represente la forma adjunta al comentario especificado.|
| [row](/cells/python-net/es/aspose.cells/comment/row) | Obtiene el índice de fila del comentario.|
| [column](/cells/python-net/es/aspose.cells/comment/column) | Obtiene el índice de la columna del comentario.|
| [is_threaded_comment](/cells/python-net/es/aspose.cells/comment/is_threaded_comment) | Indica si este comentario es un comentario enhebrado.|
| [threaded_comments](/cells/python-net/es/aspose.cells/comment/threaded_comments) | Obtiene la lista de comentarios enhebrados;|
| [note](/cells/python-net/es/aspose.cells/comment/note) | Representa el contenido del comentario.|
| [html_note](/cells/python-net/es/aspose.cells/comment/html_note) | Obtiene y establece la cadena html que contiene datos y algunos formatos en este comentario.|
| [font](/cells/python-net/es/aspose.cells/comment/font) | Obtiene la fuente del comentario.|
| [is_visible](/cells/python-net/es/aspose.cells/comment/is_visible) | Representa si el comentario es visible o no.|
| [text_orientation_type](/cells/python-net/es/aspose.cells/comment/text_orientation_type) | Obtiene y establece el tipo de orientación del texto del comentario.|
| [text_horizontal_alignment](/cells/python-net/es/aspose.cells/comment/text_horizontal_alignment) | Obtiene y establece el tipo de alineación horizontal del texto del comentario.|
| [text_vertical_alignment](/cells/python-net/es/aspose.cells/comment/text_vertical_alignment) | Obtiene y establece el tipo de alineación vertical del texto del comentario.|
| [auto_size](/cells/python-net/es/aspose.cells/comment/auto_size) | Indica si el tamaño del comentario se ajusta automáticamente según su contenido.<br/>Nota: En algunos casos especiales (como en entornos Mac), es posible que esta configuración no tenga efecto. Si no lo tiene, reemplácela con FitToTextSize().|
| [height_cm](/cells/python-net/es/aspose.cells/comment/height_cm) | Representa la altura del comentario, en unidad de centímetros.|
| [width_cm](/cells/python-net/es/aspose.cells/comment/width_cm) | Representa el ancho del comentario, en unidad de centímetros.|
| [width](/cells/python-net/es/aspose.cells/comment/width) | Representa el ancho del comentario, en unidades de píxeles.|
| [height](/cells/python-net/es/aspose.cells/comment/height) | Representa la altura del comentario, en unidad de píxeles.|
| [width_inch](/cells/python-net/es/aspose.cells/comment/width_inch) | Representa el ancho del comentario, en unidades de pulgadas.|
| [height_inch](/cells/python-net/es/aspose.cells/comment/height_inch) | Representa la altura del comentario, en unidad de pulgadas.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/es/aspose.cells/comment/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Formatear algunos caracteres con la configuración de fuente.|
| [`characters(self, start_index, length)`](/cells/python-net/es/aspose.cells/comment/characters/#int-int) | Devuelve un objeto Caracteres que representa un rango de caracteres dentro del texto del comentario.|
| [`get_characters(self)`](/cells/python-net/es/aspose.cells/comment/get_characters/#) | Devuelve todos los objetos de Personajes<br/> que representa un rango de caracteres dentro del texto del comentario.|
| [`get_rich_formattings(self)`](/cells/python-net/es/aspose.cells/comment/get_rich_formattings/#) | Devuelve todos los objetos de Personajes<br/> que representa un rango de caracteres dentro del texto del comentario.|



###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment2 = comments.get("B2")
comment2.note = "Second note."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Ver también
* módulo [`aspose.cells`](..)
