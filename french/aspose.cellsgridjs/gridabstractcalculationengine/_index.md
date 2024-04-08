---
title: GridAbstractCalculationEngine classe
second_title: Aspose.Cells.GridJs for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cellsgridjs/gridabstractcalculationengine/
is_root: false
---
##  GridAbstractCalculationEngine classe

Représente le moteur de calcul personnalisé de l'utilisateur pour étendre le moteur de calcul par défaut de Aspose.Cells.



Le type GridAbstractCalculationEngine expose les membres suivants :

###  Méthodes
| Méthode| Description|
| :- | :- |
| [calculate](/cells/python-net/fr/aspose.cellsgridjs/gridabstractcalculationengine/calculate/#aspose.cellsgridjs.GridCalculationData) | Calcule une fonction avec des données données.|



###  Remarques


L'utilisateur ne doit modifier aucune partie du classeur directement dans cette implémentation (à l'exception du résultat calculé de la fonction personnalisée, qui peut être définie par la propriété GridCalculationData.CalculatedValue).
Sinon, un résultat inattendu ou une exception peut être provoqué.
Si l'utilisateur doit modifier d'autres données que le résultat calculé lors de la mise en œuvre de certaines fonctions personnalisées,
Par exemple, modifiez la formule, le style, etc. de la cellule, l'utilisateur doit rassembler ces données dans cette implémentation et les modifier hors du champ d'application du calcul de la formule.

###  Voir également
* module [`aspose.cellsgridjs`](..)
