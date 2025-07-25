---
title: méthode get_dependents
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 90
url: /fr/aspose.cells/cell/get_dependents/
is_root: false
---
##  get_dependents(self, is_all) {#bool}
Obtenez toutes les cellules dont la formule fait directement référence à cette cellule.



```python

def get_dependents(self, is_all):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| is_all | bool |Indique si les formules de vérification sont présentes dans d'autres feuilles de calcul|
###  Remarques

* Si une référence contenant cette cellule apparaît dans la formule d'une cellule, cette cellule sera considérée comme

la dépendance de cette cellule, peu importe la référence ou si cette cellule est utilisée ou non lors du calcul.
Par exemple, bien que la cellule A2 de la formule « =SI(VRAI,A1,A2) » ne soit pas utilisée lors du calcul,
cette formule doit toujours être considérée comme dépendante de A2.
Pour obtenir les formules dont les résultats calculés dépendent de cette cellule, veuillez utiliser [`Cell.get_dependents_in_calculation`](/cells/python-net/fr/aspose.cells/cell/get_dependents_in_calculation). Lors du traçage des dépendants pour une cellule, toutes les formules du classeur ou de la feuille de calcul seront analysées et vérifiées.
C'est donc un processus chronophage. Si l'utilisateur doit tracer les dépendants de nombreuses cellules, cette méthode permettra
Cela peut entraîner de mauvaises performances. Pour des raisons de performances, l'utilisateur doit plutôt utiliser [`Cell.get_dependents_in_calculation`](/cells/python-net/fr/aspose.cells/cell/get_dependents_in_calculation).
Ou, l'utilisateur peut rassembler la carte des précédents de toutes les cellules en composant d'abord le [`Cell.get_precedents`](/cells/python-net/fr/aspose.cells/cell/get_precedents),
et ensuite construire la carte des dépendants selon la carte des précédents.

* Si une référence contenant cette cellule apparaît dans la formule d'une cellule, cette cellule sera considérée comme
la dépendance de cette cellule, peu importe la référence ou si cette cellule est utilisée ou non lors du calcul.
Par exemple, bien que la cellule A2 de la formule « =SI(VRAI,A1,A2) » ne soit pas utilisée lors du calcul,
cette formule doit toujours être considérée comme dépendante de A2.
Pour obtenir les formules dont les résultats calculés dépendent de cette cellule, veuillez utiliser [`Cell.get_dependents_in_calculation`](/cells/python-net/fr/aspose.cells/cell/get_dependents_in_calculation). Lors du traçage des dépendants pour une cellule, toutes les formules du classeur ou de la feuille de calcul seront analysées et vérifiées.
C'est donc un processus chronophage. Si l'utilisateur doit tracer les dépendants de nombreuses cellules, cette méthode permettra
Cela peut entraîner de mauvaises performances. Pour des raisons de performances, l'utilisateur doit plutôt utiliser [`Cell.get_dependents_in_calculation`](/cells/python-net/fr/aspose.cells/cell/get_dependents_in_calculation).
Ou, l'utilisateur peut rassembler la carte des précédents de toutes les cellules en composant d'abord le [`Cell.get_precedents`](/cells/python-net/fr/aspose.cells/cell/get_precedents),
et ensuite construire la carte des dépendants selon la carte des précédents.

* Si une référence contenant cette cellule apparaît dans la formule d'une cellule, cette cellule sera considérée comme
la dépendance de cette cellule, peu importe la référence ou si cette cellule est utilisée ou non lors du calcul.
Par exemple, bien que la cellule A2 de la formule « =SI(VRAI,A1,A2) » ne soit pas utilisée lors du calcul,
cette formule doit toujours être considérée comme dépendante de A2.
Pour obtenir les formules dont les résultats calculés dépendent de cette cellule, veuillez utiliser [`Cell.get_dependents_in_calculation`](/cells/python-net/fr/aspose.cells/cell/get_dependents_in_calculation). Lors du traçage des dépendants pour une cellule, toutes les formules du classeur ou de la feuille de calcul seront analysées et vérifiées.
C'est donc un processus chronophage. Si l'utilisateur doit tracer les dépendants de nombreuses cellules, cette méthode permettra
Cela peut entraîner de mauvaises performances. Pour des raisons de performances, l'utilisateur doit plutôt utiliser [`Cell.get_dependents_in_calculation`](/cells/python-net/fr/aspose.cells/cell/get_dependents_in_calculation).
Ou, l'utilisateur peut rassembler la carte des précédents de toutes les cellules en composant d'abord le [`Cell.get_precedents`](/cells/python-net/fr/aspose.cells/cell/get_precedents),
et ensuite construire la carte des dépendants selon la carte des précédents.
###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
dependents = cells.get("B1").get_dependents(True)
for i in range(len(dependents)):
    print(dependents[i].name)

```



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
