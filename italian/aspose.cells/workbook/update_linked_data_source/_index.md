---
title: Metodo update_linked_data_source
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 440
url: /it/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source(self, external_workbooks) {#list}
Se questa cartella di lavoro contiene collegamenti esterni ad altre fonti di dati,
Aspose.Cells tenterà di recuperare i dati più recenti dalle fonti indicate.



```python

def update_linked_data_source(self, external_workbooks):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| external_workbooks | list | Cartelle di lavoro che verranno utilizzate per aggiornare i dati dei link esterni a cui fa riferimento questa cartella di lavoro.<br/>La corrispondenza di queste cartelle di lavoro con i link esterni è determinata da [`Workbook.file_name`](/cells/python-net/it/aspose.cells/workbook#file_name)<br/>e [`ExternalLink.data_source`](/cells/python-net/it/aspose.cells/externallink#data_source). Quindi assicurati che [`Workbook.file_name`](/cells/python-net/it/aspose.cells/workbook#file_name) abbia<br/> sono stati specificati con il valore appropriato per ogni cartella di lavoro in modo che possano essere collegati al collegamento esterno corrispondente.|
###  Osservazioni

Se non è possibile trovare il collegamento esterno corrispondente per una cartella di lavoro, questa cartella di lavoro verrà ignorata.
Quindi, quando in seguito imposti una formula con un nuovo collegamento esterno, intendi ignorare la cartella di lavoro
essere collegato ad esso, il collegamento non potrà essere eseguito finché non si richiama nuovamente questo metodo con quelle cartelle di lavoro.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
