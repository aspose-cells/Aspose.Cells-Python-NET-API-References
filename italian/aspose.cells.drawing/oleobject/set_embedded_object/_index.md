---
title: Metodo set_embedded_object
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 200
url: /it/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label) {#bool-bytes-str-bool-str}
Imposta i dati degli oggetti incorporati.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| link_to_file | bool | Indica se l'oggetto è collegato al file. Se è vero, il parametro objectData viene ignorato.|
| object_data | bytes | I dati dell'oggetto incorporato.|
| source_file_name | str | Il nome del file.|
| display_as_icon | bool | Indica se visualizzare l'oggetto come icona.<br/> Se è vero, i dati dell'immagine originale saranno coperti dall'icona.|
| label | str | Etichetta dell'icona. Funziona solo se displayAsIcon è impostato su true.|


##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon) {#bool-bytes-str-bool-str-bool}
Imposta i dati degli oggetti incorporati.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| link_to_file | bool | Indica se l'oggetto è collegato al file. Se è vero, il parametro objectData viene ignorato.|
| object_data | bytes | I dati dell'oggetto incorporato.|
| source_file_name | str | Il nome del file.|
| display_as_icon | bool | Indica se visualizzare l'oggetto come icona.<br/> Se è vero, i dati dell'immagine originale saranno coperti dall'icona.|
| label | str | Etichetta dell'icona. Funziona solo se displayAsIcon è impostato su true.|
| update_icon | bool |Indica se l'icona si aggiorna automaticamente.|
###  Osservazioni

Poiché Aspose può aggiornare e incorporare tutte le icone dei file, è meglio aggiungere l'icona corretta impostando `update_icon` su falso.


###  Guarda anche

* modulo [`aspose.cells.drawing`](../../)
* classe [`OleObject`](/cells/python-net/it/aspose.cells.drawing/oleobject)
