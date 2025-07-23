---
title: built_in_document_properties fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 280
url: /sv/aspose.cells/worksheetcollection/built_in_document_properties/
is_root: false
---
##  built_in_document_properties fastighet

Returnerar en [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)-samling som representerar alla inbyggda dokumentegenskaper i kalkylarket.

###  Anmärkningar

En ny egenskap kan inte läggas till i listan över inbyggda dokumentegenskaper. Du kan bara hämta en inbyggd egenskap och ändra dess värde.
Följande är namnlistan för inbyggda egenskaper:

Titel


Ämne


Författare


Nyckelord


Kommentarer


Mall


Senaste författare


Revisionsnummer


Applikationsnamn


Senaste utskriftsdatum


Skapandedatum


Sista spartid


Total redigeringstid


Antal sidor


Antal ord


Antal tecken


Säkerhet


Kategori


Formatera


Chef


Företag


Antal byte


Antal rader


Antal stycken


Antal bilder


Antal anteckningar


Antal dolda bilder


Antal multimediaklipp

###  Exempel

```python
from aspose.cells import Workbook

workbook = Workbook()
doc = workbook.worksheets.built_in_document_properties.get("Author")
doc.value = "John Smith"

```
###  Definition:
```python
@property
def built_in_document_properties(self):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`BuiltInDocumentPropertyCollection`](/cells/python-net/sv/aspose.cells.properties/builtindocumentpropertycollection)
* klass [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)
* klass [`WorksheetCollection`](/cells/python-net/sv/aspose.cells/worksheetcollection)
