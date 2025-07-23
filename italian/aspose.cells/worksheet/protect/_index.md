---
title: Metodo protect
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 220
url: /it/aspose.cells/worksheet/protect/
is_root: false
---
##  protect(self, type) {#aspose.cells.ProtectionType}
Protegge il foglio di lavoro.



```python

def protect(self, type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/it/aspose.cells/protectiontype) | Tipo di protezione.|
###  Osservazioni

Questo metodo protegge il foglio di lavoro senza password. Può essere utilizzato in tutte le versioni di Excel.

##  protect(self, type, password, old_password) {#aspose.cells.ProtectionType-str-str}

Protegge il foglio di lavoro.



```python

def protect(self, type, password, old_password):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/it/aspose.cells/protectiontype) | Tipo di protezione.|
| password | str | Password.|
| old_password | str | Se il foglio di lavoro è già protetto da password, fornire la vecchia password.<br/> In caso contrario, è possibile impostare un valore nullo o una stringa vuota su questo parametro.|
###  Osservazioni

Questo metodo può essere utilizzato in tutte le versioni del foglio di lavoro Excel.
###  Esempio


```python
from aspose.cells import ProtectionType, Workbook

# Instantiating a Workbook object
excel = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = excel.worksheets[0]
# Protecting the worksheet with a password
worksheet.protect(ProtectionType.ALL, "aspose", None)
# Saving the modified Excel file in default (that is Excel 20003) format
excel.save("output.xls")

```



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet)
