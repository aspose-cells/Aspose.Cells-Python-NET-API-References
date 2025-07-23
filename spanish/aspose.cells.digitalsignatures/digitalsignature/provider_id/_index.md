---
title: provider_id propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells.digitalsignatures/digitalsignature/provider_id/
is_root: false
---
##  provider_id propiedad

Especifica el ID de clase del proveedor de firma.
El valor predeterminado es Vacío (todos ceros) Guid.

###  Observaciones

El proveedor de servicios criptográficos (CSP) es un módulo de software independiente que en realidad ejecuta algoritmos de criptografía para autenticación, codificación y cifrado.
Microsoft La oficina se reserva el valor de {00000000-0000-0000-0000-000000000000} para su proveedor de firma predeterminado.
y {000CD6A4-0000-0000-C000-0000000000046} para su proveedor de firmas del este de Asia.

El GUID del proveedor instalado adicionalmente debe obtenerse de la documentación enviada con el proveedor.
###  Definición:
```python
@property
def provider_id(self):
    ...
@provider_id.setter
def provider_id(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.digitalsignatures`](../../)
* clase [`DigitalSignature`](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature)
