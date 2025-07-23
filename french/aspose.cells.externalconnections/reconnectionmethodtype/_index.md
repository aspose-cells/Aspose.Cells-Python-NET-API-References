---
title: ReConnectionMethodType énumération
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 130
url: /fr/aspose.cells.externalconnections/reconnectionmethodtype/
is_root: false
---
##  ReConnectionMethodType énumération
Spécifie ce que l’application de feuille de calcul doit faire lorsqu’une connexion échoue.



Le type ReConnectionMethodType expose les membres suivants :

###  Des champs
| Champ| Description|
| :- | :- |
| REQUIRED | Lors de l'actualisation, utilisez les informations de connexion existantes et si elles s'avèrent invalides<br/> puis obtenez les informations de connexion mises à jour, si elles sont disponibles à partir du fichier de connexion externe.|
| ALWAYS | À chaque actualisation, obtenez des informations de connexion mises à jour à partir du fichier de connexion externe,<br/> si disponible, et utilisez-les à la place des informations de connexion existantes.<br/>Dans ce cas, l'actualisation des données échouera si le fichier de connexion externe n'est pas disponible.|
| NEVER | Ne jamais obtenir d'informations de connexion mises à jour à partir du fichier de connexion externe<br/> même s'il est disponible et même si les informations de connexion existantes ne sont pas valides|



###  Voir également
* module [`aspose.cells.externalconnections`](..)
