---
title: ThreadInterruptMonitor classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1410
url: /fr/aspose.cells/threadinterruptmonitor/
is_root: false
---
##  ThreadInterruptMonitor classe
Implémentation simple de AbstractInterruptMonitor en démarrant un autre thread pour exiger l'interruption après la mise en veille de la limite spécifiée par l'utilisateur.



**Héritage:** [`ThreadInterruptMonitor`](/cells/python-net/fr/aspose.cells/threadinterruptmonitor)



Le type ThreadInterruptMonitor expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/fr/aspose.cells/threadinterruptmonitor/__init__/#bool) | Construit un moniteur d'interruption.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [is_interruption_requested](/cells/python-net/fr/aspose.cells/threadinterruptmonitor/is_interruption_requested) | Cette implémentation vérifie simplement si le coût en temps (à partir du moment où ce moniteur démarre jusqu'à maintenant) est supérieur à la limite spécifiée par l'utilisateur.|
| [terminate_without_exception](/cells/python-net/fr/aspose.cells/threadinterruptmonitor/terminate_without_exception) |Voir TerminateWithoutException.<br/> Cette propriété est spécifiée par l'utilisateur lors de la construction de cette instance de moniteur.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/fr/aspose.cells/threadinterruptmonitor/start_monitor/#int) | Démarre le moniteur avec la limite de temps spécifiée. Le temps de démarrage du calcul du coût est calculé au moment de l'appel de cette méthode.<br/> la procédure qui doit être surveillée doit donc être lancée juste après cet appel.|
| [`finish_monitor(self)`](/cells/python-net/fr/aspose.cells/threadinterruptmonitor/finish_monitor/#) | Termine le moniteur pour une procédure.|



###  Remarques

Une instance de moniteur peut être utilisée à plusieurs reprises, à condition que vous surveilliez chaque processus en séquence.
Il ne doit pas être utilisé pour surveiller plusieurs procédures simultanément dans plusieurs threads.

###  Voir également
* module [`aspose.cells`](..)
* classe [`ThreadInterruptMonitor`](/cells/python-net/fr/aspose.cells/threadinterruptmonitor)
