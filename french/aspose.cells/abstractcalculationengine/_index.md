---
title: AbstractCalculationEngine classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/abstractcalculationengine/
is_root: false
---
##  AbstractCalculationEngine classe
Représente le moteur de calcul personnalisé de l'utilisateur pour étendre le moteur de calcul par défaut de Aspose.Cells.



Le type AbstractCalculationEngine expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [is_param_literal_required](/cells/python-net/fr/aspose.cells/abstractcalculationengine/is_param_literal_required) |Indique si ce moteur a besoin du texte littéral du paramètre lors du calcul. La valeur par défaut est fausse.|
| [is_param_array_mode_required](/cells/python-net/fr/aspose.cells/abstractcalculationengine/is_param_array_mode_required) | Indique si ce moteur a besoin que le paramètre soit calculé en mode tableau. La valeur par défaut est fausse.<br/>Si [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/fr/aspose.cells/calculationdata/get_param_value_in_array_mode) est requis lors du calcul des douanes<br/>fonctions et l'utilisateur n'a pas mis à jour la définition pour elles<br/>(par [`Workbook.update_custom_function_definition`](/cells/python-net/fr/aspose.cells/workbook/update_custom_function_definition)),<br/> cette propriété doit être définie comme vraie.|
| [process_built_in_functions](/cells/python-net/fr/aspose.cells/abstractcalculationengine/process_built_in_functions) | Si les fonctions intégrées ont été prises en charge par le moteur intégré<br/>doivent être vérifiés et traités par cette implémentation.<br/> La valeur par défaut est fausse.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [calculate](/cells/python-net/fr/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) | Calcule une fonction avec des données données.|



###  Remarques

L'utilisateur ne doit modifier aucune partie du classeur directement dans cette implémentation (sauf
le résultat calculé de la fonction personnalisée, qui peut être défini par la propriété CalculationData.CalculatedValue).
Sinon, un résultat inattendu ou une exception peut être provoqué.
Si l'utilisateur doit modifier d'autres données que le résultat calculé lors de la mise en œuvre de certaines fonctions personnalisées,
par exemple, modifier la formule, le style, etc. de la cellule, l'utilisateur doit rassembler ces données dans cette implémentation
et modifiez-les hors du champ d'application du calcul de la formule.

###  Voir également
* module [`aspose.cells`](..)
