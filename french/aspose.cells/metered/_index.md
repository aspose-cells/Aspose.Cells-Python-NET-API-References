---
title: Metered classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 980
url: /fr/aspose.cells/metered/
is_root: false
---
##  Metered classe
Fournit des méthodes pour définir la clé mesurée.



Le type Metered expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/metered/__init__/#) | Initialise une nouvelle instance de cette classe.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/cells/python-net/fr/aspose.cells/metered/set_metered_key/#str-str) | Définit les clés publiques et privées mesurées.<br/>Si vous achetez une licence mesurée, lors du démarrage de l'application, ce numéro API doit être appelé, normalement, cela suffit.<br/> Cependant, si les données de consommation ne sont toujours pas téléchargées et que le délai dépasse 24 heures, la licence sera définie sur le statut d'évaluation,<br/> pour éviter un tel cas, vous devez vérifier régulièrement l'état de la licence, s'il s'agit d'un état d'évaluation, appelez à nouveau le API.|
| [`get_consumption_quantity()`](/cells/python-net/fr/aspose.cells/metered/get_consumption_quantity/#) | Obtient la taille du fichier de consommation|
| [`get_consumption_credit()`](/cells/python-net/fr/aspose.cells/metered/get_consumption_credit/#) | Obtient un crédit à la consommation|
| [`get_product_name(self)`](/cells/python-net/fr/aspose.cells/metered/get_product_name/#) | Obtient le nom du produit|
| [`is_metered_licensed()`](/cells/python-net/fr/aspose.cells/metered/is_metered_licensed/#) | Vérifiez si le compteur est autorisé|



###  Exemple

Dans cet exemple, une tentative sera faite pour définir une clé publique et privée mesurée


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Voir également
* module [`aspose.cells`](..)
