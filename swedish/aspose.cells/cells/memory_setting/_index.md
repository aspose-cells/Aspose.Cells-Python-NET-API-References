---
title: memory_setting fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1160
url: /sv/aspose.cells/cells/memory_setting/
is_root: false
---
##  memory_setting fastighet

Hämtar eller ställer in minnesanvändningsalternativet för dessa celler.

###  Anmärkningar

Anmärkningsvärda begränsningar och rekommenderade åtgärder för vissa lägen:
| Läge| Anmärkningar| Stöds|
| :- | :- | :- |
|
 för att minska minneskostnaden. Å andra sidan kan den kompakta datan också
 orsaka högre tidskostnader, särskilt vid uppdatering av celldata,
 eller slumpmässig åtkomst till celler/rader| v8.0.0 |
|
 När det här läget används för ett kalkylblad i en arbetsbok, |
 bör anropas i slutet av arbetet för att frigöra alla resurser, såsom temporära filer.
            | 
 Slumpmässig åtkomst till celler ger dålig prestanda eftersom data behöver
 att läsas/uppdateras slumpmässigt och upprepade gånger (så att pekaren i filen kommer att vara
ändras i enlighet därmed och IO-operationer kommer att krävas upprepade gånger).
 Om möjligt, vänligen hämta alltid informationen sekventiellt (rad för rad).
            | 
 När data i en rad/cell ändras, ändras data i andra celler/rader
 kan också påverkas (till exempel att data flyttas till andra platser
 att allokera tillräckligt med utrymme för de ändrade uppgifterna).
 Så varje ändring av all data kräver synkronisering av andra befintliga objekt (
 såsom Rad eller Cell-objekt).
 Så, för att få bättre prestanda, vänligen underhåll inte flera rader/Cells
 samtidigt. Att bearbeta dem en efter en minskar datasynkroniseringen
 för dem så att prestandan kan förbättras lite.
 | v25.7 |
###  Definition:
```python
@property
def memory_setting(self):
    ...
@memory_setting.setter
def memory_setting(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
* klass [`MemorySetting`](/cells/python-net/sv/aspose.cells/memorysetting)
