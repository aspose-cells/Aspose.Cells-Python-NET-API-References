---
title: CustomDocumentPropertyCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells.properties/customdocumentpropertycollection/
is_root: false
---
##  CustomDocumentPropertyCollection classe
Una raccolta di proprietà personalizzate dei documenti.



**Eredità:** [`CustomDocumentPropertyCollection`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection)



Il tipo CustomDocumentPropertyCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get(self, name)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/get/#str) |  |
| [`get(self, index)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/get/#int) |  |
| [`index_of(self, name)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/index_of/#str) |  |
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`add(self, name, value)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/add/#str-str) | Crea una nuova proprietà del documento personalizzata del**PropertyType.String** tipo di dati.|
| [`add(self, name, value)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/add/#str-int) | Crea una nuova proprietà del documento personalizzata del**PropertyType.Numero** tipo di dati.|
| [`add(self, name, value)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/add/#str-datetime) | Crea una nuova proprietà del documento personalizzata del**PropertyType.DateTime** tipo di dati.|
| [`add(self, name, value)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/add/#str-bool) | Crea una nuova proprietà del documento personalizzata del**PropertyType.Boolean** tipo di dati.|
| [`add(self, name, value)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/add/#str-float) | Crea una nuova proprietà del documento personalizzata del**PropertyType.Float** tipo di dati.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/binary_search/#aspose.cells.properties.documentproperty) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|
| [`add_link_to_content(self, name, source)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/add_link_to_content/#str-str) |Crea una nuova proprietà personalizzata del documento che si collega al contenuto.|
| [`update_linked_property_value(self)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/update_linked_property_value/#) | Aggiorna il valore della proprietà del documento personalizzato che collega al contenuto.|
| [`update_linked_range(self)`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection/update_linked_range/#) | Aggiorna il valore della proprietà del documento personalizzato all'intervallo collegato.|



###  Osservazioni

Ogni oggetto [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty) rappresenta una proprietà personalizzata di un documento contenitore.

###  Esempio

```python
from aspose.cells import Workbook

# Instantiate a Workbook object
workbook = Workbook("book1.xls")
# Retrieve a list of all custom document properties of the Excel file
customProperties = workbook.worksheets.custom_document_properties

```

###  Guarda anche
* modulo [`aspose.cells.properties`](..)
* classe [`CustomDocumentPropertyCollection`](/cells/python-net/it/aspose.cells.properties/customdocumentpropertycollection)
* classe [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty)
