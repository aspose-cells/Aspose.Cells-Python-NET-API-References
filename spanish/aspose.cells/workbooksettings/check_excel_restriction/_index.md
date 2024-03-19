---
title: check_excel_restriction propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 110
url: /es/aspose.cells/workbooksettings/check_excel_restriction/
is_root: false
---
##  check_excel_restriction propiedad

Si se verifica la restricción del archivo de Excel cuando el usuario modifica los objetos relacionados con las celdas.
Por ejemplo, Excel no permite ingresar un valor de cadena de más de 32 K.
Cuando ingresa un valor superior a 32 KB, como por ejemplo Cell.PutValue(cadena), si esta propiedad es verdadera, obtendrá una excepción.
Si esta propiedad es falsa, aceptaremos el valor de su cadena de entrada como el valor de la celda para que más tarde
puede generar el valor de cadena completo para otros formatos de archivo como CSV.
Sin embargo, si ha establecido un tipo de valor que no es válido para el formato de archivo Excel,
no debe guardar el libro como formato de archivo Excel más adelante. De lo contrario, puede haber un error inesperado en el archivo Excel generado.
###  Definición:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`WorkbookSettings`](/cells/python-net/es/aspose.cells/workbooksettings)
