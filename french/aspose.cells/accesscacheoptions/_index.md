---
title: AccessCacheOptions énumération
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1810
url: /fr/aspose.cells/accesscacheoptions/
is_root: false
---
##  AccessCacheOptions énumération
Options de cache pour l'accès aux données. Peut être combiné avec | opérateur pour plusieurs options ensemble.



Le type AccessCacheOptions expose les membres suivants :

###  Des champs
| Champ| Description|
| :- | :- |
| NONE | Pas de cache pour tout accès aux données.|
| ALL | Appliquez toutes les optimisations possibles pour tous les types d’accès aux données dans le classeur.<br/> Tous les paramètres et données ne doivent pas être modifiés pendant l'accès optimisé.|
| POSITION_AND_SIZE |Appliquez une optimisation possible pour obtenir la position et la taille de l'objet (tel que la forme).<br/> Les paramètres de hauteur de ligne et de largeur de colonne ne doivent pas être modifiés lors de l’accès optimisé.|
| CELLS_DATA | Appliquez une optimisation possible pour obtenir les valeurs des cellules.<br/>Les données Cells (données et paramètres de Cell, ligne) ne doivent pas être modifiées pendant<br/>l'accès optimisé, aucun nouvel objet Cell/Row ne doit être créé non plus (comme<br/> par [indexeur]).|
| CELL_DISPLAY | Appliquer une optimisation possible pour obtenir des résultats liés à l'affichage de<br/>cellules ([`Cell.display_string_value`](/cells/python-net/fr/aspose.cells/cell#display_string_value), [`Cell.get_style`](/cells/python-net/fr/aspose.cells/cell/get_style), [`Cell.get_display_style`](/cells/python-net/fr/aspose.cells/cell/get_display_style), etc.).<br/>Les données Cells et les objets liés au style (styles Cell/ligne/colonne, largeur de colonne, etc.) ne doivent pas être modifiés.<br/> lors de l'accès optimisé.|
| GET_FORMULA | Appliquez l'optimisation possible pour obtenir des formules.<br/>Toutes les données et paramètres pouvant affecter l'expression de la formule (nom de la feuille de calcul, texte du nom,<br/> colonne du tableau, etc.) ne doit pas être modifié lors de l'accès optimisé.|
| SET_FORMULA |Appliquer l'optimisation possible pour définir les formules.<br/>Toutes les données et paramètres pouvant affecter l'expression de la formule (nom de la feuille de calcul, texte du nom,<br/> colonne du tableau, etc.) ne doit pas être modifié lors de l'accès optimisé.|
| CALCULATE_FORMULA | Appliquer une optimisation possible pour calculer les formules.<br/>Les données Cells ne doivent pas être modifiées lors de l'accès optimisé, aucun nouvel objet (Cell, ligne, etc.)<br/> doit être créé soit (comme par [indexeur]).|
| CONDITIONAL_FORMATTING | Appliquez une optimisation possible pour obtenir le résultat du formatage des formatages conditionnels.<br/>Toutes les données et paramètres pouvant affecter le résultat des formatages conditionnels (paramètres de<br/> formatages conditionnels, valeurs de cellules dépendantes, etc.) ne doivent pas être modifiés lors de l'accès optimisé.|
| VALIDATION | Appliquez l'optimisation possible pour obtenir le résultat de la validation.<br/>Toutes les données et paramètres pouvant affecter le résultat de la validation(paramètres de la validation,<br/> valeurs de cellules dépendantes, etc.) ne doivent pas être modifiées lors de l'accès optimisé.|



###  Remarques

Pour certaines fonctionnalités, l'accès à un grand ensemble de données nécessite de nombreuses opérations répétées et compliquées
telles que la recherche, le calcul, ... etc. et ces opérations prendront beaucoup de temps supplémentaire.
Pour les situations courantes, toutes les données dépendantes restent inchangées pendant l'accès, donc certains caches peuvent être créés et utilisés pour
améliorer les performances d’accès.
À cette fin, nous fournissons ce API afin que l'utilisateur puisse spécifier le type d'accès aux données dont il a besoin.
à optimiser par un éventuel mécanisme de mise en cache.


Veuillez noter que pour différentes options, différents ensembles de données peuvent être requis pour être « en lecture seule ».
Et les performances d'accès aux données dépendent de nombreux aspects, l'utilisation du mécanisme de mise en cache
ne garantit pas que les performances seront améliorées. Pour certaines situations,
comme l'ensemble de données auquel accéder est petit, l'utilisation du cache peut prendre encore plus de temps car
la mise en cache elle-même nécessite également un certain temps supplémentaire.

###  Voir également
* module [`aspose.cells`](..)
