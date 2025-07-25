---
title: provider_id fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 80
url: /sv/aspose.cells.digitalsignatures/digitalsignature/provider_id/
is_root: false
---
##  provider_id fastighet

Anger klass-ID för signaturleverantören.
Standardvärdet är tomt (bara nollor) Guid.

###  Anmärkningar

En kryptografisk tjänsteleverantör (CSP) är en oberoende programmodul som faktiskt utför kryptografiska algoritmer för autentisering, kodning och kryptering.
Microsoft Office reserverar värdet {00000000-0000-0000-0000-00000000000} för sin standardleverantör av signaturer,
och {000CD6A4-0000-0000-C000-000000000046} för sin östasiatiska signaturleverantör.

GUID för den ytterligare installerade providern bör hämtas från dokumentationen som medföljde providern.
###  Definition:
```python
@property
def provider_id(self):
    ...
@provider_id.setter
def provider_id(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.digitalsignatures`](../../)
* klass [`DigitalSignature`](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature)
