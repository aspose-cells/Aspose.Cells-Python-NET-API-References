---
title: CalculationOptions classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 100
url: /it/aspose.cells/calculationoptions/
is_root: false
---
##  CalculationOptions classe
Rappresenta le opzioni per il calcolo.



Il tipo CalculationOptions espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/calculationoptions/__init__/#) | Costruisce una nuova istanza di CalculationOptions|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [ignore_error](/cells/python-net/it/aspose.cells/calculationoptions/ignore_error) | Indica se gli errori riscontrati durante il calcolo delle formule devono essere ignorati.<br/>L'errore potrebbe essere dovuto a una funzione non supportata, a link esterni, ecc.<br/> Il valore predefinito è vero.|
| [recursive](/cells/python-net/it/aspose.cells/calculationoptions/recursive) | Indica se calcolare le celle dipendenti in modo ricorsivo quando si calcola una cella e questa dipende da altre celle.<br/> Il valore predefinito è vero.|
| [calc_stack_size](/cells/python-net/it/aspose.cells/calculationoptions/calc_stack_size) | La dimensione dello stack per il calcolo ricorsivo delle celle. Il valore predefinito è 200.|
| [precision_strategy](/cells/python-net/it/aspose.cells/calculationoptions/precision_strategy) | Specifica la strategia per l'elaborazione della precisione di calcolo.|
| [linked_data_sources](/cells/python-net/it/aspose.cells/calculationoptions/linked_data_sources) | Specifica le origini dati per i collegamenti esterni utilizzati nelle formule.|
| [character_encoding](/cells/python-net/it/aspose.cells/calculationoptions/character_encoding) | Specifica la codifica utilizzata per codificare/decodificare i caratteri durante il calcolo delle formule.<br/>Per funzioni quali CHAR, CODE, il risultato calcolato dipende dalle impostazioni della regione e dal set di caratteri predefinito dell'ambiente.<br/>Con questa proprietà l'utente può specificare la codifica corretta da utilizzare per le funzioni per ottenere il risultato previsto.|



###  Guarda anche
* modulo [`aspose.cells`](..)
