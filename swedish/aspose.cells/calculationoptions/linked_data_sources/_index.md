---
title: linked_data_sources fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 60
url: /sv/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources fastighet

Anger datakällorna för externa länkar som används i formler.

###  Anmärkningar

Liksom [`Workbook.update_linked_data_source`](/cells/python-net/sv/aspose.cells/workbook/update_linked_data_source), här kan du ange
datakällor för externa länkar som används i formler som ska beräknas, särskilt de
används i INDIRECT-funktionen. För de externa länkar som används i INDIRECT-funktionen,
de tas inte som en del av arbetsbokens externa länkar och kan inte uppdateras
av [`Workbook.update_linked_data_source`](/cells/python-net/sv/aspose.cells/workbook/update_linked_data_source).
Matchningen av dessa arbetsböcker med externa länkar bestäms av [`Workbook.file_name`](/cells/python-net/sv/aspose.cells/workbook#file_name)
och [`ExternalLink.data_source`](/cells/python-net/sv/aspose.cells/externallink#data_source). Så se till att [`Workbook.file_name`](/cells/python-net/sv/aspose.cells/workbook#file_name) har
har angetts med rätt värde (i allmänhet bör det vara samma med motsvarande
[`ExternalLink.data_source`](/cells/python-net/sv/aspose.cells/externallink#data_source)) för varje arbetsbok så att de kan länkas som förväntat.
###  Definition:
```python
@property
def linked_data_sources(self):
    ...
@linked_data_sources.setter
def linked_data_sources(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`CalculationOptions`](/cells/python-net/sv/aspose.cells/calculationoptions)
