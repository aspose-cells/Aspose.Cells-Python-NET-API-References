---
title: region Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 440
url: /de/aspose.cells/workbooksettings/region/
is_root: false
---
##  region Eigentum

Ruft die regionalen Einstellungen für die Arbeitsmappe ab oder legt sie fest.

###  Bemerkungen

1. Von der Komponente Aspose.Cells verwendete regionale Einstellungen für eine aus einer Vorlagendatei geladene Arbeitsmappe:
i). Für eine XLS-Datei sind Felder für regionale Einstellungen definiert und MS Excel speichert beim Speichern der XLS-Datei regionale Einstellungsdaten in der Datei.
Daher verwenden wir die gespeicherte region in der Vorlagendatei für die Arbeitsmappe.
Wenn Sie die in der Datei XLS gespeicherte Nummer region nicht verwenden möchten, setzen Sie sie nach dem Laden der Vorlagendatei bitte auf die erwartete Nummer (z. B. CountryCode.Default) zurück.
Und wir speichern den vom Benutzer angegebenen Wert (mit dieser Methode) auch in der Datei, wenn wir eine XLS-Datei speichern.
ii). Für andere Dateiformate wie XLSX, XLSB usw. ist in der Dateiformatspezifikation kein Feld für regionale Einstellungen definiert.
Daher verwenden wir die regionalen Einstellungen der Anwendungsumgebung für die Arbeitsmappe.
Und der vom Benutzer angegebene Wert (mit dieser Methode) kann für die generierten Dateien mit diesen Dateiformaten nicht beibehalten werden.
2. Für den Anzeigeeffekt in MS Excel:
Die hier angewendeten regionalen Einstellungen können nur zur Laufzeit mit der Komponente Aspose.Cells wirksam werden und nicht beim Anzeigen der generierten Datei mit MS Excel.
Auch für die generierte Datei XLS, in der die angegebenen regionalen Einstellungsdaten gespeichert wurden, gilt beim Anzeigen/Bearbeiten mit MS Excel:
Die von MS Excel zur Formatierung verwendete region entspricht immer den regionalen Standardeinstellungen der Umgebung, in der MS Excel ausgeführt wird.
nicht das in der Datei gespeicherte. Dies ist das Verhalten von MS Excel und kann nicht durch Code geändert werden.
###  Definition:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CountryCode`](/cells/python-net/de/aspose.cells/countrycode)
* Klasse [`WorkbookSettings`](/cells/python-net/de/aspose.cells/workbooksettings)
