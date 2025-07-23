---
title: update_linked_data_source metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 440
url: /sv/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source(self, external_workbooks) {#list}
Om den här arbetsboken innehåller externa länkar till andra datakällor,
Aspose.Cells kommer att försöka hämta den senaste informationen från angivna källor.



```python

def update_linked_data_source(self, external_workbooks):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| external_workbooks | list | Arbetsböcker som kommer att användas för att uppdatera data för externa länkar som refereras till i den här arbetsboken.<br/>Matchningen av dessa arbetsböcker med externa länkar bestäms av [`Workbook.file_name`](/cells/python-net/sv/aspose.cells/workbook#file_name)<br/>och [`ExternalLink.data_source`](/cells/python-net/sv/aspose.cells/externallink#data_source). Så se till att [`Workbook.file_name`](/cells/python-net/sv/aspose.cells/workbook#file_name) har<br/> har angetts med rätt värde för varje arbetsbok så att de kan länkas till motsvarande externa länk.|
###  Anmärkningar

Om motsvarande extern länk inte kan hittas för en arbetsbok, kommer den arbetsboken att ignoreras.
Så när du senare ställer in en formel med en ny extern länk som du avser att göra till den ignorerade arbetsboken
vara länkad till den, kan länken inte utföras förrän du anropar den här metoden igen med de arbetsböckerna.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Workbook`](/cells/python-net/sv/aspose.cells/workbook)
