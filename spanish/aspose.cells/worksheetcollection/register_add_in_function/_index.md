---
title: método register_add_in_function
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 180
url: /es/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function(self, id, function_name) {#int-str}
Añade una función complementaria al libro de trabajo.


###  Devoluciones

URL del archivo del complemento que contiene las funciones del complemento


```python

def register_add_in_function(self, id, function_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| id | int |ID de los datos que contienen funciones complementarias,<br/> Se puede obtener llamando al [`WorksheetCollection.register_add_in_function`](/cells/python-net/es/aspose.cells/worksheetcollection/register_add_in_function) para obtener el mismo archivo complementario.|
| function_name | str | el nombre de la función complementaria|


##  register_add_in_function(self, add_in_file, function_name, lib) {#str-str-bool}
Añade una función complementaria al libro de trabajo.


###  Devoluciones

ID de los datos que contiene la función complementaria dada


```python

def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| add_in_file | str | El archivo contiene las funciones complementarias.|
| function_name | str | el nombre de la función complementaria|
| lib | bool | si el archivo de complemento dado está en el directorio o subdirectorio de la biblioteca de complementos del libro de trabajo.<br/>Esta bandera tiene efecto y hace la diferencia cuando el addInFile dado tiene una ruta relativa:<br/> verdadero indica que la ruta es relativa a la biblioteca de complementos y falso indica que la ruta es relativa a este libro de trabajo.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`WorksheetCollection`](/cells/python-net/es/aspose.cells/worksheetcollection)
