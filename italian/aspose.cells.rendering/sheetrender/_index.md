---
title: SheetRender classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 120
url: /it/aspose.cells.rendering/sheetrender/
is_root: false
---
##  SheetRender classe
Rappresenta un rendering del foglio di lavoro che può eseguire il rendering del foglio di lavoro in varie immagini come (BMP, PNG, JPEG, TIFF..)
Il costruttore di questa classe, deve essere utilizzato dopo la modifica di pagesetup, stile cella.



Il tipo SheetRender espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells.rendering/sheetrender/__init__/#aspose.cells.Worksheet-aspose.cells.rendering.ImageOrPrintOptions) | il costrutto di SheetRender, necessita di foglio di lavoro e ImageOrPrintOptions come parametri|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [page_count](/cells/python-net/it/aspose.cells.rendering/sheetrender/page_count) | Ottiene il conteggio totale delle pagine del foglio di lavoro corrente.|
| [page_scale](/cells/python-net/it/aspose.cells.rendering/sheetrender/page_scale) | Ottiene la scala di pagina calcolata del foglio.<br/> Restituisce la scala impostata se è impostato [`PageSetup.zoom`](/cells/python-net/it/aspose.cells/pagesetup#zoom). Altrimenti restituisce la scala calcolata in base a [`PageSetup.fit_to_pages_wide`](/cells/python-net/it/aspose.cells/pagesetup#fit_to_pages_wide) e [`PageSetup.fit_to_pages_tall`](/cells/python-net/it/aspose.cells/pagesetup#fit_to_pages_tall).|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [to_image](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_image/#int-str) |Renderizza una determinata pagina in un file.|
| [to_image](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_image/#int-io.RawIOBase) | Visualizza una determinata pagina in uno stream.|
| [to_tiff](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_tiff/#io.RawIOBase) | Visualizza l'intero foglio di lavoro come immagine Tiff per lo streaming.|
| [to_tiff](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_tiff/#str) | Visualizza l'intero foglio di lavoro come immagine Tiff in un file.|
| [to_printer](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#str) | Rendering del foglio di lavoro sulla stampante|
| [to_printer](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#str-str) | Rendering del foglio di lavoro sulla stampante|
| [to_printer](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings) | Rendering del foglio di lavoro sulla stampante|
| [to_printer](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#aspose.pydrawing.printing.PrinterSettings-str) | Rendering del foglio di lavoro sulla stampante|
| [to_printer](/cells/python-net/it/aspose.cells.rendering/sheetrender/to_printer/#str-int-int) | Rendering del foglio di lavoro sulla stampante|
| [get_page_size_inch](/cells/python-net/it/aspose.cells.rendering/sheetrender/get_page_size_inch/#int) | Ottieni le dimensioni della pagina in pollici dell'immagine di output.|
| [custom_print](/cells/python-net/it/aspose.cells.rendering/sheetrender/custom_print/#bool-aspose.pydrawing.printing.PrintPageEventArgs) | Il client può controllare l'impostazione della pagina della stampante quando stampa ciascuna pagina utilizzando questa funzione.|
| [dispose](/cells/python-net/it/aspose.cells.rendering/sheetrender/dispose/#) | Rilascia le risorse create e utilizzate per il rendering.|



###  Guarda anche
* modulo [`aspose.cells.rendering`](..)
