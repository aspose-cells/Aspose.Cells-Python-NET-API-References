---
title: default_style propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 580
url: /fr/aspose.cells/workbook/default_style/
is_root: false
---
##  default_style propriété

Obtient ou définit l'objet [`Style`](/cells/python-net/fr/aspose.cells/style) par défaut du classeur.

###  Remarques

La propriété DefaultStyle est utile pour implémenter un style pour l'ensemble du classeur.

###  Exemple

Le code suivant crée et instancie un nouveau classeur et lui définit une valeur par défaut [`Style`](/cells/python-net/fr/aspose.cells/style).

```python
from aspose.cells import Workbook

workbook = Workbook()
defaultStyle = workbook.default_style
defaultStyle.font.name = "Tahoma"
workbook.default_style = defaultStyle

```
###  Définition:
```python
@property
def default_style(self):
    ...
@default_style.setter
def default_style(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`Style`](/cells/python-net/fr/aspose.cells/style)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
