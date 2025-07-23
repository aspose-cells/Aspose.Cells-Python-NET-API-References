---
title: LookInType enumeración
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 2270
url: /es/aspose.cells/lookintype/
is_root: false
---
##  LookInType enumeración
Representa la apariencia en tipo.



El tipo LookInType expone los siguientes miembros:

###  Campos
| Campo| Descripción|
| :- | :- |
| FORMULAS | Encuentra el objeto buscado de la fórmula ([`Cell.formula`](/cells/python-net/es/aspose.cells/cell#formula)) si la celda es fórmula,<br/>de lo contrario, busca el valor original de la celda (igual que [`LookInType.ORIGINAL_VALUES`](/cells/python-net/es/aspose.cells/lookintype#ORIGINAL_VALUES)).|
| VALUES | Encuentra el objeto a partir del valor original de la celda ([`Cell.value`](/cells/python-net/es/aspose.cells/cell#value))<br/> y valor formateado ([`Cell.string_value`](/cells/python-net/es/aspose.cells/cell#string_value)).|
| VALUES_EXCLUDE_FORMULA_CELL | Ignora las celdas que son fórmula. Para las celdas que no son fórmula,<br/> Es lo mismo con [`LookInType.VALUES`](/cells/python-net/es/aspose.cells/lookintype#VALUES).|
| COMMENTS | Encuentra el objeto solo en el comentario de la celda. Ignora las celdas sin comentario.|
| ONLY_FORMULAS | Ignora las celdas que no son fórmula. Para las celdas que sí lo son,<br/> Encuentra el objeto buscado a partir de la fórmula ([`Cell.formula`](/cells/python-net/es/aspose.cells/cell#formula)).|
| ORIGINAL_VALUES | Buscar objeto únicamente a partir del valor original de la celda.|
| FORMATTED_VALUES | Busque el objeto únicamente a partir del valor formateado de la celda ([`Cell.string_value`](/cells/python-net/es/aspose.cells/cell#string_value)).|



###  Ver también
* módulo [`aspose.cells`](..)
