---
title: ConnectionParameter klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cells.externalconnections/connectionparameter/
is_root: false
---
##  ConnectionParameter klass
Anger egenskaper för alla parametrar som används med externa dataanslutningar
Parametrar är giltiga för ODBC- och webbfrågor.



Typen ConnectionParameter avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [sql_type](/cells/python-net/sv/aspose.cells.externalconnections/connectionparameter/sql_type) | Parameterns SQL-datatyp. Gäller endast för ODBC-källor.|
| [refresh_on_change](/cells/python-net/sv/aspose.cells.externalconnections/connectionparameter/refresh_on_change) | Flagga som anger om frågan ska uppdateras automatiskt när innehållet i en<br/> cell som anger parametervärdet ändras. Om sant uppdateras externa data<br/> använder det nya parametervärdet varje gång det sker en ändring. Om falskt, då externa data<br/> uppdateras bara när användaren begär det, eller när någon annan händelse utlöser uppdatering (t.ex. arbetsboken öppnas).|
| [prompt](/cells/python-net/sv/aspose.cells.externalconnections/connectionparameter/prompt) | Frågsträng för parametern. Presenteras för kalkylbladsanvändaren tillsammans med inmatningsgränssnittet.<br/> för att samla in parametervärdet innan externa data uppdateras. Används endast när<br/>parameterTyp = prompt.|
| [type](/cells/python-net/sv/aspose.cells.externalconnections/connectionparameter/type) | Typ av parameter som används.<br/> Om parameterType=value, då värdet från booleskt, dubbelt, heltal,<br/> eller sträng kommer att användas. I det här fallet förväntas det att endast en av<br/> {boolean, double, integer eller sträng} kommer att anges.|
| [name](/cells/python-net/sv/aspose.cells.externalconnections/connectionparameter/name) | Parameterns namn.|
| [cell_reference](/cells/python-net/sv/aspose.cells.externalconnections/connectionparameter/cell_reference) | Cell-referens som anger vilken cells värde som ska användas för frågeparametern. Används endast när parameterType är cell.|
| [value](/cells/python-net/sv/aspose.cells.externalconnections/connectionparameter/value) | Numeriskt värde som inte är heltal, heltalsvärde, strängvärde eller booleskt värde<br/> att använda som frågeparameter. Används endast när parameterType är ett värde.|



###  Se även
* modul [`aspose.cells.externalconnections`](..)
