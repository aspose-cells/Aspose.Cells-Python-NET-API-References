---
title: check_excel_restriction fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 70
url: /sv/aspose.cells/txtloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction fastighet

Om begränsning av Excel-filen ska kontrolleras när användaren ändrar celler relaterade objekt.
Till exempel tillåter inte Excel inmatning av strängvärden som är längre än 32K.
När du matar in ett värde som är längre än 32K, till exempel Cell.PutValue(string), får du ett undantag om den här egenskapen är sann.
Om den här egenskapen är falsk accepterar vi ditt inmatade strängvärde som cellens värde så att senare
Du kan mata ut hela strängvärdet för andra filformat som CSV.
Om du däremot har angett ett värde som är ogiltigt för Excel-filformatet,
Du bör inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå ett oväntat fel för den genererade Excel-filen.
###  Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`TxtLoadOptions`](/cells/python-net/sv/aspose.cells/txtloadoptions)
