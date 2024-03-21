---
title: Metered clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1090
url: /es/aspose.cells/metered/
is_root: false
---
##  Metered clase
Proporciona métodos para configurar la clave medida.



El tipo Metered expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/metered/__init__/#) | Inicializa una nueva instancia de esta clase.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [set_metered_key](/cells/python-net/es/aspose.cells/metered/set_metered_key/#str-str) | Establece claves públicas y privadas medidas.<br/> Si compra una licencia medida, cuando inicie la solicitud, se debe llamar a este API; normalmente, esto es suficiente.<br/> Sin embargo, si siempre no se cargan los datos de consumo y excede las 24 horas, la licencia pasará al estado de evaluación.<br/> Para evitar tal caso, debe verificar periódicamente el estado de la licencia; si es un estado de evaluación, llame nuevamente al API.|
| [get_consumption_quantity](/cells/python-net/es/aspose.cells/metered/get_consumption_quantity/#) | Obtiene el tamaño del archivo de consumo|
| [get_consumption_credit](/cells/python-net/es/aspose.cells/metered/get_consumption_credit/#) | Obtiene crédito de consumo|
| [get_product_name](/cells/python-net/es/aspose.cells/metered/get_product_name/#) | Obtiene el nombre del producto|
| [is_metered_licensed](/cells/python-net/es/aspose.cells/metered/is_metered_licensed/#) | Compruebe si el medidor tiene licencia|



###  Ejemplo

En este ejemplo, se intentará establecer claves públicas y privadas medidas.


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Ver también
* módulo [`aspose.cells`](..)
