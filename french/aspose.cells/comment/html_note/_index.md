---
title: html_note propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 150
url: /fr/aspose.cells/comment/html_note/
is_root: false
---
##  html_note propriété

Obtient et définit la chaîne HTML qui contient les données et certains formats dans ce commentaire.

###  Remarques

S'il s'agit d'un commentaire filé, la note ne pourra pas être modifiée, sinon MS Excel ne pourra pas la traiter comme un commentaire filé.

###  Exemple

```python

comment1.html_note = "<Font Style='FONT-FAMILY: Calibri;FONT-SIZE: 11pt;COLOR: #0000ff;TEXT-ALIGN: left;'>This is a <b>test</b>.</Font>"

```
###  Définition:
```python
@property
def html_note(self):
    ...
@html_note.setter
def html_note(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`Comment`](/cells/python-net/fr/aspose.cells/comment)
