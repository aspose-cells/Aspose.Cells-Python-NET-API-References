---
title: refer_to_sheet_with_same_name propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells/copyoptions/refer_to_sheet_with_same_name/
is_root: false
---
##  refer_to_sheet_with_same_name propiedad

En MS Excel, al copiar fórmulas que hacen referencia a otras hojas de cálculo mientras se copia una hoja de cálculo a otra,
Las fórmulas copiadas deben hacer referencia al libro de trabajo de origen.
Sin embargo, para algunas situaciones, el usuario puede necesitar que las fórmulas copiadas se refieran a hojas de trabajo con el mismo nombre.
en el mismo libro de trabajo, como cuando esas hojas de trabajo se han copiado antes de esta operación de copia,
Entonces esta propiedad debe mantenerse como verdadera.

###  Observaciones

El valor predeterminado es verdadero.
###  Definición:
```python
@property
def refer_to_sheet_with_same_name(self):
    ...
@refer_to_sheet_with_same_name.setter
def refer_to_sheet_with_same_name(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CopyOptions`](/cells/python-net/es/aspose.cells/copyoptions)
