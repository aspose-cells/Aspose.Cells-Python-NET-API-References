---
title: region Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 400
url: /de/aspose.cells/workbooksettings/region/
is_root: false
---
##  region Eigentum

Ruft die regionalen Einstellungen für die Arbeitsmappe ab oder legt diese fest.

###  Bemerkungen

1. Regionale Einstellungen, die von der Komponente Aspose.Cells für eine aus einer Vorlagendatei geladene Arbeitsmappe verwendet werden:
ich). Für eine XLS-Datei sind Felder für regionale Einstellungen definiert und MS Excel speichert regionale Einstellungsdaten in der Datei, wenn die XLS-Datei gespeichert wird.
Daher verwenden wir die gespeicherte region in der Vorlagendatei für die Arbeitsmappe.
Wenn Sie die in der Datei XLS gespeicherte region nicht verwenden möchten, setzen Sie sie nach dem Laden der Vorlagendatei auf die erwartete zurück (z. B. CountryCode.Default).
Und wir speichern den vom Benutzer angegebenen Wert (mit dieser Methode) auch in der Datei, wenn wir eine XLS-Datei speichern.
ii). Für andere Dateiformate wie XLSX, XLSB usw. ist in der Dateiformatspezifikation kein Feld für regionale Einstellungen definiert.
Daher verwenden wir die regionalen Einstellungen der Anwendungsumgebung für die Arbeitsmappe.
Und der vom Benutzer angegebene Wert (durch diese Methode) kann für die generierten Dateien mit diesen Dateiformaten nicht beibehalten werden.
2. Für den Ansichtseffekt in MS Excel:
Die hier angewendeten regionalen Einstellungen können nur zur Laufzeit mit der Komponente Aspose.Cells wirksam werden und nicht beim Anzeigen der generierten Datei mit MS Excel.
Selbst für die generierte Datei XLS, in der die angegebenen regionalen Einstellungsdaten gespeichert wurden, gilt beim Anzeigen/Bearbeiten mit MS Excel:
Die zur Formatierung durch MS Excel verwendete region entspricht immer den regionalen Standardeinstellungen der Umgebung, in der MS Excel ausgeführt wird.
nicht die in der Datei gespeicherte. Es handelt sich um das Verhalten von MS Excel und kann nicht durch Code geändert werden.
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
