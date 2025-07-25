---
title: Style classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1350
url: /fr/aspose.cells/style/
is_root: false
---
##  Style classe
Représente le style d'affichage du document Excel, tel que la police, la couleur, l'alignement, la bordure, etc.
L'objet Style contient tous les attributs de style (police, format numérique, alignement, etc.) en tant que propriétés.



Le type Style expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/style/__init__/#) | Initialise une nouvelle instance de la classe [`Style`](/cells/python-net/fr/aspose.cells/style).|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [background_theme_color](/cells/python-net/fr/aspose.cells/style/background_theme_color) | Obtient et définit la couleur du thème d'arrière-plan.|
| [foreground_theme_color](/cells/python-net/fr/aspose.cells/style/foreground_theme_color) | Obtient et définit la couleur du thème de premier plan.|
| [name](/cells/python-net/fr/aspose.cells/style/name) | Obtient ou définit le nom du style.|
| [pattern](/cells/python-net/fr/aspose.cells/style/pattern) | Obtient ou définit le type de motif d'arrière-plan de la cellule.|
| [borders](/cells/python-net/fr/aspose.cells/style/borders) | Obtient le [`BorderCollection`](/cells/python-net/fr/aspose.cells/bordercollection) du style.|
| [background_color](/cells/python-net/fr/aspose.cells/style/background_color) | Obtient ou définit la couleur d'arrière-plan d'un style.|
| [background_argb_color](/cells/python-net/fr/aspose.cells/style/background_argb_color) | Obtient et définit la couleur d'arrière-plan avec une valeur ARGB 32 bits.|
| [foreground_color](/cells/python-net/fr/aspose.cells/style/foreground_color) | Obtient ou définit la couleur de premier plan d'un style.|
| [foreground_argb_color](/cells/python-net/fr/aspose.cells/style/foreground_argb_color) | Obtient et définit la couleur de premier plan avec une valeur ARGB 32 bits.|
| [has_borders](/cells/python-net/fr/aspose.cells/style/has_borders) | Vérifie si des bordures ont été définies pour le style.|
| [parent_style](/cells/python-net/fr/aspose.cells/style/parent_style) | Obtient le style parent de ce style.|
| [is_number_format_applied](/cells/python-net/fr/aspose.cells/style/is_number_format_applied) | Indiquez si le formatage des nombres doit être appliqué.|
| [is_font_applied](/cells/python-net/fr/aspose.cells/style/is_font_applied) |Indiquez si la mise en forme de la police doit être appliquée.|
| [is_alignment_applied](/cells/python-net/fr/aspose.cells/style/is_alignment_applied) | Indiquez si la mise en forme d'alignement doit être appliquée.|
| [is_border_applied](/cells/python-net/fr/aspose.cells/style/is_border_applied) | Indiquez si la mise en forme de la bordure doit être appliquée.|
| [is_fill_applied](/cells/python-net/fr/aspose.cells/style/is_fill_applied) | Indiquez si la mise en forme de remplissage doit être appliquée.|
| [is_protection_applied](/cells/python-net/fr/aspose.cells/style/is_protection_applied) | Indiquez si le formatage de protection doit être appliqué.|
| [indent_level](/cells/python-net/fr/aspose.cells/style/indent_level) | Représente le niveau de retrait de la cellule ou de la plage. Ne peut être qu'un entier compris entre 0 et 250.|
| [font](/cells/python-net/fr/aspose.cells/style/font) | Obtient un objet [`Style.font`](/cells/python-net/fr/aspose.cells/style#font).|
| [rotation_angle](/cells/python-net/fr/aspose.cells/style/rotation_angle) | Représente l'angle de rotation du texte.|
| [horizontal_alignment](/cells/python-net/fr/aspose.cells/style/horizontal_alignment) | Obtient ou définit le type d'alignement horizontal du texte dans une cellule.|
| [vertical_alignment](/cells/python-net/fr/aspose.cells/style/vertical_alignment) | Obtient ou définit le type d'alignement vertical du texte dans une cellule.|
| [is_text_wrapped](/cells/python-net/fr/aspose.cells/style/is_text_wrapped) | Obtient ou définit une valeur indiquant si le texte dans une cellule est enveloppé.|
| [number](/cells/python-net/fr/aspose.cells/style/number) | Obtient ou définit le format d'affichage des nombres et des dates. Les modèles de formatage varient selon les régions.|
| [is_locked](/cells/python-net/fr/aspose.cells/style/is_locked) | Obtient ou définit une valeur indiquant si une cellule peut être modifiée ou non.|
| [custom](/cells/python-net/fr/aspose.cells/style/custom) | Représente la chaîne de format numérique personnalisée de cet objet de style.<br/>Si le format de nombre personnalisé n'est pas défini (par exemple, le format de nombre est intégré), "" sera renvoyé.|
| [culture_custom](/cells/python-net/fr/aspose.cells/style/culture_custom) | Obtient et définit la chaîne de modèle dépendante de la culture pour le format numérique.<br/>Si aucun format numérique n'a été défini pour cet objet, null sera renvoyé.<br/> Si le format numérique est intégré, la chaîne de modèle correspondant au numéro intégré sera renvoyée.|
| [invariant_custom](/cells/python-net/fr/aspose.cells/style/invariant_custom) | Obtient la chaîne de modèle indépendante de la culture pour le format numérique.<br/>Si aucun format numérique n'a été défini pour cet objet, null sera renvoyé.<br/> Si le format numérique est intégré, la chaîne de modèle correspondant au numéro intégré sera renvoyée.|
| [is_formula_hidden](/cells/python-net/fr/aspose.cells/style/is_formula_hidden) | Indique si la formule sera masquée lorsque la feuille de calcul est protégée.|
| [shrink_to_fit](/cells/python-net/fr/aspose.cells/style/shrink_to_fit) | Indique si le texte se réduit automatiquement pour s'adapter à la largeur de colonne disponible.|
| [text_direction](/cells/python-net/fr/aspose.cells/style/text_direction) | Représente l'ordre de lecture du texte.|
| [is_justify_distributed](/cells/python-net/fr/aspose.cells/style/is_justify_distributed) | Indique si l'alignement justifié ou distribué des cellules doit être utilisé sur la dernière ligne de texte.|
| [quote_prefix](/cells/python-net/fr/aspose.cells/style/quote_prefix) | Indique si la valeur de la cellule commence par un guillemet simple.|
| [is_gradient](/cells/python-net/fr/aspose.cells/style/is_gradient) | Indique si l'ombrage des cellules est un motif dégradé.|
| [is_percent](/cells/python-net/fr/aspose.cells/style/is_percent) | Indique si le format numérique est un format de pourcentage.|
| [is_date_time](/cells/python-net/fr/aspose.cells/style/is_date_time) | Indique si le format numérique est un format de date.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/fr/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Définit les bordures du style.|
| [`set_border(self, border_type, border_style, border_color)`](/cells/python-net/fr/aspose.cells/style/set_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Définit les bordures du style.|
| [`set_pattern_color(self, pattern, color1, color2)`](/cells/python-net/fr/aspose.cells/style/set_pattern_color/#aspose.cells.backgroundtype-aspose.pydrawing.color-aspose.pydrawing.color) |Définit la couleur d'arrière-plan.|
| [`copy(self, style)`](/cells/python-net/fr/aspose.cells/style/copy/#aspose.cells.style) | Copie les données d'un autre objet de style|
| [`update(self)`](/cells/python-net/fr/aspose.cells/style/update/#) | Appliquez le style nommé aux styles des cellules qui utilisent ce style nommé.<br/>Cela fonctionne comme si vous cliquiez sur le bouton « ok » après avoir terminé de modifier le style.<br/> S'applique uniquement au style nommé.|
| [`is_modified(self, modify_flag)`](/cells/python-net/fr/aspose.cells/style/is_modified/#aspose.cells.stylemodifyflag) | Vérifie si les propriétés spécifiées du style ont été modifiées.<br/> Utilisé pour le style de ConditionalFormattings pour vérifier si les propriétés spécifiées de ce style doivent être utilisées lors de l'application de ConditionalFormattings sur une cellule.|
| [`set_custom(self, custom, builtin_preference)`](/cells/python-net/fr/aspose.cells/style/set_custom/#str-bool) | Définit la chaîne de format numérique personnalisée d'une cellule.|
| [`set_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/fr/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Définit le remplissage spécifié sur un dégradé à deux couleurs.|
| [`get_two_color_gradient(self, color1, color2, gradient_style_type, variant)`](/cells/python-net/fr/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.color&-aspose.pydrawing.color&-any-any) | Obtenez le paramètre de dégradé bicolore.|
| [`get_two_color_gradient_setting(self)`](/cells/python-net/fr/aspose.cells/style/get_two_color_gradient_setting/#) | Obtenez le paramètre de dégradé bicolore.|
| [`to_json(self)`](/cells/python-net/fr/aspose.cells/style/to_json/#) | Convertissez les données de structure [`Style`](/cells/python-net/fr/aspose.cells/style) en JSON.|



###  Exemple

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
style.font.name = "Times New Roman"
style.font.color = Color.blue
cell.set_style(style)

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`BorderCollection`](/cells/python-net/fr/aspose.cells/bordercollection)
* classe [`Style`](/cells/python-net/fr/aspose.cells/style)
