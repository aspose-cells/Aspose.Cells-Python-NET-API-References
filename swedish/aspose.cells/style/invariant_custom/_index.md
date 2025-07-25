---
title: invariant_custom fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 260
url: /sv/aspose.cells/style/invariant_custom/
is_root: false
---
##  invariant_custom fastighet

Hämtar den kulturoberoende mönstersträngen för talformat.
Om inget talformat har angetts för detta objekt returneras null.
Om talformat är inbyggt returneras mönstersträngen som motsvarar det inbyggda talet.

###  Anmärkningar

För inbyggda talformat är det returnerade mönsterinnehållet fortfarande kulturberoende,
till exempel, för vissa språk returnerar den "m/d/y" och för vissa andra språk returnerar den "d/m/y".
Skillnaden från [`Style.culture_custom`](/cells/python-net/sv/aspose.cells/style#culture_custom) är (det är också vad kulturoberoende betyder):
Formatspecifikationerna och avgränsarna behålls som standard, till exempel kommer '/' alltid att användas som datum- och tidsavgränsare
och "y" kommer alltid att användas som "år"-del oavsett vilket annat specialtecken som används för den specifika språkinställningen.
###  Definition:
```python
@property
def invariant_custom(self):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`Style`](/cells/python-net/sv/aspose.cells/style)
