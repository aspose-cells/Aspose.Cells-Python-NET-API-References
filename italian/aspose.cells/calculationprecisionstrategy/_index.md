---
title: Enumerazione CalculationPrecisionStrategy
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1790
url: /it/aspose.cells/calculationprecisionstrategy/
is_root: false
---
##  Enumerazione CalculationPrecisionStrategy
Elenca le strategie per gestire la precisione di calcolo.
A causa del problema di precisione dell'aritmetica in virgola mobile IEEE 754, alcune formule "apparentemente semplici" potrebbero non essere calcolate come risultato previsto.
Ad esempio, con la formula "=-0,45+0,43+0,02", calcolando gli operandi direttamente con l'operatore '+', il risultato non è zero. Per questo tipo di problema di precisione,
Alcune strategie speciali potrebbero dare i risultati attesi.



Il tipo CalculationPrecisionStrategy espone i seguenti membri:

###  Campi
| Campo| Descrizione|
| :- | :- |
| NONE | Nessuna strategia applicata al calcolo.<br/>Durante il calcolo, utilizzare semplicemente il valore double originale come operando e restituire direttamente il risultato.<br/> Più efficiente in termini di prestazioni e applicabile nella maggior parte dei casi.|
| ROUND | Arrotonda il risultato del calcolo in base alle cifre significative.|
| DECIMAL | Se possibile, utilizza i numeri decimali come operandi.<br/> Molto inefficiente in termini di prestazioni.|



###  Guarda anche
* modulo [`aspose.cells`](..)
