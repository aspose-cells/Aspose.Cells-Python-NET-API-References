---
title: Metodo add
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.slicers/slicercollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati


###  ritorna

Il nuovo indice Slicer add


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Oggetto tabella pivot|
| dest_cell_name | str | La cella nell'angolo in alto a sinistra dell'intervallo Slicer.|
| base_field_name | str | Il nome del PivotField in PivotTable.BaseFields|

###  Esempio

```python

slicers.add(pivot, "E3", "fruit")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati


###  ritorna

Il nuovo indice Slicer add


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Oggetto tabella pivot|
| dest_cell_name | str | La cella nell'angolo in alto a sinistra dell'intervallo Slicer.|
| base_field_index | int | L'indice di PivotField in PivotTable.BaseFields|

###  Esempio

```python

slicers.add(pivot, "E20", 0)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati


###  ritorna

Il nuovo indice Slicer add


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Oggetto tabella pivot|
| dest_cell_name | str | La cella nell'angolo in alto a sinistra dell'intervallo Slicer.|
| base_field | aspose.cells.pivot.PivotField | Il campo pivot in PivotTable.BaseFields|

###  Esempio

```python

slicers.add(pivot, "I3", pivot.base_fields[0])

```


##  add(self, table, index, dest_cell_name) {#aspose.cells.tables.ListObject-int-str}
Aggiungi un nuovo Slicer utilizzando ListObjet come origine dati


###  ritorna

Il nuovo indice Slicer add


```python

def add(self, table, index, dest_cell_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | Oggetto ListObject|
| index | int | L'indice di ListColumn in ListObject.ListColumns|
| dest_cell_name | str | La cella nell'angolo in alto a sinistra dell'intervallo Slicer.|

###  Esempio

```python

slicers.add(table, 1, "E38")

```


##  add(self, table, list_column, dest_cell_name) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-str}
Aggiungi un nuovo Slicer utilizzando ListObjet come origine dati


###  ritorna

Il nuovo indice Slicer add


```python

def add(self, table, list_column, dest_cell_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | Oggetto ListObject|
| list_column | aspose.cells.tables.ListColumn | La colonna ListColumn in ListObject.ListColumns|
| dest_cell_name | str | La cella nell'angolo in alto a sinistra dell'intervallo Slicer.|

###  Esempio

```python

slicers.add(table, table.list_columns[1], "I38")

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati


###  ritorna

Il nuovo indice Slicer add


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Oggetto tabella pivot|
| row | int | Indice di riga della cella nell'angolo in alto a sinistra dell'intervallo Slicer.|
| column | int | Indice di colonna della cella nell'angolo in alto a sinistra dell'intervallo dello Slicer.|
| base_field_name | str | Il nome del PivotField in PivotTable.BaseFields|

###  Esempio

```python

slicers.add(pivot, 20, 12, "fruit")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati


###  ritorna

Il nuovo indice Slicer add


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Oggetto tabella pivot|
| row | int | Indice di riga della cella nell'angolo in alto a sinistra dell'intervallo Slicer.|
| column | int | Indice di colonna della cella nell'angolo in alto a sinistra dell'intervallo dello Slicer.|
| base_field_index | int | L'indice di PivotField in PivotTable.BaseFields|

###  Esempio

```python

slicers.add(pivot, 20, 8, 0)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati


###  ritorna

Il nuovo indice Slicer add


```python

def add(self, pivot, row, column, base_field):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Oggetto tabella pivot|
| row | int | Indice di riga della cella nell'angolo in alto a sinistra dell'intervallo Slicer.|
| column | int | Indice di colonna della cella nell'angolo in alto a sinistra dell'intervallo dello Slicer.|
| base_field | aspose.cells.pivot.PivotField | Il campo pivot in PivotTable.BaseFields|

###  Esempio

```python

slicers.add(pivot, 3, 12, pivot.base_fields[0])

```


##  add(self, table, list_column, row, column) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-int-int}
Aggiungi un nuovo Slicer utilizzando ListObjet come origine dati


###  ritorna

Il nuovo indice Slicer add


```python

def add(self, table, list_column, row, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | Oggetto ListObject|
| list_column | aspose.cells.tables.ListColumn | La colonna ListColumn in ListObject.ListColumns|
| row | int | Indice di riga della cella nell'angolo in alto a sinistra dell'intervallo Slicer.|
| column | int | Indice di colonna della cella nell'angolo in alto a sinistra dell'intervallo dello Slicer.|

###  Esempio

```python

slicers.add(table, table.list_columns[1], 38, 12)

```



###  Guarda anche
* modulo [`aspose.cells.slicers`](../../)
* classe [`SlicerCollection`](/cells/python-net/it/aspose.cells.slicers/slicercollection)
