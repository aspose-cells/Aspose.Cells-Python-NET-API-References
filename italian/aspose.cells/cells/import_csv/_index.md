---
title: Metodo import_csv
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 620
url: /it/aspose.cells/cells/import_csv/
is_root: false
---
##  import_csv {#str-aspose.cells.TxtLoadOptions-int-int}
Importa un file CSV nelle celle.



```python
def import_csv(self, file_name, options, first_row, first_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| file_name | str | Il nome del file CSV.|
| options | [`TxtLoadOptions`](/cells/python-net/it/aspose.cells/txtloadoptions) | Le opzioni di caricamento per leggere il file di testo|
| first_row | int | Il numero di riga della prima cella in cui importare.|
| first_column | int | Il numero di colonna della prima cella in cui importare.|


##  import_csv {#io.RawIOBase-aspose.cells.TxtLoadOptions-int-int}
Importa un file CSV nelle celle.



```python
def import_csv(self, stream, options, first_row, first_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | Il flusso di file CSV.|
| options | [`TxtLoadOptions`](/cells/python-net/it/aspose.cells/txtloadoptions) | Le opzioni di caricamento per leggere il file di testo|
| first_row | int | Il numero di riga della prima cella in cui importare.|
| first_column | int | Il numero di colonna della prima cella in cui importare.|


##  import_csv {#str-str-bool-int-int}
Importa un file CSV nelle celle.



```python
def import_csv(self, file_name, splitter, convert_numeric_data, first_row, first_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| file_name | str | Il nome del file CSV.|
| splitter | str | Lo sdoppiatore|
| convert_numeric_data | bool | Indica se la stringa nel file di testo viene convertita in dati numerici.|
| first_row | int | Il numero di riga della prima cella in cui importare.|
| first_column | int | Il numero di colonna della prima cella in cui importare.|


##  import_csv {#io.RawIOBase-str-bool-int-int}
Importa un file CSV nelle celle.



```python
def import_csv(self, stream, splitter, convert_numeric_data, first_row, first_column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| stream | io.RawIOBase | Il flusso di file CSV.|
| splitter | str | Lo sdoppiatore|
| convert_numeric_data | bool | Indica se la stringa nel file di testo viene convertita in dati numerici.|
| first_row | int | Il numero di riga della prima cella in cui importare.|
| first_column | int | Il numero di colonna della prima cella in cui importare.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
