---
title: multi_thread_reading fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1220
url: /sv/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading fastighet

Hämtar eller anger om cellernas datamodell ska stödja flertrådsläsning.
Standardvärdet för den här egenskapen är falskt.

###  Anmärkningar

Om det finns flera trådar att läsa Row/Cell-objekt i den här samlingen samtidigt,
Den här egenskapen bör sättas till sant, annars kan oväntade resultat uppstå.
Stöd för läsning av flera trådar kan försämra prestandan för åtkomst till Row/Cell-objekt från den här samlingen.
Observera att vissa funktioner inte stöder flertrådsläsning,
såsom formatering av värden (med [`Cell.string_value`](/cells/python-net/sv/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/sv/aspose.cells/cell#display_string_value), etc.).
Så även om den här egenskapen är inställd på sant kan dessa API:er fortfarande ge oväntade resultat för läsning av flera trådar.
###  Definition:
```python
@property
def multi_thread_reading(self):
    ...
@multi_thread_reading.setter
def multi_thread_reading(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
