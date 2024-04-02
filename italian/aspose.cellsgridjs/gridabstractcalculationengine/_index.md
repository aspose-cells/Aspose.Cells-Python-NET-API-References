---
title: GridAbstractCalculationEngine classe
second_title: Aspose.Cells.GridJs for Python via .NET API Referenze
description:
type: docs
weight: 20
url: /it/aspose.cellsgridjs/gridabstractcalculationengine/
is_root: false
---
##  GridAbstractCalculationEngine classe

Rappresenta il motore di calcolo personalizzato dell'utente per estendere il motore di calcolo predefinito di Aspose.Cells.



Il tipo GridAbstractCalculationEngine espone i seguenti membri:

###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [calculate](/cells/python-net/it/aspose.cellsgridjs/gridabstractcalculationengine/calculate/#aspose.cellsgridjs.GridCalculationData) | Calcola una funzione con dati forniti.|



###  Osservazioni


L'utente non deve modificare alcuna parte della cartella di lavoro direttamente in questa implementazione (eccetto il risultato calcolato della funzione personalizzata, che può essere impostato dalla proprietà GridCalculationData.CalculatedValue).
In caso contrario si potrebbero verificare risultati imprevisti o eccezioni.
Se l'utente deve modificare altri dati rispetto a quelli calcolati risulta nell'implementazione di alcune funzioni personalizzate,
Ad esempio, modificando la formula, lo stile, ecc. della cella, l'utente deve raccogliere tali dati in questa implementazione e modificarli fuori dall'ambito del calcolo della formula.

###  Guarda anche
* modulo [`aspose.cellsgridjs`](..)
