---
title: CalculationOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 100
url: /fr/aspose.cells/calculationoptions/
is_root: false
---
##  CalculationOptions classe
Représente les options de calcul.



Le type CalculationOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/calculationoptions/__init__/#) | Construit une nouvelle instance de CalculationOptions|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [ignore_error](/cells/python-net/fr/aspose.cells/calculationoptions/ignore_error) | Indique si les erreurs rencontrées lors du calcul des formules doivent être ignorées.<br/>L'erreur peut être une fonction non prise en charge, des liens externes, etc.<br/> La valeur par défaut est vrai.|
| [recursive](/cells/python-net/fr/aspose.cells/calculationoptions/recursive) | Indique si les cellules dépendantes doivent être calculées de manière récursive lors du calcul d'une cellule et si elle dépend d'autres cellules.<br/> La valeur par défaut est vrai.|
| [calc_stack_size](/cells/python-net/fr/aspose.cells/calculationoptions/calc_stack_size) | Taille de la pile pour le calcul récursif des cellules. La valeur par défaut est 200.|
| [precision_strategy](/cells/python-net/fr/aspose.cells/calculationoptions/precision_strategy) | Spécifie la stratégie de traitement de la précision du calcul.|
| [linked_data_sources](/cells/python-net/fr/aspose.cells/calculationoptions/linked_data_sources) | Spécifie les sources de données pour les liens externes utilisés dans les formules.|
| [character_encoding](/cells/python-net/fr/aspose.cells/calculationoptions/character_encoding) | Spécifie l'encodage utilisé pour l'encodage/décodage des caractères lors du calcul des formules.<br/>Pour les fonctions telles que CHAR, CODE, le résultat calculé dépend des paramètres de région et du jeu de caractères par défaut de l'environnement.<br/>Avec cette propriété, l'utilisateur peut spécifier l'encodage approprié utilisé pour ces fonctions afin d'obtenir le résultat attendu.|



###  Voir également
* module [`aspose.cells`](..)
