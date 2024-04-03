---
title: Config classe
second_title: Aspose.Cells.GridJs for Python via .NET API Referenze
description:
type: docs
weight: 10
url: /it/aspose.cellsgridjs/config/
is_root: false
---
##  Config classe

Rappresenta tutte le impostazioni per GridJs



Il tipo Config espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cellsgridjs/config/__init__/#) | Costruisce una nuova istanza di Config|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [save_html_as_zip](/cells/python-net/it/aspose.cellsgridjs/config/save_html_as_zip) | Imposta/ottiene se salvare il file html come archivio zip, il valore predefinito è false.|
| [same_image_detecting](/cells/python-net/it/aspose.cellsgridjs/config/same_image_detecting) | Imposta/ottiene se verificare se l'immagine ha la stessa origine, il valore predefinito è true<br/> il valore predefinito è vero.|
| [auto_optimize_for_large_cells](/cells/python-net/it/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | Imposta/Ottiene se ottimizzare automaticamente le prestazioni di caricamento per fogli di lavoro con celle di grandi dimensioni<br/> ignora alcuni stili/bordi per ridurre il tempo di caricamento<br/> il valore predefinito è vero.|
| [islimit_shape_or_image](/cells/python-net/it/aspose.cellsgridjs/config/islimit_shape_or_image) |Imposta/Ottiene se limitare il conteggio totale di forme/immagini di visualizzazione all'interno di un foglio di lavoro, se impostato su true,<br/> GridJs limiterà la dimensione totale della forma/immagine di visualizzazione all'interno di un foglio di lavoro a MaxShapeOrImageCount<br/> il valore predefinito è vero.|
| [max_shape_or_image_count](/cells/python-net/it/aspose.cellsgridjs/config/max_shape_or_image_count) | Imposta/ottiene la forma di visualizzazione/il conteggio totale delle immagini all'interno del foglio attivo, avrà effetto quando IslimitShapes=true.<br/> il valore predefinito è 100.|
| [max_total_shape_or_image_count](/cells/python-net/it/aspose.cellsgridjs/config/max_total_shape_or_image_count) | Imposta/ottiene la forma di visualizzazione/il conteggio totale delle immagini all'interno dell'intera cartella di lavoro, avrà effetto quando IslimitShapes=true.<br/> il valore predefinito è 300.|
| [max_shape_or_image_width_or_height](/cells/python-net/it/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | Imposta/ottiene la larghezza o l'altezza massima per una forma/immagine, GridJs ignorerà la forma/immagine con larghezza o altezza maggiore di questa, avrà effetto quando IslimitShapes=true.<br/> il valore predefinito è 10000.|
| [max_pdf_save_seconds](/cells/python-net/it/aspose.cellsgridjs/config/max_pdf_save_seconds) | Imposta/ottiene il numero massimo di secondi scaduti durante il salvataggio in PDF.<br/> il valore predefinito è 10.|
| [ignore_empty_content](/cells/python-net/it/aspose.cellsgridjs/config/ignore_empty_content) | Imposta/Ottiene se mostrare l'intervallo massimo che include dati, stile, celle unite e forme.<br/> se l'ultima riga o colonna contiene celle senza valore e formula ma ha uno stile personalizzato<br/>quindi non mostreremo questa riga/colonna quando questo valore è vero.<br/> il valore predefinito è true.|
| [use_print_area](/cells/python-net/it/aspose.cellsgridjs/config/use_print_area) |Imposta/ottiene se utilizzare PageSetup.PrintArea per l'intervallo di visualizzazione dell'interfaccia utente quando il foglio di lavoro dispone dell'impostazione PageSetup per PrintArea.<br/> Il valore predefinito è falso .|
| [load_time_out](/cells/python-net/it/aspose.cellsgridjs/config/load_time_out) | Imposta/Ottiene un'interruzione di timeout in millisecondi nel caricamento del file, quando il periodo di tempo di costo del caricamento del file è più lungo delle aspettative, genererà un'eccezione.<br/> il valore predefinito è -1, il che significa che non è impostato alcun interrupt di timeout.|
| [show_chart_sheet](/cells/python-net/it/aspose.cellsgridjs/config/show_chart_sheet) | Imposta/Ottiene se mostrare il foglio di lavoro del grafico.<br/> Il valore predefinito è falso .|
| [page_size](/cells/python-net/it/aspose.cellsgridjs/config/page_size) | Imposta/Ottiene se eseguire l'impaginazione<br/> GridJs limiterà la dimensione della riga in base a PageSize, se PageSize è -1, non eseguirà l'impaginazione<br/> il valore predefinito è -1|
| [empty_sheet_max_row](/cells/python-net/it/aspose.cellsgridjs/config/empty_sheet_max_row) | Imposta/ottiene la riga massima predefinita per un foglio di lavoro vuoto.<br/> il valore predefinito è 12.|
| [empty_sheet_max_col](/cells/python-net/it/aspose.cellsgridjs/config/empty_sheet_max_col) | Imposta/ottiene la colonna massima predefinita per un foglio di lavoro vuoto.<br/> il valore predefinito è 15.|
| [picture_cache_directory](/cells/python-net/it/aspose.cellsgridjs/config/picture_cache_directory) | Imposta/Ottiene la directory della cache per le immagini. (questo avrà effetto quando GridJsWorkbook.CacheImp è nullo)<br/> il percorso predefinito sarà "_piccache" all'interno della FileCacheDirectory.|
| [file_cache_directory](/cells/python-net/it/aspose.cellsgridjs/config/file_cache_directory) |Imposta/Ottiene la directory della cache per il file del foglio di calcolo.<br/> Dobbiamo impostarlo su un percorso specifico prima di utilizzare GridJs.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [set_license](/cells/python-net/it/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/cells/python-net/it/aspose.cellsgridjs/config/set_license/#io.RawIOBase) | Concede in licenza il componente.|
| [set_font_folder](/cells/python-net/it/aspose.cellsgridjs/config/set_font_folder/#str-bool) | Imposta la cartella dei caratteri|
| [set_font_folders](/cells/python-net/it/aspose.cellsgridjs/config/set_font_folders/#list-bool) | Imposta le cartelle dei caratteri|



###  Guarda anche
* modulo [`aspose.cellsgridjs`](..)
