---
title: Metered klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 980
url: /sv/aspose.cells/metered/
is_root: false
---
##  Metered klass
Tillhandahåller metoder för att ställa in mätad nyckel.



Typen Metered avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/metered/__init__/#) | Initierar en ny instans av den här klassen.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/cells/python-net/sv/aspose.cells/metered/set_metered_key/#str-str) | Ställer in uppmätt offentlig och privat nyckel.<br/>Om du köper en mätlicens bör API ringas när du startar ansökan, normalt räcker detta.<br/> Om det dock alltid misslyckas med att ladda upp förbrukningsdata och det tar mer än 24 timmar, kommer licensen att ställas in på utvärderingsstatus.<br/> För att undvika ett sådant fall bör du regelbundet kontrollera licensstatusen. Om det är utvärderingsstatus, ring API igen.|
| [`get_consumption_quantity()`](/cells/python-net/sv/aspose.cells/metered/get_consumption_quantity/#) | Hämtar förbrukningsfilstorlek|
| [`get_consumption_credit()`](/cells/python-net/sv/aspose.cells/metered/get_consumption_credit/#) | Får konsumtionskredit|
| [`get_product_name(self)`](/cells/python-net/sv/aspose.cells/metered/get_product_name/#) | Hämtar produktnamn|
| [`is_metered_licensed()`](/cells/python-net/sv/aspose.cells/metered/is_metered_licensed/#) | Kontrollera om mätaren är licensierad|



###  Exempel

I det här exemplet kommer ett försök att ställa in uppmätta offentliga och privata nycklar


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Se även
* modul [`aspose.cells`](..)
