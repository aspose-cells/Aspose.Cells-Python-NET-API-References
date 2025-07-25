---
title: Metodo add_identify
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.pivot/pivotpagefields/add_identify/
is_root: false
---
##  add_identify(self, range_index, page_item_index) {#int-list}
Imposta quale etichetta di elemento in ogni campo della pagina utilizzare per identificare l'intervallo di dati.
pageItemIndex.Length deve essere uguale a PageFieldCount, quindi aggiungi prima il campo pagina.



```python

def add_identify(self, range_index, page_item_index):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| range_index | int | Indice dell'intervallo dei dati di consolidamento.|
| page_item_index | list | Indice degli elementi della pagina in ogni campo della pagina.<br/>pageItemIndex[2] = 1 indica il secondo elemento nel terzo campo da utilizzare per identificare questo intervallo.<br/> pageItemIndex[1] = -1 significa che non c'è alcun elemento nel secondo campo da utilizzare per identificare questo intervallo<br/> e MS creerà automaticamente un elemento "vuoto" nel secondo campo per identificare questo intervallo.|



###  Guarda anche
* modulo [`aspose.cells.pivot`](../../)
* classe [`PivotPageFields`](/cells/python-net/it/aspose.cells.pivot/pivotpagefields)
