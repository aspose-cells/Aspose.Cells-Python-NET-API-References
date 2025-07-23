---
title: Enumerazione LookInType
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 2270
url: /it/aspose.cells/lookintype/
is_root: false
---
##  Enumerazione LookInType
Rappresenta l'aspetto nel tipo.



Il tipo LookInType espone i seguenti membri:

###  Campi
| Campo| Descrizione|
| :- | :- |
| FORMULAS | Trova l'oggetto cercato dalla formula ([`Cell.formula`](/cells/python-net/it/aspose.cells/cell#formula)) se la cella è formula,<br/>altrimenti cerca a partire dal valore originale della cella (lo stesso con [`LookInType.ORIGINAL_VALUES`](/cells/python-net/it/aspose.cells/lookintype#ORIGINAL_VALUES)).|
| VALUES | Trova l'oggetto dal valore originale della cella ([`Cell.value`](/cells/python-net/it/aspose.cells/cell#value))<br/> e valore formattato ([`Cell.string_value`](/cells/python-net/it/aspose.cells/cell#string_value)).|
| VALUES_EXCLUDE_FORMULA_CELL | Ignora le celle che contengono formule. Per le celle che non contengono formule,<br/> lo stesso vale per [`LookInType.VALUES`](/cells/python-net/it/aspose.cells/lookintype#VALUES).|
| COMMENTS | Trova l'oggetto solo a partire dal commento della cella. Ignora le celle senza commento.|
| ONLY_FORMULAS | Ignora le celle che non sono formule. Per le celle che sono formule,<br/> trova l'oggetto cercato dalla formula ([`Cell.formula`](/cells/python-net/it/aspose.cells/cell#formula)).|
| ORIGINAL_VALUES | Trova l'oggetto solo in base al valore originale della cella.|
| FORMATTED_VALUES | Trova l'oggetto solo dal valore formattato della cella ([`Cell.string_value`](/cells/python-net/it/aspose.cells/cell#string_value)).|



###  Guarda anche
* modulo [`aspose.cells`](..)
