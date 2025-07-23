---
title: memory_setting propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1160
url: /fr/aspose.cells/cells/memory_setting/
is_root: false
---
##  memory_setting propriété

Obtient ou définit l'option d'utilisation de la mémoire pour ces cellules.

###  Remarques

Limites notables et opérations recommandées pour certains modes :
| Mode| Remarques| Soutenu|
| :- | :- | :- |
|
 pour réduire le coût mémoire. D'autre part, les données compactes peuvent également
 entraîner des coûts de temps plus élevés, en particulier lors de la mise à jour des données des cellules,
 ou accéder aux cellules/lignes de manière aléatoire | v8.0.0 |
|
 Lorsque ce mode est utilisé pour n'importe quelle feuille de calcul dans un classeur, |
 doit être appelé à la fin du travail pour libérer toutes les ressources telles que les fichiers temporaires.
            | 
 L'accès aléatoire aux cellules donnera de mauvaises performances car les données ont besoin
 être lu/mis à jour de manière aléatoire et répétée (donc le pointeur dans le fichier sera
modifié en conséquence et les opérations d'E/S seront nécessaires à plusieurs reprises).
 Si possible, veuillez toujours accéder aux données de manière séquentielle (ligne par ligne).
            | 
 Lorsque les données d'une ligne/cellule sont modifiées, les données des autres cellules/lignes
 peut également être influencé (par exemple, les données peuvent être déplacées vers d'autres emplacements)
 pour allouer suffisamment d'espace pour les données modifiées).
 Ainsi, chaque modification de chaque donnée nécessite une synchronisation des autres objets existants (
 comme Row ou l'objet Cell).
 Donc, pour obtenir de meilleures performances, veuillez ne pas conserver plusieurs lignes/Cells
 simultanément. Les traiter un par un réduira la synchronisation des données.
 pour eux, les performances peuvent donc être un peu améliorées.
 | v25.7 |
###  Définition:
```python
@property
def memory_setting(self):
    ...
@memory_setting.setter
def memory_setting(self, value):
    ...
```

###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/fr/aspose.cells/cells)
* classe [`MemorySetting`](/cells/python-net/fr/aspose.cells/memorysetting)
