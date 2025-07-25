---
title: Hyperlink clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 820
url: /es/aspose.cells/hyperlink/
is_root: false
---
##  Hyperlink clase
Encapsula el objeto que representa un hipervínculo.



El tipo Hyperlink expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [address](/cells/python-net/es/aspose.cells/hyperlink/address) | Representa la dirección de un hipervínculo.|
| [text_to_display](/cells/python-net/es/aspose.cells/hyperlink/text_to_display) | Representa el texto que se mostrará para el hipervínculo especificado. El valor predeterminado es la dirección del hipervínculo.|
| [area](/cells/python-net/es/aspose.cells/hyperlink/area) | Obtiene el rango del hipervínculo.|
| [screen_tip](/cells/python-net/es/aspose.cells/hyperlink/screen_tip) | Devuelve o establece el texto de información en pantalla para el hipervínculo especificado.|
| [link_type](/cells/python-net/es/aspose.cells/hyperlink/link_type) | Obtiene el tipo de enlace.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`delete(self)`](/cells/python-net/es/aspose.cells/hyperlink/delete/#) | Elimina este hipervínculo|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Workbook object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Adding a hyperlink to a URL at "A1" cell
index = worksheet.hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Getting a Hyperlink by index.
hyperlink = worksheet.hyperlinks[index]
# Setting display text of this hyperlink.
hyperlink.text_to_display = "Aspose"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
