---
title: user_password proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 130
url: /it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password/
is_root: false
---
##  user_password proprietà

Ottiene o imposta la password utente richiesta per aprire il documento crittografato PDF.

###  Osservazioni

Per aprire il documento crittografato PDF e visualizzarlo sarà necessaria la password del proprietario o la password dell'utente.


La password utente può essere una stringa nulla o vuota, in questo caso non verrà richiesta alcuna password all'utente quando si apre il documento PDF.


L'apertura del documento con la password del proprietario corretta consente l'accesso completo al documento.


 Apertura del documento con la password utente corretta (o apertura di un documento che non ha una password utente)
consente un accesso limitato in base alle autorizzazioni specificate.
###  Definizione:
```python
@property
def user_password(self):
    ...
@user_password.setter
def user_password(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.rendering.pdfsecurity`](../../)
* classe [`PdfSecurityOptions`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
