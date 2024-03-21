---
title: método get_default_sheet_name
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells/globalizationsettings/get_default_sheet_name/
is_root: false
---
##  get_default_sheet_name {#}
Obtiene el nombre de la hoja predeterminada para agregar una hoja de trabajo automáticamente.
El valor predeterminado es "Hoja".


###  Devoluciones

el nombre de hoja predeterminado para agregar una hoja de trabajo automáticamente


```python
def get_default_sheet_name(self):
    ...
```


###  Observaciones

El agregado automáticamente (como por [`WorksheetCollection.add`](/cells/python-net/es/aspose.cells/worksheetcollection/add))
El nombre de la hoja será el nombre especificado más el número de secuencia.
 Por ejemplo, para Alemania, el usuario tal vez quiera que el nombre de la hoja sea "Tabellenblatt2" en lugar de "Hoja2".
Entonces el usuario puede implementar este método para devolver "Tabellenblatt".


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`GlobalizationSettings`](/cells/python-net/es/aspose.cells/globalizationsettings)
