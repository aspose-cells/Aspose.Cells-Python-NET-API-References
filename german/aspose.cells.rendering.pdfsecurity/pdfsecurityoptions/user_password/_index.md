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

Um ein verschlüsseltes PDF-Dokument zur Ansicht zu öffnen, ist das Besitzerpasswort oder Benutzerpasswort erforderlich.


Das Benutzerkennwort kann null oder eine leere Zeichenfolge sein. In diesem Fall ist beim Öffnen des Dokuments PDF kein Kennwort vom Benutzer erforderlich.


Das Öffnen des Dokuments mit dem richtigen Besitzerkennwort ermöglicht den vollständigen Zugriff auf das Dokument.


 Öffnen des Dokuments mit dem richtigen Benutzerkennwort (oder Öffnen eines Dokuments ohne Benutzerkennwort)
Ermöglicht eingeschränkten Zugriff gemäß den angegebenen Berechtigungen.
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
