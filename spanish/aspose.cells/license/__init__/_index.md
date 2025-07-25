---
title: License constructor
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells/license/__init__/
is_root: false
---
##  \_\_init\_\_(yo mismo){#}
Inicializa una nueva instancia de esta clase.



```python

def __init__(self):
    ...
```



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
* módulo [`aspose.cells`](../../)
* clase [`License`](/cells/python-net/es/aspose.cells/license)
