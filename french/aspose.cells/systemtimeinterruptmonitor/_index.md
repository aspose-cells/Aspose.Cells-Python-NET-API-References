---
title: SystemTimeInterruptMonitor classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1390
url: /fr/aspose.cells/systemtimeinterruptmonitor/
is_root: false
---
##  SystemTimeInterruptMonitor classe
Implémentation simple d'AbstractInterruptMonitor en vérifiant et en comparant l'heure système actuelle avec la limite spécifiée par l'utilisateur.



**Héritage:** [`SystemTimeInterruptMonitor`](/cells/python-net/fr/aspose.cells/systemtimeinterruptmonitor)



Le type SystemTimeInterruptMonitor expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/fr/aspose.cells/systemtimeinterruptmonitor/__init__/#bool) | Construit un moniteur d'interruption.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [is_interruption_requested](/cells/python-net/fr/aspose.cells/systemtimeinterruptmonitor/is_interruption_requested) | Cette implémentation vérifie simplement si le coût en temps (à partir du moment où ce moniteur démarre jusqu'à maintenant) est supérieur à la limite spécifiée par l'utilisateur.|
| [terminate_without_exception](/cells/python-net/fr/aspose.cells/systemtimeinterruptmonitor/terminate_without_exception) |Voir TerminateWithoutException.<br/> Cette propriété est spécifiée par l'utilisateur lors de la construction de cette instance de moniteur.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/fr/aspose.cells/systemtimeinterruptmonitor/start_monitor/#int) | Démarre le moniteur avec la limite de temps spécifiée. Le temps de démarrage du calcul du coût est calculé au moment de l'appel de cette méthode.<br/> la procédure qui doit être surveillée doit donc être lancée juste après cet appel.|



###  Remarques

Cette implémentation n’est qu’une solution simple pour des scénarios simples.
Il doit fréquemment récupérer et vérifier l'heure du système, ce qui peut avoir un impact négatif sur les performances dans une certaine mesure.

###  Voir également
* module [`aspose.cells`](..)
* classe [`SystemTimeInterruptMonitor`](/cells/python-net/fr/aspose.cells/systemtimeinterruptmonitor)
