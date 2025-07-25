---
title: WorkbookRender classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 150
url: /it/aspose.cells.rendering/workbookrender/
is_root: false
---
##  WorkbookRender classe
 Rappresenta il rendering di una cartella di lavoro.
Il costruttore di questa classe deve essere utilizzato dopo la modifica dello stile della cella di pagesetup.



Il tipo WorkbookRender espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self, workbook, options)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/__init__/#aspose.cells.workbook-aspose.cells.rendering.imageorprintoptions) | Il costrutto di WorkbookRender|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [page_count](/cells/python-net/it/aspose.cells.rendering/workbookrender/page_count) | Ottiene il conteggio totale delle pagine della cartella di lavoro.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`to_image(self, stream)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/to_image/#io.rawiobase) | Esegui il rendering dell'intera cartella di lavoro come immagine Tiff per lo streaming.|
| [`to_image(self, filename)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/to_image/#str) | Esegui il rendering dell'intera cartella di lavoro come immagine Tiff in un file.|
| [`to_image(self, page_index, file_name)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/to_image/#int-str) | Esegue il rendering di una determinata pagina in un file.|
| [`to_image(self, page_index, stream)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/to_image/#int-io.rawiobase) | Esegue il rendering di una determinata pagina in un flusso.|
| [`to_printer(self, printer_name)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/to_printer/#str) | Esegui il rendering della cartella di lavoro sulla stampante|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/to_printer/#str-str) | Esegui il rendering della cartella di lavoro sulla stampante|
| [`to_printer(self, printer_settings)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings) | Esegui il rendering della cartella di lavoro sulla stampante|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Esegui il rendering della cartella di lavoro sulla stampante|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/to_printer/#str-int-int) | Esegui il rendering della cartella di lavoro sulla stampante|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/get_page_size_inch/#int) | Ottieni le dimensioni della pagina in pollici dell'immagine di output.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Utilizzando questa funzione, il cliente può controllare le impostazioni di pagina della stampante quando stampa ogni pagina.|
| [`dispose(self)`](/cells/python-net/it/aspose.cells.rendering/workbookrender/dispose/#) | Rilascia le risorse create e utilizzate per il rendering.|



###  Osservazioni



###  Guarda anche
* modulo [`aspose.cells.rendering`](..)
