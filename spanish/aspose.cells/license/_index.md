---
title: License clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 930
url: /es/aspose.cells/license/
is_root: false
---
##  License clase
Proporciona métodos para licenciar el componente.



El tipo License expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/license/__init__/#) | Inicializa una nueva instancia de esta clase.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`set_license(self, license_name)`](/cells/python-net/es/aspose.cells/license/set_license/#str) | Licencia el componente.|
| [`set_license(self, stream)`](/cells/python-net/es/aspose.cells/license/set_license/#io.rawiobase) | Licencia el componente.|



###  Ejemplo

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic
 en la carpeta que contiene


el componente, en la carpeta que contiene el ensamblado que lo llama,
en la carpeta del ensamblaje de entrada y luego en los recursos integrados del ensamblaje que llama.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Ver también
* módulo [`aspose.cells`](..)
