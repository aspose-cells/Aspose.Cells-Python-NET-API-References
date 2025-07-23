---
title: provider_id proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 80
url: /it/aspose.cells.digitalsignatures/digitalsignature/provider_id/
is_root: false
---
##  provider_id proprietà

Specifica l'ID di classe del fornitore della firma.
Il valore predefinito è Vuoto (tutti zeri) Guid.

###  Osservazioni

Il fornitore di servizi crittografici (CSP) è un modulo software indipendente che esegue effettivamente algoritmi di crittografia per l'autenticazione, la codifica e la cifratura.
Microsoft L'ufficio riserva il valore di {00000000-0000-0000-0000-000000000000} per il suo fornitore di firma predefinito,
e {000CD6A4-0000-0000-C000-000000000046} per il suo fornitore di firme dell'Asia orientale.

Il GUID del provider installato in aggiunta dovrebbe essere ricavato dalla documentazione fornita con il provider.
###  Definizione:
```python
@property
def provider_id(self):
    ...
@provider_id.setter
def provider_id(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.digitalsignatures`](../../)
* classe [`DigitalSignature`](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature)
