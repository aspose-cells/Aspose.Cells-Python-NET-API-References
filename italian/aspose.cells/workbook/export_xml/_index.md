---
title: Metodo export_xml
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 150
url: /it/aspose.cells/workbook/export_xml/
is_root: false
---
##  export_xml(self, map_name, path) {#str-str}
Esporta i dati XML collegati dalla mappa XML specificata.



```python

def export_xml(self, map_name, path):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| map_name | str | nome della mappa XML che deve essere esportata|
| path | str | il percorso di esportazione|

###  Esempio

Il codice seguente esporta i dati collegati dal primo XmlMap.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
# Make sure that the source xlsx file contains a XmlMap.
xmlMap = wb.worksheets.xml_maps[0]
wb.export_xml(xmlMap.name, "output.xml")

```


##  export_xml(self, map_name, stream) {#str-io.RawIOBase}
Esportare dati XML.



```python

def export_xml(self, map_name, stream):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| map_name | str | nome della mappa XML che deve essere esportata|
| stream | io.RawIOBase | il flusso di esportazione|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
