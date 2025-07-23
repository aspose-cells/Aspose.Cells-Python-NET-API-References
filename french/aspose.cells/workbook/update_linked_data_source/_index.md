---
title: méthode update_linked_data_source
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 440
url: /fr/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source(self, external_workbooks) {#list}
Si ce classeur contient des liens externes vers d'autres sources de données,
Aspose.Cells tentera de récupérer les dernières données à partir des sources données.



```python

def update_linked_data_source(self, external_workbooks):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| external_workbooks | list | Cahiers d'exercices qui seront utilisés pour mettre à jour les données des liens externes référencés par ce classeur.<br/>La correspondance de ces classeurs avec des liens externes est déterminée par [`Workbook.file_name`](/cells/python-net/fr/aspose.cells/workbook#file_name)<br/>et [`ExternalLink.data_source`](/cells/python-net/fr/aspose.cells/externallink#data_source). Veuillez donc vous assurer que [`Workbook.file_name`](/cells/python-net/fr/aspose.cells/workbook#file_name) a<br/> ont été spécifiés avec la valeur appropriée pour chaque classeur afin qu'ils puissent être liés au lien externe correspondant.|
###  Remarques

Si le lien externe correspondant ne peut pas être trouvé pour un classeur, ce classeur sera ignoré.
Ainsi, lorsque vous définissez ultérieurement une formule avec un nouveau lien externe que vous souhaitez ignorer, le classeur
être lié à celui-ci, le lien ne peut pas être effectué tant que vous n'appelez pas à nouveau cette méthode avec ces classeurs.


###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
