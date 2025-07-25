---
title: SheetRender classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 110
url: /it/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender classe
Rappresenta un rendering del foglio di lavoro che può convertire il foglio di lavoro in varie immagini, ad esempio (BMP, PNG, JPEG, TIFF..)
Il costruttore di questa classe deve essere utilizzato dopo la modifica dello stile della cella di pagesetup.



Il tipo SheetRender espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self, worksheet, options)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.worksheet-aspose.cells.rendering.imageorprintoptions) | la struttura di SheetRender, necessita di worksheet e ImageOrPrintOptions come parametri|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [page_count](/cells/python-net/it/aspose.cells.rendering/sheetrender/page_count) | Ottiene il conteggio totale delle pagine del foglio di lavoro corrente.|
| [page_scale](/cells/python-net/it/aspose.cells.rendering/sheetrender/page_scale) | Ottiene la scala di pagina calcolata del foglio.<br/> Restituisce la scala impostata se è impostato [`PageSetup.zoom`](/cells/python-net/it/aspose.cells/pagesetup#zoom). In caso contrario, restituisce la scala calcolata in base a [`PageSetup.fit_to_pages_wide`](/cells/python-net/it/aspose.cells/pagesetup#fit_to_pages_wide) e [`PageSetup.fit_to_pages_tall`](/cells/python-net/it/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`to_image(self, page_index, file_name)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_image/#int-str) | Esegue il rendering di una determinata pagina in un file.|
| [`to_image(self, page_index, stream)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_image/#int-io.rawiobase) | Esegue il rendering di una determinata pagina in un flusso.|
| [`to_tiff(self, stream)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_tiff/#io.rawiobase) | Esegui il rendering dell'intero foglio di lavoro come immagine Tiff per lo streaming.|
| [`to_tiff(self, filename)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_tiff/#str) | Trasforma l'intero foglio di lavoro in un file immagine Tiff.|
| [`to_printer(self, printer_name)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#str) | Esegui il rendering del foglio di lavoro sulla stampante|
| [`to_printer(self, printer_name, job_name)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Esegui il rendering del foglio di lavoro sulla stampante|
| [`to_printer(self, printer_settings)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings) | Esegui il rendering del foglio di lavoro sulla stampante|
| [`to_printer(self, printer_settings, job_name)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.printersettings-str) | Esegui il rendering del foglio di lavoro sulla stampante|
| [`to_printer(self, printer_name, print_page_index, print_page_count)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Esegui il rendering del foglio di lavoro sulla stampante|
| [`get_page_size_inch(self, page_index)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Ottieni le dimensioni della pagina in pollici dell'immagine di output.|
| [`custom_print(self, next_page_after_print, print_page_event_args)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.printpageeventargs) | Utilizzando questa funzione, il cliente può controllare le impostazioni di pagina della stampante quando stampa ogni pagina.|
| [`dispose(self)`](/cells/python-net/it/aspose.cells.rendering/sheetrender/dispose/#) | Rilascia le risorse create e utilizzate per il rendering.|



###  Guarda anche
* modulo [`aspose.cells.rendering`](..)
