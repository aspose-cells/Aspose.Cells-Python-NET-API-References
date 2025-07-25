---
title: DigitalSignature constructeur
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells.digitalsignatures/digitalsignature/__init__/
is_root: false
---
##  \_\_init\_\_(self, certificat, commentaires, sign_time){#System.Security.Cryptography.X509Certificates.X509Certificate2-str-DateTime}
Constructeur de signature numérique. Utilise l'implémentation .Net.



```python

def __init__(self, certificate, comments, sign_time):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| certificate | System.Security.Cryptography.X509Certificates.X509Certificate2 | Objet de certificat qui a été utilisé pour signer le document.|
| comments | str | Le but de la signature.|
| sign_time | DateTime | L'heure UTC à laquelle le document a été signé.|


## \_\_init\_\_(self, raw_data, mot de passe, commentaires, sign_time){#bytes-str-str-DateTime}
Constructeur de signature numérique. Utilise l'implémentation Bouncy Castle.



```python

def __init__(self, raw_data, password, comments, sign_time):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| raw_data | bytes | Un tableau d'octets contenant des données provenant d'un certificat X.509.|
| password | str | Le mot de passe requis pour accéder aux données du certificat X.509.|
| comments | str | Le but de la signature.|
| sign_time | DateTime | L'heure UTC à laquelle le document a été signé.|



###  Voir également
* module [`aspose.cells.digitalsignatures`](../../)
* classe [`DigitalSignature`](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature)
