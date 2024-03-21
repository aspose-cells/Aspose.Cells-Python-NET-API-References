---
title: InterruptMonitor sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 990
url: /tr/aspose.cells/interruptmonitor/
is_root: false
---
##  InterruptMonitor sınıfı
Kesmeyle ilgili tüm operatörleri temsil eder.



**Miras:** [`InterruptMonitor`](/cells/python-net/aspose.cells/interruptmonitor) → 
[`AbstractInterruptMonitor`](/cells/python-net/tr/aspose.cells/abstractinterruptmonitor)



InterruptMonitor türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/interruptmonitor/__init__/#) | InterruptMonitor'un yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_interruption_requested](/cells/python-net/tr/aspose.cells/interruptmonitor/is_interruption_requested) | Monitörü kesinti talep ediyor olarak işaretleyin|
| [terminate_without_exception](/cells/python-net/tr/aspose.cells/interruptmonitor/terminate_without_exception) | Prosedür kesintiye uğradığında, prosedürü sessizce sonlandırın veya bir İstisna atın.<br/>Varsayılan yanlıştır, yani [`AbstractInterruptMonitor.is_interruption_requested`](/cells/python-net/tr/aspose.cells/abstractinterruptmonitor#is_interruption_requested) doğru olduğunda,<br/> [`ExceptionType.INTERRUPTED`](/cells/python-net/tr/aspose.cells/exceptiontype#INTERRUPTED) kodlu bir [`CellsException`](/cells/python-net/tr/aspose.cells/cellsexception) atılacak.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [interrupt](/cells/python-net/tr/aspose.cells/interruptmonitor/interrupt/#) | Geçerli operatörün sözünü kesin.|



###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`AbstractInterruptMonitor`](/cells/python-net/tr/aspose.cells/abstractinterruptmonitor)
* sınıf [`CellsException`](/cells/python-net/tr/aspose.cells/cellsexception)
* sınıf [`InterruptMonitor`](/cells/python-net/tr/aspose.cells/interruptmonitor)
