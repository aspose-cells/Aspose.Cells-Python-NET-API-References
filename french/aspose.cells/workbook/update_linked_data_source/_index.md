---
title: méthode update_linked_data_source
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 420
url: /fr/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source {#list}
Si ce classeur contient des liens externes vers une autre source de données,
Aspose.Cells tentera de récupérer les dernières données à partir de sources données.



```python
def update_linked_data_source(self, external_workbooks):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| external_workbooks | list | Classeurs qui serviront à mettre à jour les données des liens externes référencés par ce classeur.<br/>La correspondance de ces classeurs avec des liens externes est déterminée par [`Workbook.file_name`](/cells/python-net/fr/aspose.cells/workbook#file_name)<br/>et [`ExternalLink.data_source`](/cells/python-net/fr/aspose.cells/externallink#data_source). Veuillez donc vous assurer que [`Workbook.file_name`](/cells/python-net/fr/aspose.cells/workbook#file_name) a<br/> ont été spécifiés avec la valeur appropriée pour chaque classeur afin qu'ils puissent être liés au lien externe correspondant.|
###  Remarques

Si le lien externe correspondant est introuvable pour un classeur, ce classeur sera ignoré.
Ainsi, lorsque vous définissez une formule plus tard avec un nouveau lien externe dont vous avez l'intention de créer le classeur ignoré
être lié à celui-ci, le lien ne peut pas être effectué jusqu'à ce que vous appeliez à nouveau cette méthode avec ces classeurs.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
