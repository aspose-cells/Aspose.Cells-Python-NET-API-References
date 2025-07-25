---
title: Range classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1180
url: /it/aspose.cells/range/
is_root: false
---
##  Range classe
Incapsula l'oggetto che rappresenta un intervallo di celle all'interno di un foglio di calcolo.



Il tipo Range espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [current_region](/cells/python-net/it/aspose.cells/range/current_region) | Restituisce un oggetto Range che rappresenta la regione corrente.<br/> L'area corrente è un intervallo delimitato da qualsiasi combinazione di righe e colonne vuote.|
| [hyperlinks](/cells/python-net/it/aspose.cells/range/hyperlinks) | Ottiene tutti i collegamenti ipertestuali nell'intervallo.|
| [row_count](/cells/python-net/it/aspose.cells/range/row_count) | Ottiene il conteggio delle righe nell'intervallo.|
| [column_count](/cells/python-net/it/aspose.cells/range/column_count) | Ottiene il conteggio delle colonne nell'intervallo.|
| [name](/cells/python-net/it/aspose.cells/range/name) | Ottiene o imposta il nome dell'intervallo.|
| [refers_to](/cells/python-net/it/aspose.cells/range/refers_to) | Ottiene l'intervallo a cui si riferisce.|
| [address](/cells/python-net/it/aspose.cells/range/address) | Ottiene l'indirizzo dell'intervallo.|
| [left](/cells/python-net/it/aspose.cells/range/left) | Ottiene la distanza, in punti, dal bordo sinistro della colonna A al bordo sinistro dell'intervallo.|
| [top](/cells/python-net/it/aspose.cells/range/top) | Ottiene la distanza, in punti, dal bordo superiore della riga 1 al bordo superiore dell'intervallo.|
| [width](/cells/python-net/it/aspose.cells/range/width) | Ottiene la larghezza di un intervallo in punti.|
| [height](/cells/python-net/it/aspose.cells/range/height) | Ottiene la larghezza di un intervallo in punti.|
| [first_row](/cells/python-net/it/aspose.cells/range/first_row) | Ottiene l'indice della prima riga dell'intervallo.|
| [first_column](/cells/python-net/it/aspose.cells/range/first_column) | Ottiene l'indice della prima colonna dell'intervallo.|
| [value](/cells/python-net/it/aspose.cells/range/value) | Ottiene e imposta il valore dell'intervallo.|
| [column_width](/cells/python-net/it/aspose.cells/range/column_width) | Imposta o ottiene la larghezza della colonna di questo intervallo|
| [row_height](/cells/python-net/it/aspose.cells/range/row_height) | Imposta o ottiene l'altezza delle righe in questo intervallo|
| [entire_column](/cells/python-net/it/aspose.cells/range/entire_column) |Ottiene un oggetto Range che rappresenta l'intera colonna (o le colonne) che contiene l'intervallo specificato.|
| [entire_row](/cells/python-net/it/aspose.cells/range/entire_row) | Ottiene un oggetto Range che rappresenta l'intera riga (o le righe) che contengono l'intervallo specificato.|
| [worksheet](/cells/python-net/it/aspose.cells/range/worksheet) | Ottiene l'oggetto [`Range.worksheet`](/cells/python-net/it/aspose.cells/range#worksheet) che contiene questo intervallo.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`auto_fill(self, target)`](/cells/python-net/it/aspose.cells/range/auto_fill/#aspose.cells.range) | Riempi automaticamente l'intervallo di destinazione.|
| [`auto_fill(self, target, auto_fill_type)`](/cells/python-net/it/aspose.cells/range/auto_fill/#aspose.cells.range-aspose.cells.autofilltype) | Riempi automaticamente l'intervallo di destinazione.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/it/aspose.cells/range/set_style/#aspose.cells.style-bool) | Applica lo stile della cella.|
| [`set_style(self, style)`](/cells/python-net/it/aspose.cells/range/set_style/#aspose.cells.style) | Imposta lo stile dell'intervallo.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/it/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.cells.cellscolor) | Imposta i bordi del contorno attorno a un intervallo di celle con lo stesso stile e colore.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/it/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Imposta i bordi del contorno attorno a un intervallo di celle con lo stesso stile e colore.|
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/it/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.color[]) | Imposta i bordi delle linee attorno a un intervallo di celle.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/it/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Imposta il bordo attorno a un intervallo di celle.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/it/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Imposta il bordo attorno a un intervallo di celle.|
| [`copy(self, range, options)`](/cells/python-net/it/aspose.cells/range/copy/#aspose.cells.range-aspose.cells.pasteoptions) | Copia dell'intervallo con le opzioni Incolla speciale.|
| [`copy(self, range)`](/cells/python-net/it/aspose.cells/range/copy/#aspose.cells.range) | Copia dati (incluse formule), formattazione, oggetti di disegno ecc. da un intervallo di origine.|
| [`add_hyperlink(self, address, text_to_display, screen_tip)`](/cells/python-net/it/aspose.cells/range/add_hyperlink/#str-str-str) | Aggiunge un collegamento ipertestuale a una cella specificata o a un intervallo di celle.|
| [`is_intersect(self, range)`](/cells/python-net/it/aspose.cells/range/is_intersect/#aspose.cells.range) | Indica se l'intervallo è intersecato.|
| [`intersect(self, range)`](/cells/python-net/it/aspose.cells/range/intersect/#aspose.cells.range) | Restituisce un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) che rappresenta l'intersezione rettangolare di due intervalli.|
| [`union_rang(self, range)`](/cells/python-net/it/aspose.cells/range/union_rang/#aspose.cells.range) | Restituisce il risultato dell'unione di due intervalli.|
| [`union_ranges(self, ranges)`](/cells/python-net/it/aspose.cells/range/union_ranges/#list) | Restituisce il risultato dell'unione di due intervalli.|
| [`union(self, range)`](/cells/python-net/it/aspose.cells/range/union/#aspose.cells.range) | Restituisce l'unione di due intervalli.|
| [`is_blank(self)`](/cells/python-net/it/aspose.cells/range/is_blank/#) | Indica se l'intervallo contiene valori.|
| [`merge(self)`](/cells/python-net/it/aspose.cells/range/merge/#) |Combina un intervallo di celle in un'unica cella.|
| [`un_merge(self)`](/cells/python-net/it/aspose.cells/range/un_merge/#) | Annulla l'unione delle celle unite di questo intervallo.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/it/aspose.cells/range/put_value/#str-bool-bool) | Inserisce un valore nell'intervallo; se appropriato, il valore verrà convertito in un altro tipo di dati e il formato numerico della cella verrà reimpostato.|
| [`apply_style(self, style, flag)`](/cells/python-net/it/aspose.cells/range/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Applica formati per un intervallo intero.|
| [`set_inside_borders(self, border_edge, line_style, border_color)`](/cells/python-net/it/aspose.cells/range/set_inside_borders/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Impostato all'interno dei confini dell'intervallo.|
| [`move_to(self, dest_row, dest_column)`](/cells/python-net/it/aspose.cells/range/move_to/#int-int) | Sposta l'intervallo corrente nell'intervallo di destinazione.|
| [`copy_data(self, range)`](/cells/python-net/it/aspose.cells/range/copy_data/#aspose.cells.range) | Copia i dati delle celle (incluse le formule) da un intervallo di origine.|
| [`copy_value(self, range)`](/cells/python-net/it/aspose.cells/range/copy_value/#aspose.cells.range) | Copia il valore della cella da un intervallo di origine.|
| [`copy_style(self, range)`](/cells/python-net/it/aspose.cells/range/copy_style/#aspose.cells.range) | Copia le impostazioni di stile da un intervallo sorgente.|
| [`transpose(self)`](/cells/python-net/it/aspose.cells/range/transpose/#) | Trasporre (ruotare) i dati dalle righe alle colonne o viceversa.|
| [`get(self, row_offset, column_offset)`](/cells/python-net/it/aspose.cells/range/get/#int-int) | Aggiungi API for Python tramite .Net. poiché questo [int, int] non è supportato|
| [`get_cell_or_null(self, row_offset, column_offset)`](/cells/python-net/it/aspose.cells/range/get_cell_or_null/#int-int) | Ottiene [`Cell`](/cells/python-net/it/aspose.cells/cell) oggetto o null in questo intervallo.|
| [`get_offset(self, row_offset, column_offset)`](/cells/python-net/it/aspose.cells/range/get_offset/#int-int) | Ottiene l'intervallo [`Range`](/cells/python-net/it/aspose.cells/range) tramite offset.|
| [`to_image(self, options)`](/cells/python-net/it/aspose.cells/range/to_image/#aspose.cells.rendering.imageorprintoptions) | Converte l'intervallo in immagine.|
| [`to_json(self, options)`](/cells/python-net/it/aspose.cells/range/to_json/#aspose.cells.jsonsaveoptions) | Convertire l'intervallo nel valore JSON.|
| [`to_html(self, save_options)`](/cells/python-net/it/aspose.cells/range/to_html/#aspose.cells.htmlsaveoptions) | Converti l'intervallo in html.|
| [`clear(self)`](/cells/python-net/it/aspose.cells/range/clear/#) | Cancella questo intervallo.|
| [`clear_contents(self)`](/cells/python-net/it/aspose.cells/range/clear_contents/#) | Cancella il contenuto di questo intervallo.|
| [`clear_formats(self)`](/cells/python-net/it/aspose.cells/range/clear_formats/#) | Cancella i formati di questo intervallo.|
| [`clear_comments(self)`](/cells/python-net/it/aspose.cells/range/clear_comments/#) | Cancella i commenti di questo intervallo.|
| [`clear_hyperlinks(self, clear_format)`](/cells/python-net/it/aspose.cells/range/clear_hyperlinks/#bool) | Rimuove solo i collegamenti ipertestuali.|



###  Osservazioni

La classe Range indica una parte del foglio di calcolo Excel.
Con questo è possibile formattare e impostare il valore dell'intervallo.
Puoi anche semplicemente copiare un intervallo di dati di Excel.

###  Esempio

L'esempio seguente mostra come creare un intervallo e impostare il valore dell'intervallo di Excel.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
* classe [`Range`](/cells/python-net/it/aspose.cells/range)
