---
title: CalculationPrecisionStrategy énumération
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1790
url: /fr/aspose.cells/calculationprecisionstrategy/
is_root: false
---
##  CalculationPrecisionStrategy énumération
Énumère les stratégies de gestion de la précision des calculs.
En raison du problème de précision de l'arithmétique à virgule flottante IEEE 754, certaines formules « apparemment simples » peuvent ne pas être calculées comme le résultat attendu.
Par exemple, dans la formule « =-0,45+0,43+0,02 », le calcul direct des opérandes par l'opérateur « + » produit un résultat différent de zéro. Pour ce type de problème de précision,
certaines stratégies spéciales peuvent donner le résultat escompté.



Le type CalculationPrecisionStrategy expose les membres suivants :

###  Des champs
| Champ| Description|
| :- | :- |
| NONE | Aucune stratégie appliquée au calcul.<br/>Lors du calcul, utilisez simplement la valeur double d'origine comme opérande et renvoyez le résultat directement.<br/> Le plus efficace en termes de performances et applicable dans la plupart des cas.|
| ROUND | Arrondit le résultat du calcul en utilisant des chiffres significatifs.|
| DECIMAL | Utilise le nombre décimal comme opérandes lorsque cela est possible.<br/> Le plus inefficace en termes de performances.|



###  Voir également
* module [`aspose.cells`](..)
