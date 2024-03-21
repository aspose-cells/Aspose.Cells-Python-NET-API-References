---
title: método set_embedded_object
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 190
url: /es/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object {#bool-bytes-str-bool-str}
Establece datos de objetos incrustados.



```python
def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| link_to_file | bool | Indica si el objeto se vincula al archivo. Si es verdadero, se ignora el parámetro objectData.|
| object_data | bytes | Los datos del objeto incrustado.|
| source_file_name | str | El nombre del archivo.|
| display_as_icon | bool | Indica si se muestra el objeto como un icono.<br/> Si es verdadero, los datos de la imagen original estarán cubiertos por un ícono.|
| label | str | La etiqueta del icono. Solo funciona cuando displayAsIcon es verdadero.|


##  set_embedded_object {#bool-bytes-str-bool-str-bool}
Establece datos de objetos incrustados.



```python
def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| link_to_file | bool | Indica si el objeto se vincula al archivo. Si es verdadero, se ignora el parámetro objectData.|
| object_data | bytes | Los datos del objeto incrustado.|
| source_file_name | str | El nombre del archivo.|
| display_as_icon | bool | Indica si se muestra el objeto como un icono.<br/> Si es verdadero, los datos de la imagen original estarán cubiertos por un ícono.|
| label | str | La etiqueta del icono. Solo funciona cuando displayAsIcon es verdadero.|
| update_icon | bool |Indica si el icono se actualiza automáticamente.|
###  Observaciones

Como Aspose puede actualizar e incrustar todos los íconos de archivos, es mejor que pueda agregar el ícono correcto con `update_icon` como falso.


###  Ver también

* módulo [`aspose.cells.drawing`](../../)
* clase [`OleObject`](/cells/python-net/es/aspose.cells.drawing/oleobject)
