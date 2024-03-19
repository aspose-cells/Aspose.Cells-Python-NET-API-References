---
title: check_font_compatibility proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 60
url: /it/aspose.cells/pptxsaveoptions/check_font_compatibility/
is_root: false
---
##  check_font_compatibility proprietà

Indica se verificare la compatibilità dei caratteri per ogni carattere del testo.

###  Osservazioni

Il valore predefinito è vero.
Disabilitare questa proprietà può fornire prestazioni migliori.
Ma quando il carattere predefinito o specificato del testo/carattere non può essere utilizzato per visualizzarlo,
caratteri illeggibili (come il blocco) potrebbero essere presenti nel pdf generato.
Per tale situazione l'utente dovrebbe mantenere questa proprietà vera in modo che
è possibile cercare e utilizzare caratteri alternativi per visualizzare il testo;
###  Definizione:
```python
@property
def check_font_compatibility(self):
    ...
@check_font_compatibility.setter
def check_font_compatibility(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`PptxSaveOptions`](/cells/python-net/it/aspose.cells/pptxsaveoptions)
