---
title: DigitalSignature constructor
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.digitalsignatures/digitalsignature/__init__/
is_root: false
---
##  \_\_init\_\_(self, certificado, comentarios, tiempo_de_firma){#System.Security.Cryptography.X509Certificates.X509Certificate2-str-DateTime}
Constructor de firma digital. Implementado en .NET.



```python

def __init__(self, certificate, comments, sign_time):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| certificate | System.Security.Cryptography.X509Certificates.X509Certificate2 | Objeto de certificado que se utilizó para firmar el documento.|
| comments | str | El propósito de la firma.|
| sign_time | DateTime | La hora UTC en que se firmó el documento.|


## \_\_init\_\_(self, raw_data, contraseña, comentarios, tiempo_de_inicio){#bytes-str-str-DateTime}
Constructor de firma digital. Utiliza la implementación de Bouncy Castle.



```python

def __init__(self, raw_data, password, comments, sign_time):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| raw_data | bytes | Una matriz de bytes que contiene datos de un certificado X.509.|
| password | str | La contraseña necesaria para acceder a los datos del certificado X.509.|
| comments | str | El propósito de la firma.|
| sign_time | DateTime | La hora UTC en que se firmó el documento.|



###  Ver también
* módulo [`aspose.cells.digitalsignatures`](../../)
* clase [`DigitalSignature`](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature)
