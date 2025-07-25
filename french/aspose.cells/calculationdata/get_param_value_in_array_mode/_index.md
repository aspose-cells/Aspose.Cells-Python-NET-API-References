---
title: méthode get_param_value_in_array_mode
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode(self, index, max_row_count, max_column_count) {#int-int-int}
Obtient la ou les valeurs du paramètre à l'index donné.
Si le paramètre est une sorte d’expression qui doit être calculée,
alors il sera calculé en mode tableau.


###  Retour

Un tableau qui contient tous les éléments représentés par le paramètre spécifié.


```python

def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| index | int | L'index du paramètre (basé sur 0)|
| max_row_count | int | La limite du nombre de lignes pour le tableau renvoyé.<br/> Si le nombre de lignes n'est pas positif ou est supérieur au nombre réel de lignes, le nombre réel de lignes sera utilisé.|
| max_column_count | int | La limite du nombre de colonnes pour le tableau renvoyé.<br/> Si le nombre n'est pas positif ou supérieur au nombre réel de lignes, le nombre réel de colonnes sera utilisé.|
###  Remarques

Pour une expression qui doit être calculée, en prenant A:A+B:B comme exemple :
En mode valeur, il sera calculé sur une valeur unique en fonction de la base de cellules actuelle.
Mais en mode tableau, toutes les valeurs de A1+B1,A2+B2,A3+B3,... seront calculées et utilisées pour construire le tableau renvoyé.
Et pour ce genre de situation, il est préférable de spécifier la limite du nombre de lignes/colonnes
(comme selon [`Cells.max_data_row`](/cells/python-net/fr/aspose.cells/cells#max_data_row) et [`Cells.max_data_column`](/cells/python-net/fr/aspose.cells/cells#max_data_column)),
sinon, le grand tableau renvoyé peut augmenter le coût de la mémoire avec une grande quantité de données inutiles.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`CalculationData`](/cells/python-net/fr/aspose.cells/calculationdata)
