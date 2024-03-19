---
title: Range classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1290
url: /it/aspose.cells/range/
is_root: false
---
##  Range classe
Incapsula l'oggetto che rappresenta un intervallo di celle all'interno di un foglio di calcolo.



Il tipo Range espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [current_region](/cells/python-net/it/aspose.cells/range/current_region) |Restituisce un oggetto Range che rappresenta la regione corrente.<br/> La regione corrente è un intervallo delimitato da qualsiasi combinazione di righe e colonne vuote.|
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
| [entire_column](/cells/python-net/it/aspose.cells/range/entire_column) | Ottiene un oggetto Range che rappresenta l'intera colonna (o le colonne) che contiene l'intervallo specificato.|
| [entire_row](/cells/python-net/it/aspose.cells/range/entire_row) |Ottiene un oggetto Range che rappresenta l'intera riga (o righe) che contiene l'intervallo specificato.|
| [worksheet](/cells/python-net/it/aspose.cells/range/worksheet) | Ottiene l'oggetto [`Range.worksheet`](/cells/python-net/it/aspose.cells/range#worksheet) che contiene questo intervallo.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [auto_fill](/cells/python-net/it/aspose.cells/range/auto_fill/#aspose.cells.Range) | Riempie automaticamente l'intervallo target.|
| [auto_fill](/cells/python-net/it/aspose.cells/range/auto_fill/#aspose.cells.Range-aspose.cells.AutoFillType) | Riempie automaticamente l'intervallo target.|
| [set_style](/cells/python-net/it/aspose.cells/range/set_style/#aspose.cells.Style-bool) | Applicare lo stile della cella.|
| [set_style](/cells/python-net/it/aspose.cells/range/set_style/#aspose.cells.Style) | Imposta lo stile dell'intervallo.|
| [set_outline_borders](/cells/python-net/it/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.cells.CellsColor) | Imposta i bordi del contorno attorno a un intervallo di celle con lo stesso stile e colore del bordo.|
| [set_outline_borders](/cells/python-net/it/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.pydrawing.Color) | Imposta i bordi del contorno attorno a un intervallo di celle con lo stesso stile e colore del bordo.|
| [set_outline_borders](/cells/python-net/it/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.Color[]) | Definisce i bordi della linea attorno a un intervallo di celle.|
| [set_outline_border](/cells/python-net/it/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Imposta il bordo del contorno attorno a un intervallo di celle.|
| [set_outline_border](/cells/python-net/it/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Imposta il bordo del contorno attorno a un intervallo di celle.|
| [copy](/cells/python-net/it/aspose.cells/range/copy/#aspose.cells.Range-aspose.cells.PasteOptions) | Copia dell'intervallo con le opzioni speciali Incolla.|
| [copy](/cells/python-net/it/aspose.cells/range/copy/#aspose.cells.Range) | Copia dati (incluse formule), formattazione, oggetti di disegno, ecc. da un intervallo di origine.|
| [add_hyperlink](/cells/python-net/it/aspose.cells/range/add_hyperlink/#str-str-str) | Aggiunge un collegamento ipertestuale a una cella specifica o a un intervallo di celle.|
| [get_enumerator](/cells/python-net/it/aspose.cells/range/get_enumerator/#) | Ottiene l'enumeratore per le celle in questo Range.|
| [is_intersect](/cells/python-net/it/aspose.cells/range/is_intersect/#aspose.cells.Range) | Indica se l'intervallo è intersecato.|
| [intersect](/cells/python-net/it/aspose.cells/range/intersect/#aspose.cells.Range) | Restituisce un oggetto [`Range`](/cells/python-net/it/aspose.cells/range) che rappresenta l'intersezione rettangolare di due intervalli.|
| [union_rang](/cells/python-net/it/aspose.cells/range/union_rang/#aspose.cells.Range) | Restituisce il risultato dell'unione di due intervalli.|
| [union](/cells/python-net/it/aspose.cells/range/union/#aspose.cells.Range) | Restituisce l'unione di due intervalli.|
| [is_blank](/cells/python-net/it/aspose.cells/range/is_blank/#) | Indica se l'intervallo contiene valori.|
| [merge](/cells/python-net/it/aspose.cells/range/merge/#) | Combina un intervallo di celle in un'unica cella.|
| [un_merge](/cells/python-net/it/aspose.cells/range/un_merge/#) |Separa le celle unite di questo intervallo.|
| [put_value](/cells/python-net/it/aspose.cells/range/put_value/#str-bool-bool) | Inserisce un valore nell'intervallo, se appropriato il valore verrà convertito in un altro tipo di dati e il formato del numero della cella verrà ripristinato.|
| [apply_style](/cells/python-net/it/aspose.cells/range/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Applica i formati per un'intera gamma.|
| [set_inside_borders](/cells/python-net/it/aspose.cells/range/set_inside_borders/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Impostato all'interno dei confini dell'intervallo.|
| [move_to](/cells/python-net/it/aspose.cells/range/move_to/#int-int) | Sposta l'intervallo corrente nell'intervallo di destinazione.|
| [copy_data](/cells/python-net/it/aspose.cells/range/copy_data/#aspose.cells.Range) | Copia i dati della cella (comprese le formule) da un intervallo di origine.|
| [copy_value](/cells/python-net/it/aspose.cells/range/copy_value/#aspose.cells.Range) | Copia il valore della cella da un intervallo di origine.|
| [copy_style](/cells/python-net/it/aspose.cells/range/copy_style/#aspose.cells.Range) | Copia le impostazioni di stile da un intervallo di origine.|
| [get_cell_or_null](/cells/python-net/it/aspose.cells/range/get_cell_or_null/#int-int) | Ottiene l'oggetto [`Cell`](/cells/python-net/it/aspose.cells/cell) o null in questo intervallo.|
| [get_offset](/cells/python-net/it/aspose.cells/range/get_offset/#int-int) | Ottiene l'intervallo [`Range`](/cells/python-net/it/aspose.cells/range) per offset.|



###  Osservazioni

La classe Range denota una regione del foglio di calcolo Excel.
Con questo, puoi formattare e impostare il valore dell'intervallo.
E puoi semplicemente copiare anche l'intervallo di Excel.

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
