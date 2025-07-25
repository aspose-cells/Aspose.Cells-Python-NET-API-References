---
title: Metodo add
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.pivot/pivottablecollection/add/
is_root: false
---
##  add(self, source_data, dest_cell_name, table_name) {#str-str-str}
Aggiunge una nuova tabella pivot.


###  ritorna

Nuovo indice cache aggiunto.


```python

def add(self, source_data, dest_cell_name, table_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_data | str | I dati per la nuova cache della tabella pivot.|
| dest_cell_name | str | Cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| table_name | str | Nome del nuovo rapporto di tabella pivot.|


##  add(self, pivot_table, dest_cell_name, table_name) {#aspose.cells.pivot.PivotTable-str-str}
Aggiunge una nuova tabella pivot basata su un'altra tabella pivot.


###  ritorna

Nuovo indice aggiunto alla tabella pivot.


```python

def add(self, pivot_table, dest_cell_name, table_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/it/aspose.cells.pivot/pivottable) | La tabella pivot di origine.|
| dest_cell_name | str | Cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| table_name | str | Nome del nuovo rapporto di tabella pivot.|


##  add(self, source_data, dest_cell_name, table_name, use_same_source) {#str-str-str-bool}
Aggiunge una nuova tabella pivot.


###  ritorna

Nuovo indice cache aggiunto.


```python

def add(self, source_data, dest_cell_name, table_name, use_same_source):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_data | str | I dati per la nuova cache della tabella pivot.|
| dest_cell_name | str | Cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| table_name | str | Nome del nuovo rapporto di tabella pivot.|
| use_same_source | bool | Indica se si sta utilizzando la stessa origine dati quando un'altra tabella pivot esistente ha utilizzato questa origine dati.<br/> Se la proprietà è vera, verrà risparmiata memoria.|


##  add(self, source_data, row, column, table_name) {#str-int-int-str}
Aggiunge una nuova tabella pivot.


###  ritorna

Nuovo indice cache aggiunto.


```python

def add(self, source_data, row, column, table_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_data | str | Intervallo di celle dati per la nuova tabella pivot. Esempio: Sheet1!A1:C8|
| row | int |Indice di riga della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| column | int | Indice di colonna della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| table_name | str | Nome del nuovo rapporto di tabella pivot.|


##  add(self, pivot_table, row, column, table_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Aggiunge una nuova tabella pivot basata su un'altra tabella pivot.


###  ritorna

Nuovo indice aggiunto alla tabella pivot.


```python

def add(self, pivot_table, row, column, table_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/it/aspose.cells.pivot/pivottable) | La tabella pivot di origine.|
| row | int |Indice di riga della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| column | int | Indice di colonna della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| table_name | str | Nome del nuovo rapporto di tabella pivot.|


##  add(self, source_data, row, column, table_name, use_same_source) {#str-int-int-str-bool}
Aggiunge una nuova tabella pivot.


###  ritorna

Nuovo indice cache aggiunto.


```python

def add(self, source_data, row, column, table_name, use_same_source):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_data | str | Intervallo di celle dati per la nuova tabella pivot. Esempio: Sheet1!A1:C8|
| row | int |Indice di riga della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| column | int | Indice di colonna della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| table_name | str | Nome del nuovo rapporto di tabella pivot.|
| use_same_source | bool | Indica se si sta utilizzando la stessa origine dati quando un'altra tabella pivot esistente ha utilizzato questa origine dati.<br/> Se la proprietà è vera, verrà risparmiata memoria.|


##  add(self, source_data, cell, table_name, use_same_source, is_xls_classic) {#str-str-str-bool-bool}
Aggiunge una nuova tabella pivot.


###  ritorna

Nuovo indice cache aggiunto.


```python

def add(self, source_data, cell, table_name, use_same_source, is_xls_classic):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_data | str | Intervallo di celle dati per la nuova tabella pivot. Esempio: Sheet1!A1:C8|
| cell | str | Cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| table_name | str | Nome del nuovo rapporto di tabella pivot.|
| use_same_source | bool | Indica se si sta utilizzando la stessa origine dati quando un'altra tabella pivot esistente ha utilizzato questa origine dati.<br/> Se la proprietà è vera, verrà risparmiata memoria.|
| is_xls_classic | bool | Indica se aggiungere la tabella pivot classica di Excel 97-2003.|


##  add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-str-str}
Aggiunge un nuovo oggetto tabella pivot alla raccolta con più intervalli di consolidamento come origine dati.


###  ritorna

Nuovo indice aggiunto alla tabella pivot.


```python

def add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_data | list | Gli intervalli di consolidamento multipli, come {"Foglio1!A1:C8","Foglio2!A1:B8"} |
| is_auto_page | bool | Se creare automaticamente un campo di pagina singola.<br/> Se è vero, il seguente parametro pageFields verrà ignorato.|
| page_fields | [`PivotPageFields`](/cells/python-net/it/aspose.cells.pivot/pivotpagefields) | Gli elementi del campo della pagina pivot.|
| dest_cell_name | str | destCellName Nome del nuovo rapporto di tabella pivot.|
| table_name | str | il nome del nuovo rapporto di tabella pivot.|


##  add(self, source_data, row, column, table_name, use_same_source, is_xls_classic) {#str-int-int-str-bool-bool}
Aggiunge una nuova tabella pivot.


###  ritorna

Nuovo indice cache aggiunto.


```python

def add(self, source_data, row, column, table_name, use_same_source, is_xls_classic):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_data | str | Intervallo di celle dati per la nuova tabella pivot. Esempio: Sheet1!A1:C8|
| row | int |Indice di riga della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| column | int | Indice di colonna della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| table_name | str | Nome del nuovo rapporto di tabella pivot.|
| use_same_source | bool | Indica se si sta utilizzando la stessa origine dati quando un'altra tabella pivot esistente ha utilizzato questa origine dati.<br/> Se la proprietà è vera, verrà risparmiata memoria.|
| is_xls_classic | bool | Indica se aggiungere la tabella pivot classica di Excel 97-2003.|


##  add(self, source_data, is_auto_page, page_fields, row, column, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str}
Aggiunge un nuovo oggetto tabella pivot alla raccolta con più intervalli di consolidamento come origine dati.


###  ritorna

Nuovo indice aggiunto alla tabella pivot.


```python

def add(self, source_data, is_auto_page, page_fields, row, column, table_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| source_data | list | Gli intervalli di consolidamento multipli, come {"Foglio1!A1:C8","Foglio2!A1:B8"} |
| is_auto_page | bool | Se creare automaticamente un campo di pagina singola.<br/> Se è vero, il seguente parametro pageFields verrà ignorato|
| page_fields | [`PivotPageFields`](/cells/python-net/it/aspose.cells.pivot/pivotpagefields) | Gli elementi del campo della pagina pivot.|
| row | int |Indice di riga della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| column | int | Indice di colonna della cella nell'angolo in alto a sinistra dell'intervallo di destinazione del report di tabella pivot.|
| table_name | str | Nome del nuovo rapporto di tabella pivot.|



###  Guarda anche
* modulo [`aspose.cells.pivot`](../../)
* classe [`PivotTableCollection`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection)
