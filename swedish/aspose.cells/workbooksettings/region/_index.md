---
title: region fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 440
url: /sv/aspose.cells/workbooksettings/region/
is_root: false
---
##  region fastighet

Hämtar eller anger de regionala inställningarna för arbetsboken.

###  Anmärkningar

1. Regionala inställningar som används av Aspose.Cells-komponenten för en arbetsbok som laddats från en mallfil:
i). För en XLS-fil finns det definierade fält för regionala inställningar och MS Excel sparar regionala inställningsdata i filen när XLS-filen sparas.
Så använder vi den sparade region i mallfilen för arbetsboken.
Om du inte vill använda region som sparats i XLS-filen, återställ den till den förväntade värdet (t.ex. CountryCode.Default) efter att du har laddat mallfilen.
Och vi sparar det användarspecificerade värdet (med den här metoden) i filen också när vi sparar en XLS-fil.
ii). För andra filformat, såsom XLSX, XLSB...etc., finns inget fält definierat för regionala inställningar i filformatspecifikationen.
Så använder vi de regionala inställningarna för programmiljön för arbetsboken.
Och det användarspecificerade värdet (med den här metoden) kan inte behållas för de genererade filerna med dessa filformat.
2. För vyeffekten i MS Excel:
De tillämpade regionala inställningarna här kan endast träda i kraft vid körning med Aspose.Cells-komponenten och inte när den genererade filen visas med MS Excel.
Även för den genererade XLS-filen där de angivna regionala inställningsdatan har sparats, när den visas/redigeras med MS Excel,
Den använda region-filen för att formatera MS Excel är alltid de regionala standardinställningarna för den miljö där MS Excel körs.
inte den som sparats i filen. Det är MS Excels beteende och kan inte ändras med kod.
###  Definition:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`CountryCode`](/cells/python-net/sv/aspose.cells/countrycode)
* klass [`WorkbookSettings`](/cells/python-net/sv/aspose.cells/workbooksettings)
