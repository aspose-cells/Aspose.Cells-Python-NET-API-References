---
title: Metodo add_date_filter
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/autofilter/add_date_filter/
is_root: false
---
##  add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second) {#int-aspose.cells.DateTimeGroupingType-int-int-int-int-int-int}
Aggiunge un filtro data.



```python

def add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| field_index | int | L'offset intero del campo su cui si desidera basare il filtro<br/> (da sinistra nell'elenco; il campo più a sinistra è il campo 0).|
| date_time_grouping_type | [`DateTimeGroupingType`](/cells/python-net/it/aspose.cells/datetimegroupingtype) | Il tipo di raggruppamento|
| year | int | L'anno.|
| month | int | Il mese.|
| day | int | Il giorno.|
| hour | int | L'ora.|
| minute | int | Il minuto.|
| second | int | Il secondo.|
###  Osservazioni

Se DateTimeGroupingType è Year, ha effetto solo il parametro year.
Se DateTiemGroupingType è Month, hanno effetto solo i parametri anno e mese.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`AutoFilter`](/cells/python-net/it/aspose.cells/autofilter)
