---
title: set_embedded_object metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 200
url: /sv/aspose.cells.drawing/oleobject/set_embedded_object/
is_root: false
---
##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label) {#bool-bytes-str-bool-str}
Ställer in inbäddade objektdata.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| link_to_file | bool | Anger om objektet länkar till filen. Om detta är sant ignoreras parametern objectData.|
| object_data | bytes | Den inbäddade objektdatan.|
| source_file_name | str | Filnamnet.|
| display_as_icon | bool | Anger om objektet visas som en ikon.<br/> Om det är sant kommer den ursprungliga bildinformationen att täckas av en ikon.|
| label | str | Ikonens etikett. Fungerar bara när displayAsIcon är satt till sant.|


##  set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon) {#bool-bytes-str-bool-str-bool}
Ställer in inbäddade objektdata.



```python

def set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| link_to_file | bool | Anger om objektet länkar till filen. Om detta är sant ignoreras parametern objectData.|
| object_data | bytes | Den inbäddade objektdatan.|
| source_file_name | str | Filnamnet.|
| display_as_icon | bool | Anger om objektet visas som en ikon.<br/> Om det är sant kommer den ursprungliga bildinformationen att täckas av en ikon.|
| label | str | Ikonens etikett. Fungerar bara när displayAsIcon är satt till sant.|
| update_icon | bool |Anger om ikonen uppdateras automatiskt.|
###  Anmärkningar

Eftersom Aspose kan uppdatera alla inbäddade filikoner, är det bättre att du lägger till korrekt ikon med `update_icon` som falskt.


###  Se även

* modul [`aspose.cells.drawing`](../../)
* klass [`OleObject`](/cells/python-net/sv/aspose.cells.drawing/oleobject)
