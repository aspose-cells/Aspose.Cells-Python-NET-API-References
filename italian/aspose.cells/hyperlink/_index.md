---
title: Hyperlink classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 820
url: /it/aspose.cells/hyperlink/
is_root: false
---
##  Hyperlink classe
Incapsula l'oggetto che rappresenta un collegamento ipertestuale.



Il tipo Hyperlink espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [address](/cells/python-net/it/aspose.cells/hyperlink/address) | Rappresenta l'indirizzo di un collegamento ipertestuale.|
| [text_to_display](/cells/python-net/it/aspose.cells/hyperlink/text_to_display) | Rappresenta il testo da visualizzare per il collegamento ipertestuale specificato. Il valore predefinito è l'indirizzo del collegamento ipertestuale.|
| [area](/cells/python-net/it/aspose.cells/hyperlink/area) | Ottiene l'intervallo del collegamento ipertestuale.|
| [screen_tip](/cells/python-net/it/aspose.cells/hyperlink/screen_tip) | Restituisce o imposta il testo della descrizione comando per il collegamento ipertestuale specificato.|
| [link_type](/cells/python-net/it/aspose.cells/hyperlink/link_type) | Ottiene il tipo di collegamento.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`delete(self)`](/cells/python-net/it/aspose.cells/hyperlink/delete/#) | Elimina questo collegamento ipertestuale|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Workbook object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Adding a hyperlink to a URL at "A1" cell
index = worksheet.hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Getting a Hyperlink by index.
hyperlink = worksheet.hyperlinks[index]
# Setting display text of this hyperlink.
hyperlink.text_to_display = "Aspose"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
