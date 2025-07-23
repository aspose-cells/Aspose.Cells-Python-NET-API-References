---
title: sever_command proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 300
url: /it/aspose.cells.externalconnections/dbconnection/sever_command/
is_root: false
---
##  sever_command proprietà

 Specifica una seconda stringa di testo del comando che viene mantenuta quando basata sul server PivotTable
 i campi della pagina sono in uso.
 Per le connessioni ODBC, serverCommand è solitamente una query più ampia di command (no
La clausola WHERE è presente nel primo. Sulla base di questi 2 comandi (Command e ServerCommand),
l'interfaccia utente dei parametri può essere popolata e possono essere costruite query parametrizzate

###  Osservazioni

 NOTA: questa proprietà è ora obsoleta. Invece,
si prega di utilizzare la proprietà ExternalConnection.SecondCommand.
 Questo metodo verrà rimosso 12 mesi dopo, a partire da ottobre 2024.
Aspose si scusa per ogni eventuale disagio arrecato.
###  Definizione:
```python
@property
def sever_command(self):
    ...
@sever_command.setter
def sever_command(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.externalconnections`](../../)
* classe [`DBConnection`](/cells/python-net/it/aspose.cells.externalconnections/dbconnection)
