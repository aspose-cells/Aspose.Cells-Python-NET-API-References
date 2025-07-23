---
title: check_excel_restriction propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 70
url: /es/aspose.cells.loading/difloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction propiedad

Si verificar la restricción del archivo Excel cuando el usuario modifica objetos relacionados con celdas.
Por ejemplo, Excel no permite ingresar valores de cadena con una longitud mayor a 32K.
Cuando ingresa un valor más largo que 32K, como por ejemplo Cell.PutValue(string), si esta propiedad es verdadera, obtendrá una excepción.
Si esta propiedad es falsa, aceptaremos el valor de la cadena de entrada como el valor de la celda para que más adelante
Puede generar el valor de cadena completo para otros formatos de archivo, como CSV.
Sin embargo, si ha establecido un tipo de valor que no es válido para el formato de archivo de Excel,
No guarde el libro de trabajo como archivo Excel posteriormente. De lo contrario, podría producirse un error inesperado en el archivo Excel generado.
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
* módulo [`aspose.cells.loading`](../../)
* clase [`DifLoadOptions`](/cells/python-net/es/aspose.cells.loading/difloadoptions)
