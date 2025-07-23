---
title: number_category_type fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 700
url: /sv/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type fastighet

Representerar kategoritypen för den här cellens talformatering.

###  Anmärkningar

När cellens formateringsmönster kombineras med villkorsstyrda formateringsmönster,
då motsvarar den returnerade typen den del som används för det aktuella värdet i den här cellen.
Om till exempel formateringsmönstret för den här cellen är "#,##0;(#,##0);"-";@",
när cellens värde är numeriskt och inte 0, är den returnerade typen [`NumberCategoryType.NUMBER`](/cells/python-net/sv/aspose.cells/numbercategorytype#NUMBER);
När cellens värde är 0 eller inte ett numeriskt värde, är den returnerade typen [`NumberCategoryType.TEXT`](/cells/python-net/sv/aspose.cells/numbercategorytype#TEXT).
###  Definition:
```python
@property
def number_category_type(self):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
* klass [`NumberCategoryType`](/cells/python-net/sv/aspose.cells/numbercategorytype)
