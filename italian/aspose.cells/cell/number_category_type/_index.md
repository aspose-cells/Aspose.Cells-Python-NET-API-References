---
title: number_category_type proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 670
url: /it/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type proprietà

Rappresenta il tipo di categoria della formattazione numerica di questa cella.

###  Osservazioni

Quando il modello di formattazione della cella è combinato con modelli di formattazione condizionale,
quindi il tipo restituito corrisponde alla parte utilizzata per il valore corrente di questa cella.
Ad esempio, se il modello di formattazione per questa cella è "#,##0;(#,##0);"-";@",
quindi quando il valore della cella è numerico e non 0, il tipo restituito è [`NumberCategoryType.NUMBER`](/cells/python-net/it/aspose.cells/numbercategorytype#NUMBER);
Quando il valore della cella è 0 o non è un valore numerico, il tipo restituito è [`NumberCategoryType.TEXT`](/cells/python-net/it/aspose.cells/numbercategorytype#TEXT).
###  Definizione:
```python
@property
def number_category_type(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
* classe [`NumberCategoryType`](/cells/python-net/it/aspose.cells/numbercategorytype)
