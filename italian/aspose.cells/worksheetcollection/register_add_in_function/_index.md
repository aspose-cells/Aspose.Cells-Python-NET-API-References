---
title: Metodo register_add_in_function
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 180
url: /it/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function(self, id, function_name) {#int-str}
Aggiunge la funzione addin alla cartella di lavoro


###  ritorna

URL del file aggiuntivo che contiene le funzioni aggiuntive


```python

def register_add_in_function(self, id, function_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| id | int |ID dei dati che contengono funzioni aggiuntive,<br/> può essere ottenuto chiamando per la prima volta il numero [`WorksheetCollection.register_add_in_function`](/cells/python-net/it/aspose.cells/worksheetcollection/register_add_in_function) per lo stesso file aggiuntivo.|
| function_name | str | il nome della funzione aggiuntiva|


##  register_add_in_function(self, add_in_file, function_name, lib) {#str-str-bool}
Aggiunge la funzione addin alla cartella di lavoro


###  ritorna

ID dei dati che contengono la funzione aggiuntiva specificata


```python

def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| add_in_file | str | il file contiene le funzioni aggiuntive|
| function_name | str | il nome della funzione aggiuntiva|
| lib | bool | se il file aggiuntivo specificato si trova nella directory o nella sottodirectory della libreria dei componenti aggiuntivi della cartella di lavoro.<br/>Questo flag ha effetto e fa la differenza quando addInFile specificato ha un percorso relativo:<br/> true indica che il percorso è relativo alla libreria dei componenti aggiuntivi e false indica che il percorso è relativo a questa cartella di lavoro.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`WorksheetCollection`](/cells/python-net/it/aspose.cells/worksheetcollection)
