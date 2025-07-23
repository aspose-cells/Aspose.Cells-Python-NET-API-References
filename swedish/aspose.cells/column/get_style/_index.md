---
title: get_style metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/column/get_style/
is_root: false
---
##  get_style(self) {#}
Hämtar stilen för den här kolumnen.



```python

def get_style(self):
    ...
```


###  Anmärkningar

Att ändra det returnerade stilobjektet direkt har ingen effekt för den här kolumnen eller några celler i den här kolumnen.
Du måste ringa [`Column.apply_style`](/cells/python-net/sv/aspose.cells/column/apply_style) eller [`Column.set_style`](/cells/python-net/sv/aspose.cells/column/set_style)-metoden.
för att tillämpa ändringen på den här kolumnen.

Kolumnens stil är den stil som ärvs av cellerna i den här kolumnen (de celler som inte har några anpassade stilinställningar,
såsom befintliga celler som inte explicit har fått sin stil, eller de som inte har instansierats)


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Column`](/cells/python-net/sv/aspose.cells/column)
