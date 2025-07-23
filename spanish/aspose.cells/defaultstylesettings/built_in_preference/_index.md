---
title: built_in_preference propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/defaultstylesettings/built_in_preference/
is_root: false
---
##  built_in_preference propiedad

Indica si la propiedad para el formato de número es preferible cuando el estilo define tanto un número integrado como un patrón personalizado.
El valor predeterminado es falso, lo que significa que, de forma predeterminada, se utilizará un patrón personalizado para formatear valores siempre que no esté vacío para un estilo.

###  Observaciones

Al cargar un libro de trabajo desde un archivo de plantilla existente, es posible que tanto el número integrado como el patrón personalizado se definan para un estilo.
Esta propiedad determina si debemos utilizar el número incorporado o el patrón personalizado al formatear valores con el estilo.
###  Definición:
```python
@property
def built_in_preference(self):
    ...
@built_in_preference.setter
def built_in_preference(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`DefaultStyleSettings`](/cells/python-net/es/aspose.cells/defaultstylesettings)
