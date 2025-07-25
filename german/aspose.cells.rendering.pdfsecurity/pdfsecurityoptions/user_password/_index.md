---
title: user_password Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 130
url: /de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password/
is_root: false
---
##  user_password Eigentum

Ruft das zum Öffnen des verschlüsselten Dokuments PDF erforderliche Benutzerkennwort ab oder legt es fest.

###  Bemerkungen

Zum Öffnen eines verschlüsselten PDF-Dokuments zur Anzeige ist das Eigentümerkennwort oder das Benutzerkennwort erforderlich.


Das Benutzerkennwort kann null oder eine leere Zeichenfolge sein. In diesem Fall wird beim Öffnen des Dokuments PDF kein Kennwort vom Benutzer verlangt.


Durch Öffnen des Dokuments mit dem richtigen Besitzerkennwort erhalten Sie vollständigen Zugriff auf das Dokument.


 Öffnen des Dokuments mit dem richtigen Benutzerkennwort (oder Öffnen eines Dokuments ohne Benutzerkennwort)
ermöglicht eingeschränkten Zugriff gemäß den angegebenen Berechtigungen.
###  Definition:
```python
@property
def user_password(self):
    ...
@user_password.setter
def user_password(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.rendering.pdfsecurity`](../../)
* Klasse [`PdfSecurityOptions`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
