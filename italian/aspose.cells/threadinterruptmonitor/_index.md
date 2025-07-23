---
title: ThreadInterruptMonitor classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1410
url: /it/aspose.cells/threadinterruptmonitor/
is_root: false
---
##  ThreadInterruptMonitor classe
Semplice implementazione di AbstractInterruptMonitor mediante l'avvio di un altro thread per richiedere l'interruzione dopo il limite di sospensione specificato dall'utente.



**Eredità:** [`ThreadInterruptMonitor`](/cells/python-net/it/aspose.cells/threadinterruptmonitor)



Il tipo ThreadInterruptMonitor espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/it/aspose.cells/threadinterruptmonitor/__init__/#bool) | Costruisce un monitor di interruzione.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [is_interruption_requested](/cells/python-net/it/aspose.cells/threadinterruptmonitor/is_interruption_requested) | Questa implementazione controlla semplicemente se il costo temporale (dal momento in cui si avvia il monitor a adesso) è maggiore del limite specificato dall'utente.|
| [terminate_without_exception](/cells/python-net/it/aspose.cells/threadinterruptmonitor/terminate_without_exception) |Vedere TerminateWithoutException.<br/> Questa proprietà viene specificata dall'utente durante la creazione di questa istanza del monitor.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/it/aspose.cells/threadinterruptmonitor/start_monitor/#int) | Avvia il monitor con il limite di tempo specificato. L'ora di inizio per calcolare il costo del tempo è proprio quella in cui viene chiamato questo metodo.<br/> quindi la procedura da monitorare dovrebbe essere avviata subito dopo questa chiamata.|
| [`finish_monitor(self)`](/cells/python-net/it/aspose.cells/threadinterruptmonitor/finish_monitor/#) | Termina il monitoraggio per una procedura.|



###  Osservazioni

Un'istanza del monitor può essere utilizzata ripetutamente, a patto che si monitorino tutti i processi in sequenza.
Non dovrebbe essere utilizzato per monitorare più procedure contemporaneamente in multi-thread.

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`ThreadInterruptMonitor`](/cells/python-net/it/aspose.cells/threadinterruptmonitor)
