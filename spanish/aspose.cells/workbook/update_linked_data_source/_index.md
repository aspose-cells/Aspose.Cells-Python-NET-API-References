---
title: método update_linked_data_source
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 440
url: /es/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source(self, external_workbooks) {#list}
Si este libro de trabajo contiene enlaces externos a otras fuentes de datos,
Aspose.Cells intentará recuperar los datos más recientes de las fuentes proporcionadas.



```python

def update_linked_data_source(self, external_workbooks):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| external_workbooks | list | Libros de trabajo que se utilizarán para actualizar los datos de los enlaces externos a los que hace referencia este libro de trabajo.<br/>La coincidencia de aquellos libros de trabajo con enlaces externos está determinada por [`Workbook.file_name`](/cells/python-net/es/aspose.cells/workbook#file_name)<br/>y [`ExternalLink.data_source`](/cells/python-net/es/aspose.cells/externallink#data_source). Así que asegúrese de que [`Workbook.file_name`](/cells/python-net/es/aspose.cells/workbook#file_name) tenga<br/> Se ha especificado con el valor adecuado para cada libro de trabajo para que puedan vincularse al enlace externo correspondiente.|
###  Observaciones

Si no se puede encontrar el enlace externo correspondiente para un libro de trabajo, entonces dicho libro se ignorará.
Entonces, cuando más tarde configure una fórmula con un nuevo enlace externo que desea que sea el libro de trabajo ignorado
estar vinculado a él, el vínculo no se puede realizar hasta que vuelva a llamar a este método con esos libros de trabajo.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
