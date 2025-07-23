---
title: OoxmlSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1050
url: /it/aspose.cells/ooxmlsaveoptions/
is_root: false
---
##  OoxmlSaveOptions classe
Rappresenta le opzioni per salvare il file XML di Office Open.



**Eredità:** [`OoxmlSaveOptions`](/cells/python-net/aspose.cells/ooxmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)



Il tipo OoxmlSaveOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/__init__/#) | Crea le opzioni per salvare il file Office Open XML.|
| [`__init__(self, save_format)`](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/__init__/#aspose.cells.saveformat) | Crea le opzioni per salvare il file Office Open XML.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [save_format](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/save_format) | Ottiene il formato del file di salvataggio.|
| [clear_data](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/clear_data) | Dopo aver salvato il file, svuotare la cartella di lavoro.|
| [cached_file_folder](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/cached_file_folder) | Cartella per i file temporanei che possono essere utilizzati come cache di dati.|
| [validate_merged_areas](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/validate_merged_areas) | Indica se convalidare le celle unite prima di salvare il file.|
| [merge_areas](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/merge_areas) | Indica se unire le aree di formattazione condizionale e convalida prima di salvare il file.|
| [create_directory](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/create_directory) | Se è vero e la directory non esiste, la directory verrà creata automaticamente prima di salvare il file.|
| [sort_names](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/sort_names) |Indica se ordinare i nomi definiti prima di salvare il file.|
| [sort_external_names](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/sort_external_names) | Indica se ordinare i nomi definiti esternamente prima di salvare il file.|
| [refresh_chart_cache](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/refresh_chart_cache) | Indica se aggiornare i dati della cache del grafico|
| [check_excel_restriction](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/check_excel_restriction) | Se verificare la restrizione del file Excel quando l'utente modifica celle con oggetti correlati.<br/>Ad esempio, Excel non consente di immettere valori stringa più lunghi di 32K.<br/> Se si immette un valore più lungo di 32K, questo verrà troncato.|
| [update_smart_art](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/update_smart_art) | Indica se aggiornare l'impostazione SmartArt.<br/> Il valore predefinito è falso.|
| [encrypt_document_properties](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/encrypt_document_properties) | Indica se crittografare le proprietà del documento quando si salva come file .xls.<br/> Il valore predefinito è vero.|
| [export_cell_name](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/export_cell_name) | Indica se il nome della cella deve essere esportato nel file Excel2007 .xlsx (.xlsm, .xltx, .xltm).<br/>Se il file di output è accessibile tramite SQL Server DTS, questo valore deve essere true.<br/>Impostando il valore su false si aumenteranno notevolmente le prestazioni e si ridurranno le dimensioni del file quando si creano file di grandi dimensioni.<br/> Il valore predefinito è vero.|
| [update_zoom](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/update_zoom) | Indica se aggiornare il fattore di scala prima di salvare il file<br/> se le proprietà PageSetup.FitToPagesWide e PageSetup.FitToPagesTall controllano il modo in cui viene ridimensionato il foglio di lavoro.|
| [enable_zip64](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/enable_zip64) | Utilizzare sempre le estensioni ZIP64 quando si scrivono archivi zip, anche quando non sono necessarie.|
| [embed_ooxml_as_ole_object](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/embed_ooxml_as_ole_object) | Indica se incorporare i file Ooxml di OleObject come oggetto ole.|
| [compression_type](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/compression_type) | Ottiene e imposta il tipo di compressione per il file ooxml.|
| [wps_compatibility](/cells/python-net/it/aspose.cells/ooxmlsaveoptions/wps_compatibility) | Indica se rendere xls più compatibile con WPS.|



###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`OoxmlSaveOptions`](/cells/python-net/it/aspose.cells/ooxmlsaveoptions)
* classe [`SaveOptions`](/cells/python-net/it/aspose.cells/saveoptions)
