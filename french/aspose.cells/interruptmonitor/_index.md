---
title: InterruptMonitor classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 990
url: /fr/aspose.cells/interruptmonitor/
is_root: false
---
##  InterruptMonitor classe
Représente tous les opérateurs concernant l'interruption.



**Héritage:** [`InterruptMonitor`](/cells/python-net/aspose.cells/interruptmonitor) → 
[`AbstractInterruptMonitor`](/cells/python-net/fr/aspose.cells/abstractinterruptmonitor)



Le type InterruptMonitor expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/interruptmonitor/__init__/#) | Construit une nouvelle instance d'InterruptMonitor|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [is_interruption_requested](/cells/python-net/fr/aspose.cells/interruptmonitor/is_interruption_requested) | Marquer le moniteur comme demandant une interruption|
| [terminate_without_exception](/cells/python-net/fr/aspose.cells/interruptmonitor/terminate_without_exception) | Lorsque la procédure est interrompue, terminez-la tranquillement ou lancez une exception.<br/>La valeur par défaut est false, c'est-à-dire lorsque [`AbstractInterruptMonitor.is_interruption_requested`](/cells/python-net/fr/aspose.cells/abstractinterruptmonitor#is_interruption_requested) est vrai,<br/> un [`CellsException`](/cells/python-net/fr/aspose.cells/cellsexception) avec le code [`ExceptionType.INTERRUPTED`](/cells/python-net/fr/aspose.cells/exceptiontype#INTERRUPTED) sera lancé.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [interrupt](/cells/python-net/fr/aspose.cells/interruptmonitor/interrupt/#) | Interrompre l'opérateur actuel.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`AbstractInterruptMonitor`](/cells/python-net/fr/aspose.cells/abstractinterruptmonitor)
* classe [`CellsException`](/cells/python-net/fr/aspose.cells/cellsexception)
* classe [`InterruptMonitor`](/cells/python-net/fr/aspose.cells/interruptmonitor)
