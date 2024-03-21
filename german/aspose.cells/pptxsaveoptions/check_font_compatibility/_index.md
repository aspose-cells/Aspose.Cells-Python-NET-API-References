---
title: check_font_compatibility Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells/pptxsaveoptions/check_font_compatibility/
is_root: false
---
##  check_font_compatibility Eigentum

Gibt an, ob die Schriftartkompatibilität für jedes Zeichen im Text überprüft werden soll.

###  Bemerkungen

Der Standardwert ist wahr.
Durch Deaktivieren dieser Eigenschaft kann die Leistung verbessert werden.
Wenn jedoch die Standardschriftart oder die angegebene Schriftart des Texts/Zeichens nicht zum Rendern verwendet werden kann,
Im generierten PDF können möglicherweise unleserliche Zeichen (z. B. Blöcke) vorkommen.
In einer solchen Situation sollte der Benutzer diese Eigenschaft als wahr beibehalten
Eine alternative Schriftart kann gesucht und stattdessen zum Rendern des Textes verwendet werden.
###  Definition:
```python
@property
def check_font_compatibility(self):
    ...
@check_font_compatibility.setter
def check_font_compatibility(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`PptxSaveOptions`](/cells/python-net/de/aspose.cells/pptxsaveoptions)
