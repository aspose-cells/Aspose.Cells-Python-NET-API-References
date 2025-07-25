---
title: linked_data_sources Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources Eigentum

Gibt die Datenquellen für in Formeln verwendete externe Links an.

###  Bemerkungen

Wie [`Workbook.update_linked_data_source`](/cells/python-net/de/aspose.cells/workbook/update_linked_data_source), hier können Sie angeben
Datenquellen für externe Links, die in zu berechnenden Formeln verwendet werden, insbesondere solche
in der Funktion INDIREKT verwendet. Für die in der Funktion INDIREKT verwendeten externen Links gilt:
Sie werden nicht als Teil der externen Links der Arbeitsmappe übernommen und können nicht aktualisiert werden
bis [`Workbook.update_linked_data_source`](/cells/python-net/de/aspose.cells/workbook/update_linked_data_source).
Die Übereinstimmung dieser Arbeitsmappen mit externen Links wird durch [`Workbook.file_name`](/cells/python-net/de/aspose.cells/workbook#file_name) bestimmt
und [`ExternalLink.data_source`](/cells/python-net/de/aspose.cells/externallink#data_source). Stellen Sie also sicher, dass [`Workbook.file_name`](/cells/python-net/de/aspose.cells/workbook#file_name)
mit dem richtigen Wert angegeben wurde (im Allgemeinen sollte es mit dem entsprechenden identisch sein
[`ExternalLink.data_source`](/cells/python-net/de/aspose.cells/externallink#data_source)) für jede Arbeitsmappe, damit sie wie erwartet verknüpft werden können.
###  Definition:
```python
@property
def linked_data_sources(self):
    ...
@linked_data_sources.setter
def linked_data_sources(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CalculationOptions`](/cells/python-net/de/aspose.cells/calculationoptions)
