---
title: CalculationOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 130
url: /fr/aspose.cells/calculationoptions/
is_root: false
---
##  CalculationOptions classe
Représente les options de calcul.



Le type CalculationOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/calculationoptions/__init__/#) | Construit une nouvelle instance de CalculationOptions|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [ignore_error](/cells/python-net/fr/aspose.cells/calculationoptions/ignore_error) | Indique si les erreurs rencontrées lors du calcul des formules doivent être ignorées.<br/>L'erreur peut provenir d'une fonction non prise en charge, de liens externes, etc.<br/> La valeur par défaut est vraie.|
| [recursive](/cells/python-net/fr/aspose.cells/calculationoptions/recursive) | Indique si le calcul des cellules dépendantes est effectué de manière récursive lors du calcul d'une cellule et si cela dépend des autres cellules.<br/> La valeur par défaut est vraie.|
| [custom_engine](/cells/python-net/fr/aspose.cells/calculationoptions/custom_engine) | Le moteur de calcul de formule personnalisé pour étendre le moteur de calcul par défaut de Aspose.Cells.|
| [calculation_monitor](/cells/python-net/fr/aspose.cells/calculationoptions/calculation_monitor) | Le moniteur permettant à l'utilisateur de suivre la progression du calcul de la formule.|
| [calc_stack_size](/cells/python-net/fr/aspose.cells/calculationoptions/calc_stack_size) | La taille de la pile pour calculer les cellules de manière récursive. La valeur par défaut est 200.|
| [precision_strategy](/cells/python-net/fr/aspose.cells/calculationoptions/precision_strategy) | Spécifie la stratégie de traitement de la précision du calcul.|
| [linked_data_sources](/cells/python-net/fr/aspose.cells/calculationoptions/linked_data_sources) | Spécifie les sources de données pour les liens externes utilisés dans les formules.|
| [character_encoding](/cells/python-net/fr/aspose.cells/calculationoptions/character_encoding) | Spécifie l'encodage utilisé pour encoder/décoder les caractères lors du calcul des formules.<br/>Pour les fonctions telles que CHAR, CODE, le résultat calculé dépend des paramètres de région et du jeu de caractères par défaut de l'environnement.<br/> Avec cette propriété, l'utilisateur peut spécifier le codage approprié utilisé pour ces fonctions afin d'obtenir le résultat attendu.|



###  Voir également
* module [`aspose.cells`](..)
