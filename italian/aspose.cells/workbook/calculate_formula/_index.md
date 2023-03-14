---
title: metodo calculate_formula
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 40
url: /it/aspose.cells/workbook/calculate_formula/
is_root: false
---
##  calculate_formula() {#}
Calcola il risultato delle formule.



```python
def calculate_formula(self):
    ...
```


###  Osservazioni

Per tutte le formule supportate, consultare l'elenco su https://docs.aspose.com/display/cellsnet/Supported+Formula+Functions

##  calculate_formula(ignore_error) {#bool}

Calcola il risultato delle formule.



```python
def calculate_formula(self, ignore_error):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| ignore_error | bool | Indica se nascondere l'errore nel calcolo delle formule. L'errore potrebbe essere una funzione non supportata, collegamenti esterni, ecc.|


##  calculate_formula(options) {#CalculationOptions}
Calcolo delle formule in questa cartella di lavoro.



```python
def calculate_formula(self, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| options | [CalculationOptions](/cells/python-net/it/aspose.cells/calculationoptions) | Opzioni per il calcolo|


##  calculate_formula(ignore_error, custom_function) {#bool-ICustomFunction}
Calcola il risultato delle formule.



```python
def calculate_formula(self, ignore_error, custom_function):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| ignore_error | bool | Indica se nascondere l'errore nel calcolo delle formule. L'errore potrebbe essere una funzione non supportata, collegamenti esterni, ecc.|
| custom_function | [ICustomFunction](/cells/python-net/it/aspose.cells/icustomfunction) | Il calcolo della formula personalizzata funziona per estendere il motore di calcolo.|
###  Osservazioni

NOTA: questo membro è ora obsoleto. Invece,
si prega di utilizzare il metodo CalculateFormula(CalculationOptions).
 Questo metodo verrà rimosso 12 mesi dopo da agosto 2020.
Aspose si scusa per gli eventuali disagi causati.


###  Guarda anche
* modulo [aspose.cells](../../)
* classe [Workbook](/cells/python-net/it/aspose.cells/workbook)
