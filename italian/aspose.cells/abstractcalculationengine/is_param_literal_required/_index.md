---
title: is_param_literal_required proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 50
url: /it/aspose.cells/abstractcalculationengine/is_param_literal_required/
is_root: false
---
##  is_param_literal_required proprietà

Indica se questo motore necessita del testo letterale del parametro durante l'esecuzione del calcolo. Il valore predefinito è falso.

###  Osservazioni

Se questo motore di calcolo personalizzato necessita del testo letterale del parametro,
saranno necessari più stack per memorizzare nella cache il testo letterale per i parametri
e il metodo Calculate() può essere chiamato ricorsivamente per calcolare il valore del parametro.
Generalmente il testo letterale non è necessario per il calcolo delle formule
e questa proprietà dovrebbe essere mantenuta su false affinché la maggior parte delle implementazioni ottengano prestazioni migliori.
###  Definizione:
```python
@property
def is_param_literal_required(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`AbstractCalculationEngine`](/cells/python-net/it/aspose.cells/abstractcalculationengine)
