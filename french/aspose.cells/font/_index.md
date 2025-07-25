---
title: Font classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 660
url: /fr/aspose.cells/font/
is_root: false
---
##  Font classe
Encapsule l'objet de police utilisé dans une feuille de calcul.



Le type Font expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [charset](/cells/python-net/fr/aspose.cells/font/charset) | Représente le jeu de caractères.|
| [is_italic](/cells/python-net/fr/aspose.cells/font/is_italic) | Obtient ou définit une valeur indiquant si la police est en italique.|
| [is_bold](/cells/python-net/fr/aspose.cells/font/is_bold) | Obtient ou définit une valeur indiquant si la police est en gras.|
| [caps_type](/cells/python-net/fr/aspose.cells/font/caps_type) | Obtient et définit le type de majuscules du texte.|
| [strike_type](/cells/python-net/fr/aspose.cells/font/strike_type) | Obtient le type de frappe du texte.|
| [is_strikeout](/cells/python-net/fr/aspose.cells/font/is_strikeout) | Obtient ou définit une valeur indiquant si la police est à simple barré.|
| [script_offset](/cells/python-net/fr/aspose.cells/font/script_offset) | Obtient et définit le décalage du script, en unité de pourcentage|
| [is_superscript](/cells/python-net/fr/aspose.cells/font/is_superscript) | Obtient ou définit une valeur indiquant si la police est en super script.|
| [is_subscript](/cells/python-net/fr/aspose.cells/font/is_subscript) | Obtient ou définit une valeur indiquant si la police est en indice.|
| [underline](/cells/python-net/fr/aspose.cells/font/underline) | Obtient ou définit le type de soulignement de la police.|
| [name](/cells/python-net/fr/aspose.cells/font/name) | Obtient ou définit le nom du [`Font`](/cells/python-net/fr/aspose.cells/font).|
| [double_size](/cells/python-net/fr/aspose.cells/font/double_size) | Obtient et définit la double taille de la police.|
| [size](/cells/python-net/fr/aspose.cells/font/size) | Obtient ou définit la taille de la police.|
| [theme_color](/cells/python-net/fr/aspose.cells/font/theme_color) | Obtient et définit la couleur du thème.|
| [color](/cells/python-net/fr/aspose.cells/font/color) | Obtient ou définit la couleur de la police.|
| [argb_color](/cells/python-net/fr/aspose.cells/font/argb_color) | Obtient et définit la couleur avec une valeur ARGB 32 bits.|
| [is_normalize_heights](/cells/python-net/fr/aspose.cells/font/is_normalize_heights) | Indique si la normalisation de la hauteur doit être appliquée au texte exécuté.|
| [scheme_type](/cells/python-net/fr/aspose.cells/font/scheme_type) |Obtient et définit le type de schéma de la police.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`equals(self, font)`](/cells/python-net/fr/aspose.cells/font/equals/#aspose.cells.font) | Vérifie si deux polices sont égales.|



###  Exemple

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Accessing the "A1" cell from the worksheet
cell = worksheet.cells.get("A1")
# Adding some value to the "A1" cell
cell.put_value("Hello Aspose!")
font = cell.get_style().font
# Setting the font name to "Times New Roman"
font.name = "Times New Roman"
# Setting font size to 14
font.size = 14
# setting font color as Red
font.color = Color.red
# Saving the Excel file
workbook.save(r"dest.xls")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`Font`](/cells/python-net/fr/aspose.cells/font)
