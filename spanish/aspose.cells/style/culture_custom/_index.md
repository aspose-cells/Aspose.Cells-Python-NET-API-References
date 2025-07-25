---
title: culture_custom propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 170
url: /es/aspose.cells/style/culture_custom/
is_root: false
---
##  culture_custom propiedad

Obtiene y establece la cadena de patrón dependiente de la cultura para el formato de número.
Si no se ha establecido ningún formato de número para este objeto, se devolverá nulo.
Si el formato de número está incorporado, se devolverá la cadena de patrón correspondiente al número incorporado.

###  Observaciones

Para el formato de número incorporado, tanto el contenido del patrón (por ejemplo, un formato de fecha incorporado es "m/d/a" para algunas configuraciones regionales,
pero para otras configuraciones regionales se convierte en "d/m/y") y el especificador de formato (como, por ejemplo,
Algunas configuraciones regionales utilizan caracteres distintos de 'y' para representar la parte del año en el formato de fecha)
dependen de la cultura;
Para el formato personalizado especificado por el usuario, solo se cambian los especificadores de formato según la cultura.
Otras partes del patrón de formato no se modificarán.
###  Definición:
```python
@property
def culture_custom(self):
    ...
@culture_custom.setter
def culture_custom(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Style`](/cells/python-net/es/aspose.cells/style)
