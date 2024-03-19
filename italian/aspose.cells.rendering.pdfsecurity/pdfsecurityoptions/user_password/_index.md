---
title: user_password proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 130
url: /it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password/
is_root: false
---
##  user_password proprietà

Ottiene o imposta la password utente richiesta per l'apertura del documento crittografato PDF.

###  Osservazioni

Sarà richiesta la password del proprietario o la password dell'utente per aprire un documento crittografato PDF per la visualizzazione.


La password dell'utente può essere nulla o una stringa vuota, in questo caso non verrà richiesta alcuna password all'utente all'apertura del documento PDF.


L'apertura del documento con la password del proprietario corretta consente l'accesso completo al documento.


 Apertura del documento con la password utente corretta (o apertura di un documento che non dispone di una password utente)
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
