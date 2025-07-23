---
title: ConnectionParameter classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells.externalconnections/connectionparameter/
is_root: false
---
##  ConnectionParameter classe
Specifica le proprietà relative a tutti i parametri utilizzati con connessioni dati esterne
I parametri sono validi per le query ODBC e web.



Il tipo ConnectionParameter espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [sql_type](/cells/python-net/it/aspose.cells.externalconnections/connectionparameter/sql_type) | Tipo di dati SQL del parametro. Valido solo per sorgenti ODBC.|
| [refresh_on_change](/cells/python-net/it/aspose.cells.externalconnections/connectionparameter/refresh_on_change) | Flag che indica se la query deve essere aggiornata automaticamente quando il contenuto di un<br/> La cella che fornisce il valore del parametro cambia. Se è vero, i dati esterni vengono aggiornati.<br/> utilizzando il nuovo valore del parametro ogni volta che si verifica una modifica. Se falso, allora dati esterni<br/> viene aggiornato solo quando richiesto dall'utente o quando un altro evento attiva l'aggiornamento (ad esempio, cartella di lavoro aperta).|
| [prompt](/cells/python-net/it/aspose.cells.externalconnections/connectionparameter/prompt) | Stringa di richiesta per il parametro. Presentata all'utente del foglio di calcolo insieme all'interfaccia utente di input.<br/> per raccogliere il valore del parametro prima di aggiornare i dati esterni. Utilizzato solo quando<br/>tipoparametro = prompt.|
| [type](/cells/python-net/it/aspose.cells.externalconnections/connectionparameter/type) | Tipo di parametro utilizzato.<br/> Se il parametro Tipo = valore, allora il valore può essere booleano, doppio, intero,<br/> o stringa verrà utilizzata. In questo caso, ci si aspetta che solo uno dei<br/> Verrà specificato {booleano, doppio, intero o stringa}.|
| [name](/cells/python-net/it/aspose.cells.externalconnections/connectionparameter/name) | Il nome del parametro.|
| [cell_reference](/cells/python-net/it/aspose.cells.externalconnections/connectionparameter/cell_reference) | Riferimento Cell che indica il valore della cella da utilizzare per il parametro di query. Utilizzato solo quando parameterType è cell.|
| [value](/cells/python-net/it/aspose.cells.externalconnections/connectionparameter/value) | Valore numerico non intero, valore intero, valore stringa o valore booleano<br/> Da usare come parametro di query. Utilizzato solo quando parameterType è un valore.|



###  Guarda anche
* modulo [`aspose.cells.externalconnections`](..)
