---
title: DataSorter classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 410
url: /it/aspose.cells/datasorter/
is_root: false
---
##  DataSorter classe
Descrizione riassuntiva per DataSorter.



Il tipo DataSorter espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [keys](/cells/python-net/it/aspose.cells/datasorter/keys) | Ottiene l'elenco delle chiavi dell'ordinatore dati.|
| [has_headers](/cells/python-net/it/aspose.cells/datasorter/has_headers) | Indica se l'intervallo contiene intestazioni.|
| [key1](/cells/python-net/it/aspose.cells/datasorter/key1) | Rappresenta l'indice della prima colonna ordinata (posizione assoluta, la colonna A è 0, B è 1, ...).|
| [order1](/cells/python-net/it/aspose.cells/datasorter/order1) | Rappresenta l'ordinamento della prima chiave.|
| [key2](/cells/python-net/it/aspose.cells/datasorter/key2) | Rappresenta l'indice della seconda colonna ordinata (posizione assoluta, la colonna A è 0, B è 1, ...).|
| [order2](/cells/python-net/it/aspose.cells/datasorter/order2) | Rappresenta l'ordinamento della seconda chiave.|
| [key3](/cells/python-net/it/aspose.cells/datasorter/key3) | Rappresenta l'indice della terza colonna ordinata (posizione assoluta, la colonna A è 0, B è 1, ...).|
| [order3](/cells/python-net/it/aspose.cells/datasorter/order3) | Rappresenta l'ordinamento della terza chiave.|
| [sort_left_to_right](/cells/python-net/it/aspose.cells/datasorter/sort_left_to_right) |Vero significa che l'orientamento dell'ordinamento è da sinistra a destra.<br/>Falso significa che l'ordinamento avviene dall'alto verso il basso.<br/> Il valore predefinito è falso.|
| [case_sensitive](/cells/python-net/it/aspose.cells/datasorter/case_sensitive) | Ottiene e imposta se si fa distinzione tra maiuscole e minuscole durante il confronto delle stringhe.|
| [sort_as_number](/cells/python-net/it/aspose.cells/datasorter/sort_as_number) | Indica se ordinare qualsiasi cosa che assomigli a un numero.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add_key(self, key, order)`](/cells/python-net/it/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder) | Aggiunge l'indice delle colonne ordinate e l'ordine di ordinamento.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/it/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-str) | Aggiunge un indice di colonna ordinato e un criterio di ordinamento con elenco di ordinamento personalizzato.|
| [`add_key(self, key, type, order, custom_list)`](/cells/python-net/it/aspose.cells/datasorter/add_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-any) | Aggiunge un indice di colonna ordinato e un criterio di ordinamento con elenco di ordinamento personalizzato.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/it/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-list) | Aggiunge un indice di colonna ordinato e un criterio di ordinamento con elenco di ordinamento personalizzato.|
| [`sort(self, cells, start_row, start_column, end_row, end_column)`](/cells/python-net/it/aspose.cells/datasorter/sort/#aspose.cells.cells-int-int-int-int) | Ordina i dati dell'area.|
| [`sort(self, cells, area)`](/cells/python-net/it/aspose.cells/datasorter/sort/#aspose.cells.cells-aspose.cells.cellarea) | Ordina i dati dell'area.|
| [`sort(self)`](/cells/python-net/it/aspose.cells/datasorter/sort/#) | Ordina i dati nell'intervallo.|
| [`clear(self)`](/cells/python-net/it/aspose.cells/datasorter/clear/#) | Cancella tutte le impostazioni.|
| [`add_color_key(self, key, type, order, color)`](/cells/python-net/it/aspose.cells/datasorter/add_color_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-aspose.pydrawing.color) | Aggiunge una chiave di ordinamento per colore.|



###  Esempio

```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
