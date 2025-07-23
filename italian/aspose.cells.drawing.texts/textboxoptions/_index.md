---
title: TextBoxOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 80
url: /it/aspose.cells.drawing.texts/textboxoptions/
is_root: false
---
##  TextBoxOptions classe
Rappresenta le opzioni di testo della forma



Il tipo TextBoxOptions espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [shape_text_vertical_alignment](/cells/python-net/it/aspose.cells.drawing.texts/textboxoptions/shape_text_vertical_alignment) | Corrisponde a "Formato forma - Opzioni testo - Casella di testo - Allineamento verticale" in Excel.|
| [resize_to_fit_text](/cells/python-net/it/aspose.cells.drawing.texts/textboxoptions/resize_to_fit_text) | Indica se ridimensionare la forma per adattarla al testo|
| [shape_text_direction](/cells/python-net/it/aspose.cells.drawing.texts/textboxoptions/shape_text_direction) | Ottiene o imposta la direzione di visualizzazione del testo all'interno di un dato corpo di testo.<br/> Corrisponde a "Formato forma - Opzioni testo - Casella di testo - Direzione testo" in Excel|
| [left_margin_pt](/cells/python-net/it/aspose.cells.drawing.texts/textboxoptions/left_margin_pt) | Ottiene e imposta il margine sinistro in unità di punti.|
| [right_margin_pt](/cells/python-net/it/aspose.cells.drawing.texts/textboxoptions/right_margin_pt) | Ottiene e imposta il margine destro in unità di punti.|
| [top_margin_pt](/cells/python-net/it/aspose.cells.drawing.texts/textboxoptions/top_margin_pt) | Ottiene e imposta il margine superiore in unità di punti.|
| [bottom_margin_pt](/cells/python-net/it/aspose.cells.drawing.texts/textboxoptions/bottom_margin_pt) | Restituisce il margine inferiore in unità di punti|
| [allow_text_to_overflow](/cells/python-net/it/aspose.cells.drawing.texts/textboxoptions/allow_text_to_overflow) | Se consentire al testo di fuoriuscire dalla forma.|
| [wrap_text_in_shape](/cells/python-net/it/aspose.cells.drawing.texts/textboxoptions/wrap_text_in_shape) | Specifica l'avvolgimento del testo all'interno di una forma.<br/> Falso: non verrà eseguito alcun avvolgimento nel corpo del testo.<br/>Vero: il ritorno a capo avverrà sul corpo del testo.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
index = workbook.worksheets[0].text_boxes.add(0, 0, 350, 350)
shape = workbook.worksheets[0].text_boxes[index]
shape.text = "This is test."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells.drawing.texts`](..)
