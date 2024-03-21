---
title: AbstractCalculationEngine classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 20
url: /it/aspose.cells/abstractcalculationengine/
is_root: false
---
##  AbstractCalculationEngine classe
Rappresenta il motore di calcolo personalizzato dell'utente per estendere il motore di calcolo predefinito di Aspose.Cells.



Il tipo AbstractCalculationEngine espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [is_param_literal_required](/cells/python-net/it/aspose.cells/abstractcalculationengine/is_param_literal_required) |Indica se questo motore necessita del testo letterale del parametro durante l'esecuzione del calcolo. Il valore predefinito è falso.|
| [is_param_array_mode_required](/cells/python-net/it/aspose.cells/abstractcalculationengine/is_param_array_mode_required) | Indica se questo motore necessita che il parametro venga calcolato in modalità array. Il valore predefinito è falso.<br/>Se [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/it/aspose.cells/calculationdata/get_param_value_in_array_mode) è richiesto nel calcolo personalizzato<br/>funzioni e l'utente non ha aggiornato la loro definizione<br/>(tramite [`Workbook.update_custom_function_definition`](/cells/python-net/it/aspose.cells/workbook/update_custom_function_definition)),<br/> questa proprietà deve essere impostata come true.|
| [process_built_in_functions](/cells/python-net/it/aspose.cells/abstractcalculationengine/process_built_in_functions) | Se le funzioni integrate sono state supportate dal motore integrato<br/>dovrebbero essere controllati ed elaborati da questa implementazione.<br/> L'impostazione predefinita è falsa.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [calculate](/cells/python-net/it/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) | Calcola una funzione con dati forniti.|



###  Osservazioni

L'utente non deve modificare alcuna parte della cartella di lavoro direttamente in questa implementazione (eccetto
il risultato calcolato della funzione personalizzata, che può essere impostato dalla proprietà CalculationData.CalculatedValue).
In caso contrario si potrebbero verificare risultati imprevisti o eccezioni.
Se l'utente deve modificare altri dati rispetto a quelli calcolati risulta nell'implementazione di alcune funzioni personalizzate,
ad esempio, modifica la formula, lo stile, ecc. della cella, l'utente deve raccogliere tali dati in questa implementazione
e modificarli fuori dall'ambito del calcolo della formula.

###  Guarda anche
* modulo [`aspose.cells`](..)
