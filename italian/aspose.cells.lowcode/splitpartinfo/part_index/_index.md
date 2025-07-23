---
title: part_index proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells.lowcode/splitpartinfo/part_index/
is_root: false
---
##  part_index proprietà

Indice della parte corrente nella sequenza (in base a 0).
-1 significa che non ci sono parti multiple, quindi il risultato è singolo.

###  Osservazioni

Se è necessario elaborare più fogli e ogni foglio viene elaborato (suddiviso)
separatamente, l'indice delle parti parte sempre da 0 per ogni foglio.
Ad esempio, quando si converte una cartella di lavoro in immagini,
rappresenta l'indice della pagina di output del foglio attualmente elaborato.
E -1 indica che c'è una sola pagina per il foglio corrente.
###  Definizione:
```python
@property
def part_index(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.lowcode`](../../)
* classe [`SplitPartInfo`](/cells/python-net/it/aspose.cells.lowcode/splitpartinfo)
