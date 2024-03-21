---
title: Enumerazione CalculationPrecisionStrategy
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1890
url: /it/aspose.cells/calculationprecisionstrategy/
is_root: false
---
##  Enumerazione CalculationPrecisionStrategy
Enumera le strategie per gestire la precisione dei calcoli.
A causa del problema di precisione dell'aritmetica in virgola mobile IEEE 754, alcune formule "apparentemente semplici" potrebbero non essere calcolate come risultato previsto.
Come la formula "=-0,45+0,43+0,02", quando si calcolano direttamente gli operandi tramite l'operatore '+', il risultato non è zero. Per questo tipo di problema di precisione,
alcune strategie speciali possono dare il risultato atteso.



Il tipo CalculationPrecisionStrategy espone i seguenti membri:

###  Campi
| Campo| Descrizione|
| :- | :- |
| NONE | Nessuna strategia applicata al calcolo.<br/>Durante il calcolo è sufficiente utilizzare il valore double originale come operando e restituire direttamente il risultato.<br/> Il più efficiente per le prestazioni e applicabile nella maggior parte dei casi.|
| ROUND | Arrotonda il risultato del calcolo in base alle cifre significative.|
| DECIMAL |Utilizza i decimali come operandi quando possibile.<br/> Molto inefficiente per le prestazioni.|



###  Guarda anche
* modulo [`aspose.cells`](..)
