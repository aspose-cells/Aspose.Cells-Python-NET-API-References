---
title: RenameStrategy énumération
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 2490
url: /fr/aspose.cells/renamestrategy/
is_root: false
---
##  RenameStrategy énumération
Option de stratégie pour les noms de colonnes en double.



Le type RenameStrategy expose les membres suivants :

###  Des champs
| Champ| Description|
| :- | :- |
| EXCEPTION | Lève une exception.|
| DIGIT | Nommé avec un chiffre. Les noms dupliqués deviendront… 1,… 2, etc.|
| LETTER | Nommé avec une lettre. Les noms en double deviendront ...A, ...B, etc.|



###  Remarques

Lors du traitement de données avec des en-têtes, certains scénarios nécessitent que les en-têtes ne soient pas dupliqués pour toutes les colonnes.
Par exemple, lors de l'exportation de données vers une table de données et que l'en-tête doit être considéré comme le nom de colonne de la table de données,
les valeurs dupliquées de l'en-tête ne sont pas valides.
Pour ce genre de situations, l'utilisateur peut déterminer comment les gérer en spécifiant cette stratégie.

###  Voir également
* module [`aspose.cells`](..)
