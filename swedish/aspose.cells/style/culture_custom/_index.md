---
title: culture_custom fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 170
url: /sv/aspose.cells/style/culture_custom/
is_root: false
---
##  culture_custom fastighet

Hämtar och ställer in den kulturberoende mönstersträngen för talformat.
Om inget talformat har angetts för detta objekt returneras null.
Om talformat är inbyggt returneras mönstersträngen som motsvarar det inbyggda talet.

###  Anmärkningar

För inbyggt nummerformat gäller både mönsterinnehållet (t.ex. ett inbyggt datumformat är "m/d/y" för vissa språkinställningar,
men för vissa andra språkinställningar blir det "d/m/y") och formatspecifikatorn (t.ex.
vissa språkinställningar använder andra tecken än 'y' för att representera årsdelen i datumformateringen)
är kulturberoende;
För användarspecificerade anpassade format ändras endast formatspecifikationer enligt kulturen,
Andra delar av formateringsmönstret kommer inte att ändras.
###  Definition:
```python
@property
def culture_custom(self):
    ...
@culture_custom.setter
def culture_custom(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`Style`](/cells/python-net/sv/aspose.cells/style)
