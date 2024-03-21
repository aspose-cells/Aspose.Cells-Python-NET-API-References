---
title: ExportTableOptions classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 580
url: /it/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions classe
Rappresenta tutte le opzioni della tabella di esportazione.



Il tipo ExportTableOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/exporttableoptions/__init__/#) | Costruisce una nuova istanza di ExportTableOptions|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [export_column_name](/cells/python-net/it/aspose.cells/exporttableoptions/export_column_name) | Indica se i dati nella prima riga vengono esportati nel nome della colonna di DataTable.<br/> Il valore predefinito è falso.|
| [skip_error_value](/cells/python-net/it/aspose.cells/exporttableoptions/skip_error_value) | Indica se ignorare il valore non valido per la colonna.<br/> Ad esempio, se il tipo di colonna è decimal, il valore è maggiore di decimal.MaxValue<br/>e questa proprietà è vera, non genereremo nuovamente un'eccezione.<br/> Il valore predefinito è falso.|
| [plot_visible_cells](/cells/python-net/it/aspose.cells/exporttableoptions/plot_visible_cells) | Esporta solo le celle visibili.|
| [plot_visible_rows](/cells/python-net/it/aspose.cells/exporttableoptions/plot_visible_rows) | Esporta solo le righe visibili.|
| [plot_visible_columns](/cells/python-net/it/aspose.cells/exporttableoptions/plot_visible_columns) | Esporta solo le colonne visibili.|
| [export_as_string](/cells/python-net/it/aspose.cells/exporttableoptions/export_as_string) | Esporta il valore stringa delle celle in DataTable.|
| [export_as_html_string](/cells/python-net/it/aspose.cells/exporttableoptions/export_as_html_string) | Esporta il valore della stringa html delle celle nel DataTable.|
| [format_strategy](/cells/python-net/it/aspose.cells/exporttableoptions/format_strategy) | Ottiene e imposta la strategia di formato durante l'esportazione del valore come valore stringa.|
| [check_mixed_value_type](/cells/python-net/it/aspose.cells/exporttableoptions/check_mixed_value_type) | Falso, Aspose.Cells imposterà il tipo di DataColumn in base al tipo di valore della prima riga per le prestazioni.<br/> È vero, Aspose.Cells controllerà se il tipo di valore nella colonna è misto prima di impostare il tipo di DataColumn<br/> il tipo di valore è misto, il tipo di DataColumn sarà stringa.|
| [allow_db_null](/cells/python-net/it/aspose.cells/exporttableoptions/allow_db_null) | Questo valore indica se i DBNull sono consentiti in questa tabella.|
| [is_vertical](/cells/python-net/it/aspose.cells/exporttableoptions/is_vertical) | Vero se una riga nel file della cartella di lavoro rappresenta una riga in DataTable. False se una colonna nel file della cartella di lavoro rappresenta una riga in DataTable.|
| [indexes](/cells/python-net/it/aspose.cells/exporttableoptions/indexes) | Gli indici di colonne/righe che dovrebbero essere esportati.|
| [rename_strategy](/cells/python-net/it/aspose.cells/exporttableoptions/rename_strategy) | Strategia per nomi duplicati di colonne.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [preprocess_exported_value](/cells/python-net/it/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.CellValue) | Preelaborare il valore della cella corrente da esportare.|



###  Osservazioni

Se sono presenti requisiti speciali sull'esportazione, come ignorare i valori di errore, l'utente può estendere questa classe
per sovrascrivere le API corrispondenti per raggiungere l'obiettivo.

###  Guarda anche
* modulo [`aspose.cells`](..)
