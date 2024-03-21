---
title: método register_add_in_function
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 180
url: /es/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function {#int-str}
Agrega una función complementaria al libro de trabajo.


###  Devoluciones

URL del archivo complementario que contiene funciones complementarias


```python
def register_add_in_function(self, id, function_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| id | int | ID de los datos que contienen funciones complementarias,<br/> Se puede obtener mediante la primera llamada al [`WorksheetCollection.register_add_in_function`](/cells/python-net/es/aspose.cells/worksheetcollection/register_add_in_function) para el mismo archivo complementario.|
| function_name | str | el nombre de la función complementaria|


##  register_add_in_function {#str-str-bool}
Agrega una función complementaria al libro de trabajo.


###  Devoluciones

ID de los datos que contienen la función complementaria dada


```python
def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| add_in_file | str | el archivo contiene las funciones complementarias|
| function_name | str | el nombre de la función complementaria|
| lib | bool | si el archivo complementario proporcionado está en el directorio o subdirectorio de la biblioteca de complementos del libro de trabajo.<br/>Este indicador entra en vigor y marca la diferencia cuando se proporciona addInFile como ruta relativa:<br/> verdadero indica que la ruta es relativa a la biblioteca de complementos y falso indica que la ruta es relativa a este libro de trabajo.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`WorksheetCollection`](/cells/python-net/es/aspose.cells/worksheetcollection)
