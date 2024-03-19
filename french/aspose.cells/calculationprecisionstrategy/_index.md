---
title: CalculationPrecisionStrategy énumération
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1890
url: /fr/aspose.cells/calculationprecisionstrategy/
is_root: false
---
##  CalculationPrecisionStrategy énumération
Énumère les stratégies pour gérer la précision des calculs.
En raison du problème de précision de l'arithmétique à virgule flottante IEEE 754, certaines formules « apparemment simples » peuvent ne pas être calculées comme résultat attendu.
Comme la formule "=-0,45+0,43+0,02", lors du calcul direct des opérandes par l'opérateur '+', le résultat n'est pas nul. Pour ce genre de problème de précision,
certaines stratégies spéciales peuvent donner le résultat attendu.



Le type CalculationPrecisionStrategy expose les membres suivants :

###  Des champs
| Champ| Description|
| :- | :- |
| NONE | Aucune stratégie appliquée sur le calcul.<br/>Lors du calcul, utilisez simplement la valeur double d'origine comme opérande et renvoyez directement le résultat.<br/> Le plus efficace en termes de performances et applicable dans la plupart des cas.|
| ROUND | Arrondit le résultat du calcul selon les chiffres significatifs.|
| DECIMAL |Utilise le nombre décimal comme opérande lorsque cela est possible.<br/> Le plus inefficace pour les performances.|



###  Voir également
* module [`aspose.cells`](..)
