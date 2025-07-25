---
title: user_password fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 130
url: /sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password/
is_root: false
---
##  user_password fastighet

Hämtar eller ställer in användarlösenordet som krävs för att öppna det krypterade dokumentet PDF.

###  Anmärkningar

Ägarlösenordet eller användarlösenordet krävs för att öppna ett krypterat PDF-dokument för visning.


Användarlösenordet kan vara null eller en tom sträng. I det här fallet krävs inget lösenord från användaren när dokumentet PDF öppnas.


Att öppna dokumentet med rätt ägarlösenord ger fullständig åtkomst till dokumentet.


 Öppna dokumentet med rätt användarlösenord (eller öppna ett dokument som inte har ett användarlösenord)
tillåter begränsad åtkomst enligt angivna behörigheter.
###  Definition:
```python
@property
def user_password(self):
    ...
@user_password.setter
def user_password(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.rendering.pdfsecurity`](../../)
* klass [`PdfSecurityOptions`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
