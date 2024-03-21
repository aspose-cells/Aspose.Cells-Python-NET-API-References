---
title: método set_metered_key
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells/metered/set_metered_key/
is_root: false
---
##  set_metered_key {#str-str}
Establece claves públicas y privadas medidas.
 Si compra una licencia medida, cuando inicie la solicitud, se debe llamar a este API; normalmente, esto es suficiente.
 Sin embargo, si siempre no se cargan los datos de consumo y excede las 24 horas, la licencia pasará al estado de evaluación.
Para evitar tal caso, debe verificar periódicamente el estado de la licencia; si es un estado de evaluación, llame nuevamente al API.



```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| public_key | str | Llave pública|
| private_key | str | llave privada|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Metered`](/cells/python-net/es/aspose.cells/metered)
