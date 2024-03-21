---
title: método import_custom_objects
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 630
url: /es/aspose.cells/cells/import_custom_objects/
is_root: false
---
##  import_custom_objects {#list-int-int-aspose.cells.ImportTableOptions}
Importa objetos personalizados.


###  Devoluciones

Número total de filas importadas.


```python
def import_custom_objects(self, list, first_row, first_column, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| list | list | El objeto personalizado|
| first_row | int | El número de fila de la primera celda a importar.|
| first_column | int | El número de columna de la primera celda a importar.|
| options | [`ImportTableOptions`](/cells/python-net/es/aspose.cells/importtableoptions) | Las opciones de importación.|
###  Observaciones

Los objetos personalizados deben ser del mismo tipo.

##  import_custom_objects {#list-list-bool-int-int-int-bool-str-bool}

Importa objetos personalizados.


###  Devoluciones

Número total de filas importadas.


```python
def import_custom_objects(self, list, property_names, is_property_name_shown, first_row, first_column, row_number, insert_rows, date_format_string, convert_string_to_number):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| list | list | El objeto personalizado|
| property_names | list | Los nombres de las propiedades. Si es nulo, importaremos todas las propiedades del objeto.|
| is_property_name_shown | bool | Indica si el nombre de la propiedad se importará a la primera fila.|
| first_row | int | El número de fila de la primera celda a importar.|
| first_column | int | El número de columna de la primera celda a importar.|
| row_number | int | Número de filas que se importarán.|
| insert_rows | bool | Indica si se agregan filas adicionales para ajustar los datos.|
| date_format_string | str | Cadena de formato de fecha para celdas.|
| convert_string_to_number | bool | Indica si este método intentará convertir una cadena en un número.|
###  Observaciones

Los objetos personalizados deben ser del mismo tipo.


###  Ver también

* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
