---
title: ColumnCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 280
url: /it/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection classe
Raccolta degli oggetti [`Column`](/cells/python-net/it/aspose.cells/column) che rappresentano le singole colonne (impostazioni) in un foglio di lavoro.
L'oggetto Colonna rappresenta solo le impostazioni come larghezza della colonna, stili, ecc. per l'intera colonna,
non ha nulla a che fare con il fatto che ci siano celle (dati) non vuote o meno nella colonna corrispondente.
E il "Conteggio" di questa raccolta rappresenta solo il numero di oggetti Column istanziati in questa raccolta,
non ha nulla a che fare con il fatto che ci siano celle (dati) non vuote o meno nel foglio di lavoro.



Il tipo ColumnCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/columncollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco di matrici può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [copy_to](/cells/python-net/it/aspose.cells/columncollection/copy_to/#list) | Copia l'intero elenco di matrici in un elenco di matrici unidimensionali compatibile, a partire dall'inizio dell'elenco di matrici di destinazione.|
| [copy_to](/cells/python-net/it/aspose.cells/columncollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di matrici a un elenco di matrici unidimensionali compatibile, a partire dall'indice specificato dell'elenco di matrici di destinazione.|
| [index_of](/cells/python-net/it/aspose.cells/columncollection/index_of/#aspose.cells.Column-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dall'indice specificato all'ultimo elemento.|
| [index_of](/cells/python-net/it/aspose.cells/columncollection/index_of/#aspose.cells.Column-int-int) |Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che inizia in corrispondenza dell'indice specificato e contiene il numero di elementi specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/columncollection/last_index_of/#aspose.cells.Column) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intero elenco di matrici.|
| [last_index_of](/cells/python-net/it/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dal primo elemento all'indice specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che contiene il numero di elementi specificato e termina con l'indice specificato.|
| [get_by_index](/cells/python-net/it/aspose.cells/columncollection/get_by_index/#int) | Ottiene l'oggetto colonna dall'indice.|
| [get_column_by_index](/cells/python-net/it/aspose.cells/columncollection/get_column_by_index/#int) | Ottiene l'oggetto [`Column`](/cells/python-net/it/aspose.cells/column) in base alla posizione nell'elenco.|
| [binary_search](/cells/python-net/it/aspose.cells/columncollection/binary_search/#aspose.cells.Column) | Cerca un elemento nell'intero elenco di array ordinato utilizzando l'operatore di confronto predefinito e restituisce l'indice in base zero dell'elemento.|



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
