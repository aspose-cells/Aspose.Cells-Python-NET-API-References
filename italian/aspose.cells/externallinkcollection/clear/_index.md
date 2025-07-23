---
title: Metodo clear
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells/externallinkcollection/clear/
is_root: false
---
##  clear(self) {#}
Rimuove tutti i link esterni.



```python

def clear(self):
    ...
```


###  Osservazioni

Quando si rimuovono i collegamenti esterni, verranno rimosse anche tutte le formule che fanno riferimento ad essi perché
i riferimenti diventano non validi.

##  clear(self, update_references_as_local) {#bool}
Rimuove tutti i link esterni.



```python

def clear(self, update_references_as_local):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| update_references_as_local | bool |Aggiornare tutti i riferimenti dei collegamenti esterni nelle formule ai riferimenti della cartella di lavoro corrente.|
###  Osservazioni

Se è necessario aggiornare i riferimenti, i riferimenti dei link esterni nelle formule
verrà modificata nella cartella di lavoro corrente quando possibile.
Ad esempio, la formula originale di una cella è "='externalsource.xlam'!customfunction()",
dopo aver rimosso i link esterni, la formula diventerà "=customfunction()";
Quando la formula originale è "='[externalsource.xlam]Sheet1'!$A$1",
a seconda che nella cartella di lavoro corrente sia presente un foglio con il nome "Sheet1":
se vero, la formula diventerà "=Sheet1!$A$1";
se falso, la formula diventerà "=#REF!$A$1".

Se non è necessario aggiornare i riferimenti, tutte le formule con riferimenti a link esterni
verranno rimossi perché tali riferimenti non saranno più validi.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`ExternalLinkCollection`](/cells/python-net/it/aspose.cells/externallinkcollection)
