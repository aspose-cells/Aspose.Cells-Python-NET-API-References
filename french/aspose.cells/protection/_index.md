---
title: Protection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1150
url: /fr/aspose.cells/protection/
is_root: false
---
##  Protection classe
Représente les différents types d’options de protection disponibles pour une feuille de calcul.



Le type Protection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [allow_deleting_column](/cells/python-net/fr/aspose.cells/protection/allow_deleting_column) | Indique si la suppression de colonnes est autorisée sur une feuille de calcul protégée.|
| [allow_deleting_row](/cells/python-net/fr/aspose.cells/protection/allow_deleting_row) | Indique si la suppression de lignes est autorisée sur une feuille de calcul protégée.|
| [allow_filtering](/cells/python-net/fr/aspose.cells/protection/allow_filtering) | Indique si l'utilisateur est autorisé à utiliser un filtre automatique créé avant que la feuille ne soit protégée.|
| [allow_formatting_cell](/cells/python-net/fr/aspose.cells/protection/allow_formatting_cell) | Indique si la mise en forme des cellules est autorisée sur une feuille de calcul protégée.|
| [allow_formatting_column](/cells/python-net/fr/aspose.cells/protection/allow_formatting_column) | Indique si la mise en forme des colonnes est autorisée sur une feuille de calcul protégée|
| [allow_formatting_row](/cells/python-net/fr/aspose.cells/protection/allow_formatting_row) |Indique si la mise en forme des lignes est autorisée sur une feuille de calcul protégée|
| [allow_inserting_column](/cells/python-net/fr/aspose.cells/protection/allow_inserting_column) | Indique si l'insertion de colonnes est autorisée sur une feuille de calcul protégée|
| [allow_inserting_hyperlink](/cells/python-net/fr/aspose.cells/protection/allow_inserting_hyperlink) | Indique si l'insertion d'hyperliens est autorisée sur une feuille de calcul protégée|
| [allow_inserting_row](/cells/python-net/fr/aspose.cells/protection/allow_inserting_row) | Indique si l'insertion de lignes est autorisée sur une feuille de calcul protégée|
| [allow_sorting](/cells/python-net/fr/aspose.cells/protection/allow_sorting) | Indique si l'option de tri est autorisée sur une feuille de calcul protégée.|
| [allow_using_pivot_table](/cells/python-net/fr/aspose.cells/protection/allow_using_pivot_table) | Indique si l'utilisateur est autorisé à manipuler des tableaux croisés dynamiques sur une feuille de calcul protégée.|
| [allow_editing_content](/cells/python-net/fr/aspose.cells/protection/allow_editing_content) | Indique si l'utilisateur est autorisé à modifier le contenu des cellules verrouillées sur une feuille de calcul protégée.|
| [allow_editing_object](/cells/python-net/fr/aspose.cells/protection/allow_editing_object) | Indique si l'utilisateur est autorisé à manipuler des objets de dessin sur une feuille de calcul protégée.|
| [allow_editing_scenario](/cells/python-net/fr/aspose.cells/protection/allow_editing_scenario) | Indique si l'utilisateur est autorisé à modifier des scénarios sur une feuille de calcul protégée.|
| [allow_selecting_locked_cell](/cells/python-net/fr/aspose.cells/protection/allow_selecting_locked_cell) | Indique si l'utilisateur est autorisé à sélectionner des cellules verrouillées sur une feuille de calcul protégée.|
| [allow_selecting_unlocked_cell](/cells/python-net/fr/aspose.cells/protection/allow_selecting_unlocked_cell) | Indique si l'utilisateur est autorisé à sélectionner des cellules déverrouillées sur une feuille de calcul protégée.|
| [password](/cells/python-net/fr/aspose.cells/protection/password) | Représente le mot de passe pour protéger la feuille de calcul.|
| [is_protected_with_password](/cells/python-net/fr/aspose.cells/protection/is_protected_with_password) | Indique si les feuilles de calcul sont protégées par un mot de passe.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/fr/aspose.cells/protection/copy/#aspose.cells.protection) |Informations sur la protection contre la copie.|
| [`verify_password(self, password)`](/cells/python-net/fr/aspose.cells/protection/verify_password/#str) | Vérifie le mot de passe.|
| [`get_password_hash(self)`](/cells/python-net/fr/aspose.cells/protection/get_password_hash/#) | Obtient le hachage du mot de passe actuel.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Allowing users to select locked cells of the worksheet
worksheet.protection.allow_selecting_locked_cell = True
# Allowing users to select unlocked cells of the worksheet
worksheet.protection.allow_selecting_unlocked_cell = True

```

###  Voir également
* module [`aspose.cells`](..)
