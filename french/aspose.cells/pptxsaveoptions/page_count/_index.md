---
title: page_count propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 220
url: /fr/aspose.cells/pptxsaveoptions/page_count/
is_root: false
---
##  page_count propriété

Obtient ou définit le nombre de pages à enregistrer.

###  Remarques

La valeur par défaut est System.Int32.MaxValue, ce qui signifie que toutes les pages seront rendues.

###  Exemple

L'exemple suivant montre comment restituer une plage de pages (3 et 4) d'un fichier Excel Microsoft vers PDF.

```python
from aspose.cells import PdfSaveOptions, Workbook

# Open an Excel file
wb = Workbook("Book1.xlsx")
options = PdfSaveOptions()
# Print only Page 3 and Page 4 in the output PDF
# Starting page index (0-based index)
options.page_index = 3
# Number of pages to be printed
options.page_count = 2
# Save the PDF file
wb.save("output.pdf", options)

```
###  Définition:
```python
@property
def page_count(self):
    ...
@page_count.setter
def page_count(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`PptxSaveOptions`](/cells/python-net/fr/aspose.cells/pptxsaveoptions)
