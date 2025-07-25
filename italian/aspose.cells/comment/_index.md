---
title: Comment classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 260
url: /it/aspose.cells/comment/
is_root: false
---
##  Comment classe
Incapsula l'oggetto che rappresenta un commento di cella.



Il tipo Comment espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [author](/cells/python-net/it/aspose.cells/comment/author) | Ottiene e imposta il nome dell'autore del commento originale|
| [comment_shape](/cells/python-net/it/aspose.cells/comment/comment_shape) | Ottieni un oggetto Shape che rappresenta la forma associata al commento specificato.|
| [row](/cells/python-net/it/aspose.cells/comment/row) | Ottiene l'indice di riga del commento.|
| [column](/cells/python-net/it/aspose.cells/comment/column) | Ottiene l'indice della colonna del commento.|
| [is_threaded_comment](/cells/python-net/it/aspose.cells/comment/is_threaded_comment) | Indica se questo commento è un commento con thread.|
| [threaded_comments](/cells/python-net/it/aspose.cells/comment/threaded_comments) | Ottiene l'elenco dei commenti thread;|
| [note](/cells/python-net/it/aspose.cells/comment/note) | Rappresenta il contenuto del commento.|
| [html_note](/cells/python-net/it/aspose.cells/comment/html_note) | Ottiene e imposta la stringa HTML che contiene dati e alcuni formati in questo commento.|
| [font](/cells/python-net/it/aspose.cells/comment/font) | Ottiene il font del commento.|
| [is_visible](/cells/python-net/it/aspose.cells/comment/is_visible) | Indica se il commento è visibile o meno.|
| [text_orientation_type](/cells/python-net/it/aspose.cells/comment/text_orientation_type) | Ottiene e imposta il tipo di orientamento del testo del commento.|
| [text_horizontal_alignment](/cells/python-net/it/aspose.cells/comment/text_horizontal_alignment) | Ottiene e imposta il tipo di allineamento orizzontale del testo del commento.|
| [text_vertical_alignment](/cells/python-net/it/aspose.cells/comment/text_vertical_alignment) | Ottiene e imposta il tipo di allineamento verticale del testo del commento.|
| [auto_size](/cells/python-net/it/aspose.cells/comment/auto_size) | Indica se la dimensione del commento viene regolata automaticamente in base al suo contenuto.<br/>Nota: in alcuni casi particolari (ad esempio in ambiente Mac), questa impostazione potrebbe non avere effetto. Se questa impostazione non ha effetto, sostituirla con FitToTextSize().|
| [height_cm](/cells/python-net/it/aspose.cells/comment/height_cm) | Rappresenta l'altezza del commento, in centimetri.|
| [width_cm](/cells/python-net/it/aspose.cells/comment/width_cm) | Rappresenta la larghezza del commento, in centimetri.|
| [width](/cells/python-net/it/aspose.cells/comment/width) | Rappresenta la larghezza del commento, in pixel.|
| [height](/cells/python-net/it/aspose.cells/comment/height) | Rappresenta l'altezza del commento, in pixel.|
| [width_inch](/cells/python-net/it/aspose.cells/comment/width_inch) | Rappresenta la larghezza del commento, in pollici.|
| [height_inch](/cells/python-net/it/aspose.cells/comment/height_inch) | Rappresenta l'altezza del commento, in pollici.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/it/aspose.cells/comment/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Formattare alcuni caratteri con l'impostazione del font.|
| [`characters(self, start_index, length)`](/cells/python-net/it/aspose.cells/comment/characters/#int-int) | Restituisce un oggetto Characters che rappresenta un intervallo di caratteri all'interno del testo del commento.|
| [`get_characters(self)`](/cells/python-net/it/aspose.cells/comment/get_characters/#) | Restituisce tutti gli oggetti Characters<br/> che rappresenta un intervallo di caratteri all'interno del testo del commento.|
| [`get_rich_formattings(self)`](/cells/python-net/it/aspose.cells/comment/get_rich_formattings/#) | Restituisce tutti gli oggetti Characters<br/> che rappresenta un intervallo di caratteri all'interno del testo del commento.|



###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment2 = comments.get("B2")
comment2.note = "Second note."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
