---
title: number_category_type fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 670
url: /sv/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type fastighet

Representerar kategoritypen för denna cells nummerformatering.

###  Anmärkningar

När cellens formateringsmönster kombineras med villkorliga formateringsmönster,
då den returnerade typen motsvarar den del som används för det aktuella värdet av denna cell.
Till exempel, om formatmönstret för den här cellen är "#,##0;(#,##0);"-";@",
sedan när cellens värde är numeriskt och inte 0, är den returnerade typen [`NumberCategoryType.NUMBER`](/cells/python-net/sv/aspose.cells/numbercategorytype#NUMBER);
När cellens värde är 0 eller inte numeriskt värde är den returnerade typen [`NumberCategoryType.TEXT`](/cells/python-net/sv/aspose.cells/numbercategorytype#TEXT).
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
