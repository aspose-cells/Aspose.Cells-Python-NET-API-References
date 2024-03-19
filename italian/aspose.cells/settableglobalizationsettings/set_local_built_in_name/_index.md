---
title: Metodo set_local_built_in_name
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 340
url: /it/aspose.cells/settableglobalizationsettings/set_local_built_in_name/
is_root: false
---
##  set_local_built_in_name {#str-str-bool}
Imposta il testo dipendente dalla locale per il nome integrato con il testo del nome standard specificato.



```python
def set_local_built_in_name(self, standard_name, local_name, bidirectional):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| standard_name | str |Testo del nome standard (locale en-US) del nome integrato.|
| local_name | str | Testo del nome dipendente dalla lingua|
| bidirectional | bool | Se mappa automaticamente il testo del nome locale sul testo del nome standard.<br/>Se vero, il testo del nome locale verrà mappato automaticamente al testo del nome standard<br/>quindi l'utente non dovrà chiamare nuovamente lo [`SettableGlobalizationSettings.set_standard_built_in_name`](/cells/python-net/it/aspose.cells/settableglobalizationsettings/set_standard_built_in_name)<br/> per la stessa coppia di nomi standard e locali|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`SettableGlobalizationSettings`](/cells/python-net/it/aspose.cells/settableglobalizationsettings)
