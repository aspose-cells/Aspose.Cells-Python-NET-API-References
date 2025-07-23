---
title: FindOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 640
url: /it/aspose.cells/findoptions/
is_root: false
---
##  FindOptions classe
Rappresenta le opzioni di ricerca.



Il tipo FindOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/findoptions/__init__/#) | Crea una nuova istanza di FindOptions|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [is_case_sensitive](/cells/python-net/it/aspose.cells/findoptions/is_case_sensitive) | Indica se la stringa cercata distingue tra maiuscole e minuscole.|
| [case_sensitive](/cells/python-net/it/aspose.cells/findoptions/case_sensitive) | Indica se la stringa cercata distingue tra maiuscole e minuscole.|
| [look_at_type](/cells/python-net/it/aspose.cells/findoptions/look_at_type) | Guarda il tipo.|
| [is_range_set](/cells/python-net/it/aspose.cells/findoptions/is_range_set) | Indica se l'intervallo cercato è impostato.|
| [search_next](/cells/python-net/it/aspose.cells/findoptions/search_next) |Ordine di ricerca. Vero: cerca successivo. Falso: cerca precedente.|
| [search_backward](/cells/python-net/it/aspose.cells/findoptions/search_backward) | Se cercare le celle all'indietro.|
| [seach_order_by_rows](/cells/python-net/it/aspose.cells/findoptions/seach_order_by_rows) | Indica se l'ordine di ricerca è per righe o per colonne.|
| [search_order_by_rows](/cells/python-net/it/aspose.cells/findoptions/search_order_by_rows) | Indica se l'ordine di ricerca è per righe o per colonne.|
| [look_in_type](/cells/python-net/it/aspose.cells/findoptions/look_in_type) | Guarda nel tipo.|
| [regex_key](/cells/python-net/it/aspose.cells/findoptions/regex_key) | Indica se la chiave cercata è un'espressione regolare.<br/>Se vero, la chiave cercata verrà interpretata come espressione regolare e analizzata.<br/> Altrimenti la chiave verrà analizzata secondo le regole di MS Excel.|
| [value_type_sensitive](/cells/python-net/it/aspose.cells/findoptions/value_type_sensitive) | Indica se il tipo di valore della cella cercata deve essere lo stesso della chiave cercata.|
| [style](/cells/python-net/it/aspose.cells/findoptions/style) | Formato da ricercare.|
| [convert_numeric_data](/cells/python-net/it/aspose.cells/findoptions/convert_numeric_data) | Ottiene o imposta un valore che indica se convertire il valore stringa cercato in dati numerici.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_range(self)`](/cells/python-net/it/aspose.cells/findoptions/get_range/#) | Ottiene e imposta l'intervallo cercato.|
| [`set_range(self, ca)`](/cells/python-net/it/aspose.cells/findoptions/set_range/#aspose.cells.cellarea) | Imposta l'intervallo da ricercare.|



###  Esempio

```python
from aspose.cells import CellArea, FindOptions, LookInType, Workbook

# Instantiate the workbook object
workbook = Workbook("book1.xls")
# Get Cells collection
cells = workbook.worksheets[0].cells
# Instantiate FindOptions Object
findOptions = FindOptions()
# Create a Cells Area
ca = CellArea()
ca.start_row = 8
ca.start_column = 2
ca.end_row = 17
ca.end_column = 13
# Set cells area for find options
findOptions.set_range(ca)
# Set searching properties
findOptions.search_backward = False
findOptions.seach_order_by_rows = True
findOptions.look_in_type = LookInType.VALUES
# Find the cell with 0 value
cell = cells.find(0, None, findOptions)

```

###  Guarda anche
* modulo [`aspose.cells`](..)
