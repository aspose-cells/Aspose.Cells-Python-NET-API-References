---
title: método get_enumerator
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 70
url: /es/aspose.cells/row/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Obtiene un enumerador que itera celdas a través de esta fila.


###  Devoluciones

El enumerador de celdas


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| reversed | bool |si enumerar celdas en orden inverso|
| sync | bool | si el enumerador devuelto debe verificar la modificación de las celdas en esta fila<br/> y mantenerse sincronizado con él.|
###  Observaciones

Si la fila se modificará (por operaciones que pueden causar que se cree una nueva instancia de Cell o
(se eliminará el Cell existente) durante el recorrido con el enumerador,
Se debe utilizar un enumerador sincronizado en lugar de un enumerador normal para que el recorrido pueda continuar.
desde la posición justo después de la que ha sido recorrida por el último MoveNext().
Sin embargo, junto con la ventaja de que ningún elemento puede saltarse ni recorrerse repetidamente,
La desventaja del enumerador sincronizado es que el rendimiento se degradará un poco.
Al comparar con el enumerador normal.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Row`](/cells/python-net/es/aspose.cells/row)
