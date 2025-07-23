---
title: método get_enumerator
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/rowcollection/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Obtiene un enumerador que itera filas a través de esta colección


###  Devoluciones

El enumerador de filas


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| reversed | bool | si enumerar filas en orden inverso|
| sync | bool | si el enumerador devuelto debe verificar la modificación de la colección de filas<br/> y mantenerse sincronizado con él.|
###  Observaciones

Si la colección de filas se modificará (por operaciones que pueden provocar que se cree una nueva fila o
(La fila existente se eliminará) durante el recorrido con el enumerador,
Se debe utilizar un enumerador sincronizado en lugar de un enumerador normal para que el recorrido pueda continuar.
desde la posición justo después de la que ha sido recorrida por el último MoveNext().
Sin embargo, junto con la ventaja de que ningún elemento puede saltarse ni recorrerse repetidamente,
La desventaja del enumerador sincronizado es que el rendimiento se degradará un poco.
Al comparar con el enumerador normal.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`RowCollection`](/cells/python-net/es/aspose.cells/rowcollection)
