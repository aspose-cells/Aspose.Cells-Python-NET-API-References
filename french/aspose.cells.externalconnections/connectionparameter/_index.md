---
title: ConnectionParameter classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells.externalconnections/connectionparameter/
is_root: false
---
##  ConnectionParameter classe
Spécifie les propriétés de tous les paramètres utilisés avec les connexions de données externes
Les paramètres sont valides pour les requêtes ODBC et Web.



Le type ConnectionParameter expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [sql_type](/cells/python-net/fr/aspose.cells.externalconnections/connectionparameter/sql_type) | Type de données SQL du paramètre. Valable uniquement pour les sources ODBC.|
| [refresh_on_change](/cells/python-net/fr/aspose.cells.externalconnections/connectionparameter/refresh_on_change) | Drapeau indiquant si la requête doit être automatiquement actualisée lorsque le contenu d'un<br/> La cellule indiquant les modifications de valeur du paramètre. Si la valeur est « vrai », les données externes sont actualisées.<br/> En utilisant la nouvelle valeur du paramètre à chaque modification. Si la valeur est fausse, les données externes sont alors<br/> n'est actualisé que lorsque l'utilisateur le demande ou lorsqu'un autre événement déclenche l'actualisation (par exemple, un classeur ouvert).|
| [prompt](/cells/python-net/fr/aspose.cells.externalconnections/connectionparameter/prompt) | Chaîne d'invite pour le paramètre. Présentée à l'utilisateur de la feuille de calcul avec l'interface de saisie.<br/> pour collecter la valeur du paramètre avant d'actualiser les données externes. Utilisé uniquement lorsque<br/>parameterType = invite.|
| [type](/cells/python-net/fr/aspose.cells.externalconnections/connectionparameter/type) | Type de paramètre utilisé.<br/> Si le paramètreType=valeur, alors la valeur est booléenne, double, entière,<br/> ou une chaîne sera utilisée. Dans ce cas, on s'attend à ce qu'une seule des<br/> {booléen, double, entier ou chaîne} sera spécifié.|
| [name](/cells/python-net/fr/aspose.cells.externalconnections/connectionparameter/name) | Le nom du paramètre.|
| [cell_reference](/cells/python-net/fr/aspose.cells.externalconnections/connectionparameter/cell_reference) | Référence Cell indiquant la valeur de cellule à utiliser pour le paramètre de requête. Utilisé uniquement lorsque parameterType est cell.|
| [value](/cells/python-net/fr/aspose.cells.externalconnections/connectionparameter/value) | Valeur numérique non entière, valeur entière, valeur de chaîne ou valeur booléenne<br/> à utiliser comme paramètre de requête. Utilisé uniquement lorsque parameterType est une valeur.|



###  Voir également
* module [`aspose.cells.externalconnections`](..)
