---
title: NameCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1010
url: /it/aspose.cells/namecollection/
is_root: false
---
##  NameCollection classe
Rappresenta una raccolta di tutti gli [`Name`](/cells/python-net/it/aspose.cells/name) oggetti nel foglio di calcolo.



Il tipo NameCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/namecollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get(self, index)`](/cells/python-net/it/aspose.cells/namecollection/get/#int) | Aggiungi API for Python tramite .Net poiché questo [indice int] non è supportato|
| [`get(self, text)`](/cells/python-net/it/aspose.cells/namecollection/get/#str) | Aggiungi API for Python tramite .Net poiché questo [testo stringa] non è supportato|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells/namecollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells/namecollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells/namecollection/index_of/#aspose.cells.name-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/namecollection/index_of/#aspose.cells.name-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells/namecollection/last_index_of/#aspose.cells.name) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells/namecollection/last_index_of/#aspose.cells.name-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/namecollection/last_index_of/#aspose.cells.name-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`add(self, text)`](/cells/python-net/it/aspose.cells/namecollection/add/#str) | Definisce un nuovo nome.|
| [`filter(self, type, sheet_index)`](/cells/python-net/it/aspose.cells/namecollection/filter/#aspose.cells.namescopetype-int) | Ottiene tutti i nomi definiti in base all'ambito.|
| [`remove_a_name(self, text)`](/cells/python-net/it/aspose.cells/namecollection/remove_a_name/#str) | Rimuovi il nome.|
| [`remove_names_by_array(self, names)`](/cells/python-net/it/aspose.cells/namecollection/remove_names_by_array/#list) | Rimuovi un array di nomi|
| [`remove_duplicate_names(self)`](/cells/python-net/it/aspose.cells/namecollection/remove_duplicate_names/#) | Rimuovi i nomi definiti duplicati|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells/namecollection/binary_search/#aspose.cells.name) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`Name`](/cells/python-net/it/aspose.cells/name)
