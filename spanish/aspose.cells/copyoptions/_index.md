---
title: CopyOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 340
url: /es/aspose.cells/copyoptions/
is_root: false
---
##  CopyOptions clase
Representa las opciones de copia.



El tipo CopyOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/copyoptions/__init__/#) | Constructor de CopyOptions.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [keep_macros](/cells/python-net/es/aspose.cells/copyoptions/keep_macros) |Indica si se mantienen las macros;|
| [extend_to_adjacent_range](/cells/python-net/es/aspose.cells/copyoptions/extend_to_adjacent_range) | Indica si se extienden los rangos al copiar el rango al rango adyacente.|
| [copy_names](/cells/python-net/es/aspose.cells/copyoptions/copy_names) | Indica si se copian los nombres.|
| [copy_invalid_formulas_as_values](/cells/python-net/es/aspose.cells/copyoptions/copy_invalid_formulas_as_values) | Si la fórmula no es válida para el destino, solo copia los valores.|
| [column_character_width](/cells/python-net/es/aspose.cells/copyoptions/column_character_width) | Indica si se copia el ancho de la columna en unidades de caracteres.|
| [refer_to_sheet_with_same_name](/cells/python-net/es/aspose.cells/copyoptions/refer_to_sheet_with_same_name) | En MS Excel, al copiar fórmulas que hacen referencia a otras hojas de cálculo mientras se copia una hoja de cálculo a otra,<br/>Las fórmulas copiadas deben hacer referencia al libro de trabajo de origen.<br/>Sin embargo, para algunas situaciones, el usuario puede necesitar que las fórmulas copiadas se refieran a hojas de trabajo con el mismo nombre.<br/>en el mismo libro de trabajo, como cuando esas hojas de trabajo se han copiado antes de esta operación de copia,<br/> Entonces esta propiedad debe mantenerse como verdadera.|
| [refer_to_destination_sheet](/cells/python-net/es/aspose.cells/copyoptions/refer_to_destination_sheet) | Al copiar el rango en el mismo archivo y el gráfico hace referencia a la hoja de origen,<br/>Falso significa que la fuente de datos del gráfico copiado no se cambiará.<br/> Verdadero significa que la fuente de datos del gráfico copiado hace referencia a la hoja de destino.|



###  Ver también
* módulo [`aspose.cells`](..)
