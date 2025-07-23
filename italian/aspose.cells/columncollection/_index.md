---
title: ColumnCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 250
url: /it/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection classe
Raccolta di [`Column`](/cells/python-net/it/aspose.cells/column) oggetti che rappresentano le singole colonne (impostazioni) in un foglio di lavoro.
L'oggetto Colonna rappresenta solo le impostazioni come larghezza della colonna, stili, ecc. per l'intera colonna,
non ha nulla a che vedere con il fatto che non ci siano celle (dati) vuote o non presenti nella colonna corrispondente.
E il "Conteggio" di questa raccolta rappresenta solo il conteggio degli oggetti Colonna che sono stati istanziati in questa raccolta,
non ha nulla a che vedere con il fatto che non ci siano celle (dati) vuote o che non siano presenti nel foglio di lavoro.



Il tipo ColumnCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/columncollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells/columncollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells/columncollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells/columncollection/index_of/#aspose.cells.column-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/columncollection/index_of/#aspose.cells.column-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells/columncollection/last_index_of/#aspose.cells.column) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`get_by_index(self, index)`](/cells/python-net/it/aspose.cells/columncollection/get_by_index/#int) | Ottiene l'oggetto colonna tramite l'indice.|
| [`get_column_by_index(self, index)`](/cells/python-net/it/aspose.cells/columncollection/get_column_by_index/#int) | Ottiene l'oggetto [`Column`](/cells/python-net/it/aspose.cells/column) in base alla posizione nell'elenco.|
| [`get(self, column_index)`](/cells/python-net/it/aspose.cells/columncollection/get/#int) | Aggiungi API for Python tramite .Net.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells/columncollection/binary_search/#aspose.cells.column) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Add new Style to Workbook
style = workbook.create_style()
# Setting the background color to Blue
style.foreground_color = Color.blue
# setting Background Pattern
style.pattern = BackgroundType.SOLID
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Change the default width of first ten columns
for i in range(10):
    worksheet.cells.columns[i].width = 20.0
# Get the Column with non default formatting
columns = worksheet.cells.columns
for column in columns:
    # Apply Style to first ten Columns
    column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`Column`](/cells/python-net/it/aspose.cells/column)
