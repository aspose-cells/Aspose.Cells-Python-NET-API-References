---
title: GridWorkbookSettings classe
second_title: Aspose.Cells.GridJs for Python via .NET API Referenze
description:
type: docs
weight: 80
url: /it/aspose.cellsgridjs/gridworkbooksettings/
is_root: false
---
##  GridWorkbookSettings classe

Rappresenta le impostazioni della cartella di lavoro.



Il tipo GridWorkbookSettings espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/__init__/#) | Costruisce una nuova istanza di GridWorkbookSettings|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [max_iteration](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/max_iteration) | Restituisce o imposta il numero massimo di iterazioni per risolvere un riferimento circolare, il valore predefinito è 100.|
| [iteration](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/iteration) | Indica se utilizzare l'iterazione per risolvere i riferimenti circolari.|
| [force_full_calculate](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/force_full_calculate) | Indica se viene eseguito il calcolo completo ogni volta che viene attivato un calcolo.|
| [create_calc_chain](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/create_calc_chain) |Indica se creare una catena di formule calcolate. L'impostazione predefinita è falsa.|
| [re_calculate_on_open](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/re_calculate_on_open) | Indica se ricalcolare tutte le formule all'apertura del file.|
| [precision_as_displayed](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/precision_as_displayed) | Vero se i calcoli in questa cartella di lavoro verranno eseguiti utilizzando solo la precisione dei numeri così come vengono visualizzati|
| [date1904](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/date1904) | Ottiene o imposta un valore che indica se la cartella di lavoro utilizza il sistema di data 1904.|
| [enable_macros](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/enable_macros) | Abilita macro; Ora funziona solo quando si copia un foglio di lavoro in un altro foglio di lavoro in una cartella di lavoro.|
| [check_custom_number_format](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/check_custom_number_format) | Indica se controllare il formato del numero personalizzato durante l'impostazione di Style.Custom.|
| [author](/cells/python-net/it/aspose.cellsgridjs/gridworkbooksettings/author) | Ottiene/imposta l'autore del file.|



###  Esempio


```python
from aspose.cellsgridjs import GridJsWorkbook, GridWorkbookSettings

g = GridJsWorkbook()
gsettings = GridWorkbookSettings()
g.settings = gsettings

```

###  Guarda anche
* modulo [`aspose.cellsgridjs`](..)
