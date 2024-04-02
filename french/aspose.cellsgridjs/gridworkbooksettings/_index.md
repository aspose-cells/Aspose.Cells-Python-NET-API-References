---
title: GridWorkbookSettings classe
second_title: Aspose.Cells.GridJs for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cellsgridjs/gridworkbooksettings/
is_root: false
---
##  GridWorkbookSettings classe

Représente les paramètres du classeur.



Le type GridWorkbookSettings expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/__init__/#) | Construit une nouvelle instance de GridWorkbookSettings|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [max_iteration](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/max_iteration) | Renvoie ou définit le nombre maximum d'itérations pour résoudre une référence circulaire, la valeur par défaut est 100.|
| [iteration](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/iteration) | Indique si vous utilisez l’itération pour résoudre les références circulaires.|
| [force_full_calculate](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/force_full_calculate) | Indique si le calcul est entièrement effectué à chaque fois qu'un calcul est déclenché.|
| [create_calc_chain](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/create_calc_chain) |Indique si vous créez une chaîne de formules calculées. La valeur par défaut est fausse.|
| [re_calculate_on_open](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/re_calculate_on_open) | Indique s'il faut recalculer toutes les formules à l'ouverture du fichier.|
| [precision_as_displayed](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/precision_as_displayed) | Vrai si les calculs dans ce classeur seront effectués en utilisant uniquement la précision des nombres tels qu'ils sont affichés|
| [date1904](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/date1904) | Obtient ou définit une valeur qui indique si le classeur utilise le système de date 1904.|
| [enable_macros](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/enable_macros) | Activer les macros ; Désormais, cela ne fonctionne que lors de la copie d'une feuille de calcul vers une autre feuille de calcul d'un classeur.|
| [check_custom_number_format](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/check_custom_number_format) | Indique si la vérification du format de numéro personnalisé lors de la définition de Style.Custom.|
| [author](/cells/python-net/fr/aspose.cellsgridjs/gridworkbooksettings/author) | Obtient/définit l'auteur du fichier.|



###  Exemple


```python
from aspose.cellsgridjs import GridJsWorkbook, GridWorkbookSettings

g = GridJsWorkbook()
gsettings = GridWorkbookSettings()
g.settings = gsettings

```

###  Voir également
* module [`aspose.cellsgridjs`](..)
