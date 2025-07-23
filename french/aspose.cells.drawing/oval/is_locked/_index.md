---
title: is_locked propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 620
url: /fr/aspose.cells.drawing/oval/is_locked/
is_root: false
---
##  is_locked propriété

 Vrai signifie que l'objet ne peut pas être modifié lorsque la feuille est protégée.
Notez que cette valeur n'a de sens que si la feuille de calcul ou les objets de la feuille de calcul sont protégés.

###  Exemple

```python

# Sets the specified shape to unlocked state
if shape.worksheet.is_protected and shape.is_locked:
    shape.is_locked = False
# Sets the specified shape to a locked state
if shape.worksheet.is_protected and notshape.is_locked:
    shape.is_locked = True

```
###  Définition:
```python
@property
def is_locked(self):
    ...
@is_locked.setter
def is_locked(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`Oval`](/cells/python-net/fr/aspose.cells.drawing/oval)
