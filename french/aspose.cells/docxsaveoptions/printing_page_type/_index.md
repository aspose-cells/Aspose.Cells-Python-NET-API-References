---
title: printing_page_type propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 220
url: /fr/aspose.cells/docxsaveoptions/printing_page_type/
is_root: false
---
##  printing_page_type propriété

Indique quelles pages ne seront pas imprimées.

###  Remarques

Si le contenu de la feuille est clairsemé, certaines pages seront totalement vierges dans le fichier PDF de sortie.
Si vous ne voulez pas ces pages vierges, vous pouvez utiliser cette option pour les omettre.

###  Exemple

Le code suivant omet les pages vierges ou les pages qui contiennent uniquement du contenu de style comme l'arrière-plan des cellules et les bordures.

```python
from aspose.cells import PdfSaveOptions, PrintingPageType, Workbook

wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# ignore blank pages
pdfSaveOptions.printing_page_type = PrintingPageType.IGNORE_BLANK
wb.save("output_ignore_blank_page.pdf", pdfSaveOptions)
# ignore blank pages and pages which only contains some style content like cell background
pdfSaveOptions.printing_page_type = PrintingPageType.IGNORE_STYLE
wb.save("output_ignore_blank_and_style_page.pdf", pdfSaveOptions)

```
###  Définition:
```python
@property
def printing_page_type(self):
    ...
@printing_page_type.setter
def printing_page_type(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`DocxSaveOptions`](/cells/python-net/fr/aspose.cells/docxsaveoptions)
* classe [`PrintingPageType`](/cells/python-net/fr/aspose.cells/printingpagetype)
