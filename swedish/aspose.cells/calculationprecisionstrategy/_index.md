---
title: CalculationPrecisionStrategy uppräkning
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1790
url: /sv/aspose.cells/calculationprecisionstrategy/
is_root: false
---
##  CalculationPrecisionStrategy uppräkning
Räknar upp strategier för att hantera beräkningsprecision.
På grund av precisionsproblemet med IEEE 754 Flyttalsaritmetik kan vissa "till synes enkla" formler eventuellt inte beräknas som förväntat resultat.
Till exempel i formeln "=-0,45+0,43+0,02", när man beräknar operander direkt med operatorn '+', blir resultatet inte noll. För den här typen av precisionsproblem,
vissa speciella strategier kan ge det förväntade resultatet.



Typen CalculationPrecisionStrategy avslöjar följande medlemmar:

###  Fält
| Fält| Beskrivning|
| :- | :- |
| NONE | Ingen strategi tillämpad på beräkningen.<br/>Vid beräkningar, använd bara det ursprungliga double-värdet som operand och returnera resultatet direkt.<br/> Mest effektiv för prestanda och tillämplig i de flesta fall.|
| ROUND | Avrundar beräkningsresultatet med signifikanta siffror.|
| DECIMAL | Använder decimaltal som operander när det är möjligt.<br/> Mest ineffektiv för prestanda.|



###  Se även
* modul [`aspose.cells`](..)
