---
title: WorksheetCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1610
url: /it/aspose.cells/worksheetcollection/
is_root: false
---
##  WorksheetCollection classe
Incapsula una raccolta di [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet) oggetti.



Il tipo WorksheetCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/it/aspose.cells/worksheetcollection/web_extension_task_panes) | Ottiene l'elenco dei riquadri attività.|
| [web_extensions](/cells/python-net/it/aspose.cells/worksheetcollection/web_extensions) | Ottiene l'elenco dei riquadri attività.|
| [threaded_comment_authors](/cells/python-net/it/aspose.cells/worksheetcollection/threaded_comment_authors) | Ottiene l'elenco degli autori dei commenti con thread.|
| [is_refresh_all_connections](/cells/python-net/it/aspose.cells/worksheetcollection/is_refresh_all_connections) | Indica se aggiornare tutte le connessioni all'apertura del file in MS Excel.|
| [names](/cells/python-net/it/aspose.cells/worksheetcollection/names) | Ottiene la raccolta di tutti gli oggetti Name nel foglio di calcolo.|
| [active_sheet_name](/cells/python-net/it/aspose.cells/worksheetcollection/active_sheet_name) | Rappresenta il nome del foglio di lavoro attivo quando il foglio di calcolo viene aperto.|
| [active_sheet_index](/cells/python-net/it/aspose.cells/worksheetcollection/active_sheet_index) | Rappresenta l'indice del foglio di lavoro attivo quando il foglio di calcolo è aperto.|
| [dxfs](/cells/python-net/it/aspose.cells/worksheetcollection/dxfs) | Ottiene i record di formattazione differenziale master.|
| [xml_maps](/cells/python-net/it/aspose.cells/worksheetcollection/xml_maps) | Ottiene e imposta le mappe XML nella cartella di lavoro.|
| [built_in_document_properties](/cells/python-net/it/aspose.cells/worksheetcollection/built_in_document_properties) | Restituisce una raccolta [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà del documento integrate nel foglio di calcolo.|
| [custom_document_properties](/cells/python-net/it/aspose.cells/worksheetcollection/custom_document_properties) | Restituisce una raccolta [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà personalizzate del documento del foglio di calcolo.|
| [ole_size](/cells/python-net/it/aspose.cells/worksheetcollection/ole_size) | Ottiene e imposta la dimensione visualizzata quando il file Workbook viene utilizzato come oggetto Ole.|
| [external_links](/cells/python-net/it/aspose.cells/worksheetcollection/external_links) |Rappresenta i collegamenti esterni in una cartella di lavoro.|
| [table_styles](/cells/python-net/it/aspose.cells/worksheetcollection/table_styles) | Ottiene l'oggetto [`WorksheetCollection.table_styles`](/cells/python-net/it/aspose.cells/worksheetcollection#table_styles).|
| [revision_logs](/cells/python-net/it/aspose.cells/worksheetcollection/revision_logs) | Rappresenta i registri di revisione.|
| [sensitivity_labels](/cells/python-net/it/aspose.cells/worksheetcollection/sensitivity_labels) | Rappresenta tutte le etichette di sensibilità.|
| [capacity](/cells/python-net/it/aspose.cells/worksheetcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|



Ottiene l'elemento [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet) all'indice specificato.
###  Indicizzatore
| Nome| Descrizione|
| :- | :- |
| [index] | Indice basato su zero dell'elemento.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get(self, index)`](/cells/python-net/it/aspose.cells/worksheetcollection/get/#int) | Aggiungi API for Python tramite .Net poiché questo [indice int] non è supportato|
| [`get(self, sheet_name)`](/cells/python-net/it/aspose.cells/worksheetcollection/get/#str) | Aggiungi API for Python tramite .Net poiché questo [string sheetName] non è supportato|
| [`add(self, type)`](/cells/python-net/it/aspose.cells/worksheetcollection/add/#aspose.cells.sheettype) | Aggiunge un foglio di lavoro alla raccolta.|
| [`add(self)`](/cells/python-net/it/aspose.cells/worksheetcollection/add/#) | Aggiunge un foglio di lavoro alla raccolta.|
| [`add(self, sheet_name)`](/cells/python-net/it/aspose.cells/worksheetcollection/add/#str) | Aggiunge un foglio di lavoro alla raccolta.|
| [`register_add_in_function(self, add_in_file, function_name, lib)`](/cells/python-net/it/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | Aggiunge la funzione addin alla cartella di lavoro|
| [`register_add_in_function(self, id, function_name)`](/cells/python-net/it/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | Aggiunge la funzione addin alla cartella di lavoro|
| [`add_copy(self, sheet_name)`](/cells/python-net/it/aspose.cells/worksheetcollection/add_copy/#str) | Aggiunge un foglio di lavoro alla raccolta e copia i dati da un foglio di lavoro esistente.|
| [`add_copy(self, sheet_index)`](/cells/python-net/it/aspose.cells/worksheetcollection/add_copy/#int) | Aggiunge un foglio di lavoro alla raccolta e copia i dati da un foglio di lavoro esistente.|
| [`add_copy(self, source, dest_sheet_names)`](/cells/python-net/it/aspose.cells/worksheetcollection/add_copy/#list-list) | Copia un gruppo di fogli di lavoro.|
| [`get_range_by_name(self, range_name)`](/cells/python-net/it/aspose.cells/worksheetcollection/get_range_by_name/#str) | Ottiene l'oggetto Range in base al nome predefinito.|
| [`get_range_by_name(self, range_name, current_sheet_index, include_table)`](/cells/python-net/it/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | Ottiene [`Range`](/cells/python-net/it/aspose.cells/range) tramite il nome predefinito o il nome della tabella|
| [`refresh_pivot_tables(self)`](/cells/python-net/it/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | Aggiorna tutte le tabelle pivot nel file Excel.|
| [`refresh_pivot_tables(self, option)`](/cells/python-net/it/aspose.cells/worksheetcollection/refresh_pivot_tables/#aspose.cells.pivot.pivottablerefreshoption) | Aggiorna tutte le tabelle pivot nel file Excel.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells/worksheetcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`create_range(self, address, sheet_index)`](/cells/python-net/it/aspose.cells/worksheetcollection/create_range/#str-int) | Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da un indirizzo compreso nell'intervallo.|
| [`create_union_range(self, address, sheet_index)`](/cells/python-net/it/aspose.cells/worksheetcollection/create_union_range/#str-int) | Crea un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) da un indirizzo compreso nell'intervallo.|
| [`get_sheet_by_code_name(self, code_name)`](/cells/python-net/it/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | Ottiene il foglio di lavoro tramite il nome in codice.|
| [`sort_names(self)`](/cells/python-net/it/aspose.cells/worksheetcollection/sort_names/#) | Ordina i nomi definiti.|
| [`swap_sheet(self, sheet_index1, sheet_index2)`](/cells/python-net/it/aspose.cells/worksheetcollection/swap_sheet/#int-int) | Scambia i due fogli.|
| [`remove_by_name(self, name)`](/cells/python-net/it/aspose.cells/worksheetcollection/remove_by_name/#str) | Rimuovi un foglio in base al nome del foglio. (CELLSPYTHONNET-192)|
| [`remove_by_index(self, index)`](/cells/python-net/it/aspose.cells/worksheetcollection/remove_by_index/#int) | Rimuovi un indice foglio per foglio|
| [`remove_at(self, name)`](/cells/python-net/it/aspose.cells/worksheetcollection/remove_at/#str) | Rimuove l'elemento con il nome specificato.|
| [`get_named_ranges(self)`](/cells/python-net/it/aspose.cells/worksheetcollection/get_named_ranges/#) | Ottiene tutti gli intervalli denominati predefiniti nel foglio di calcolo.|
| [`get_named_ranges_and_tables(self)`](/cells/python-net/it/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | Ottiene tutti gli intervalli denominati predefiniti nel foglio di calcolo.|
| [`set_ole_size(self, start_row, end_row, start_column, end_column)`](/cells/python-net/it/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | Imposta la dimensione visualizzata quando il file Workbook viene utilizzato come oggetto Ole.|
| [`clear_pivottables(self)`](/cells/python-net/it/aspose.cells/worksheetcollection/clear_pivottables/#) |Cancella le tabelle pivot dal foglio di calcolo.|
| [`refresh_all(self)`](/cells/python-net/it/aspose.cells/worksheetcollection/refresh_all/#) | Aggiorna tutte le tabelle pivot e i grafici con la sorgente pivot.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells/worksheetcollection/binary_search/#aspose.cells.worksheet) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
sheets = workbook.worksheets
# Add a worksheet
sheets.add()
# Change the name of a worksheet
sheets[0].name = "First Sheet"
# Set the active sheet to the second worksheet
sheets.active_sheet_index = 1

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty)
* classe [`Range`](/cells/python-net/it/aspose.cells/range)
* classe [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet)
