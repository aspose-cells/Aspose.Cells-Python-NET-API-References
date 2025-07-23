---
title: built_in_document_properties Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 470
url: /de/aspose.cells/workbook/built_in_document_properties/
is_root: false
---
##  built_in_document_properties Eigentum

Gibt eine [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)-Sammlung zurück, die alle integrierten Dokumenteigenschaften der Tabelle darstellt.

###  Bemerkungen

Der Liste der integrierten Dokumenteigenschaften kann keine neue Eigenschaft hinzugefügt werden. Sie können lediglich eine integrierte Eigenschaft abrufen und ihren Wert ändern.
Nachfolgend sehen Sie die Namensliste der integrierten Eigenschaften:

Titel


Thema


Autor


Schlüsselwörter


Kommentare


Vorlage


Letzter Autor


Revisionsnummer


Anwendungsname


Letztes Druckdatum


Erstellungsdatum


Letzte Speicherzeit


Gesamtbearbeitungszeit


Seitenanzahl


Anzahl der Wörter


Anzahl der Zeichen


Sicherheit


Kategorie


Format


Manager


Unternehmen


Anzahl der Bytes


Anzahl der Zeilen


Anzahl der Absätze


Anzahl der Folien


Anzahl der Notizen


Anzahl der ausgeblendeten Folien


Anzahl der Multimedia-Clips

###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
doc = workbook.built_in_document_properties.get("Author")
doc.value = "John Smith"

```
###  Definition:
```python
@property
def built_in_document_properties(self):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`BuiltInDocumentPropertyCollection`](/cells/python-net/de/aspose.cells.properties/builtindocumentpropertycollection)
* Klasse [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)
* Klasse [`Workbook`](/cells/python-net/de/aspose.cells/workbook)
