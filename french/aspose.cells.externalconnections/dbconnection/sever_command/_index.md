---
title: sever_command propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 300
url: /fr/aspose.cells.externalconnections/dbconnection/sever_command/
is_root: false
---
##  sever_command propriété

 Spécifie une deuxième chaîne de texte de commande qui est conservée lorsque le tableau croisé dynamique est basé sur un serveur
 les champs de page sont utilisés.
 Pour les connexions ODBC, serverCommand est généralement une requête plus large que command (pas de
La clause WHERE est présente dans le premier cas. Sur la base de ces deux commandes (Command et ServerCommand),
l'interface utilisateur des paramètres peut être renseignée et des requêtes paramétrées peuvent être construites

###  Remarques

 REMARQUE : Cette propriété est désormais obsolète. À la place,
veuillez utiliser la propriété ExternalConnection.SecondCommand.
 Cette méthode sera supprimée 12 mois plus tard soit en octobre 2024.
Aspose s'excuse pour tout inconvénient que vous avez pu rencontrer.
###  Définition:
```python
@property
def sever_command(self):
    ...
@sever_command.setter
def sever_command(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.externalconnections`](../../)
* classe [`DBConnection`](/cells/python-net/fr/aspose.cells.externalconnections/dbconnection)
