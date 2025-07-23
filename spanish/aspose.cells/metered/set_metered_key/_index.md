---
title: método set_metered_key
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells/metered/set_metered_key/
is_root: false
---
##  set_metered_key(self, public_key, private_key) {#str-str}
Establece una clave pública y privada medida.
Si compra una licencia medida, al iniciar la aplicación se debe llamar al API, normalmente esto es suficiente.
 Sin embargo, si siempre falla la carga de datos de consumo y excede las 24 horas, la licencia pasará al estado de evaluación.
Para evitar tal caso, debe verificar periódicamente el estado de la licencia, si está en estado de evaluación, llame nuevamente al API.



```python

def set_metered_key(self, public_key, private_key):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| public_key | str | clave pública|
| private_key | str | clave privada|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Metered`](/cells/python-net/es/aspose.cells/metered)
