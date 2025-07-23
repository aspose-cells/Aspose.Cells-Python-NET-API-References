---
title: méthode set_metered_key
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells/metered/set_metered_key/
is_root: false
---
##  set_metered_key(self, public_key, private_key) {#str-str}
Définit les clés publiques et privées mesurées.
Si vous achetez une licence mesurée, lors du démarrage de l'application, ce numéro API doit être appelé, normalement, cela suffit.
 Cependant, si les données de consommation ne sont toujours pas téléchargées et que le délai dépasse 24 heures, la licence sera définie sur le statut d'évaluation,
pour éviter un tel cas, vous devez vérifier régulièrement l'état de la licence, s'il s'agit d'un état d'évaluation, appelez à nouveau le API.



```python

def set_metered_key(self, public_key, private_key):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| public_key | str | clé publique|
| private_key | str | clé privée|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Metered`](/cells/python-net/fr/aspose.cells/metered)
