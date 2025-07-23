---
title: Metodo is_chart_data_changed
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 80
url: /it/aspose.cells.charts/chart/is_chart_data_changed/
is_root: false
---
##  is_chart_data_changed(self) {#}
Rileva se l'origine dati di un grafico è cambiata.


###  ritorna

Restituisce true se il grafico è cambiato, altrimenti restituisce false


```python

def is_chart_data_changed(self):
    ...
```


###  Osservazioni

Il metodo rileva le modifiche nell'origine dati del grafico prima di trasformarlo in formato immagine.
Alla prima chiamata di Chart.toImage, verranno registrati i dati sorgente del grafico (ad esempio XValuesParseData, ValuesParseData).
Prima di richiamare nuovamente il metodo Chart.toImage, richiamare il metodo IsChartDataChanged per verificare se Chart necessita di un nuovo rendering.


###  Guarda anche
* modulo [`aspose.cells.charts`](../../)
* classe [`Chart`](/cells/python-net/it/aspose.cells.charts/chart)
