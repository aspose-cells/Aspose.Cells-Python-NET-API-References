---
title: Metodo update_linked_data_source
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 420
url: /it/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source {#list}
Se questa cartella di lavoro contiene collegamenti esterni ad altre origini dati,
Aspose.Cells tenterà di recuperare i dati più recenti dalle fonti fornite.



```python
def update_linked_data_source(self, external_workbooks):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| external_workbooks | list | Cartelle di lavoro che verranno utilizzate per aggiornare i dati dei collegamenti esterni a cui fa riferimento questa cartella di lavoro.<br/>La corrispondenza di tali cartelle di lavoro con collegamenti esterni è determinata da [`Workbook.file_name`](/cells/python-net/it/aspose.cells/workbook#file_name)<br/>e [`ExternalLink.data_source`](/cells/python-net/it/aspose.cells/externallink#data_source). Quindi assicurati che [`Workbook.file_name`](/cells/python-net/it/aspose.cells/workbook#file_name) lo abbia<br/> stato specificato con il valore corretto per ogni cartella di lavoro in modo che possano essere collegati al collegamento esterno corrispondente.|
###  Osservazioni

Se non è possibile trovare il collegamento esterno corrispondente per una cartella di lavoro, questa cartella di lavoro verrà ignorata.
Pertanto, quando imposti una formula in un secondo momento con un nuovo collegamento esterno che intendi rendere la cartella di lavoro ignorata
essere collegato ad esso, il collegamento non può essere eseguito finché non si chiama nuovamente questo metodo con quelle cartelle di lavoro.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
