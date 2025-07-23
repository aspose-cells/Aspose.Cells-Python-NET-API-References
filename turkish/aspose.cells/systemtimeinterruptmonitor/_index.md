---
title: SystemTimeInterruptMonitor sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1390
url: /tr/aspose.cells/systemtimeinterruptmonitor/
is_root: false
---
##  SystemTimeInterruptMonitor sınıfı
AbstractInterruptMonitor'un mevcut sistem zamanını kullanıcı tarafından belirlenen sınırla kontrol edip karşılaştırarak basit bir şekilde uygulanması.



**Miras:** [`SystemTimeInterruptMonitor`](/cells/python-net/tr/aspose.cells/systemtimeinterruptmonitor)



SystemTimeInterruptMonitor türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/tr/aspose.cells/systemtimeinterruptmonitor/__init__/#bool) | Bir kesinti izleyicisi oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_interruption_requested](/cells/python-net/tr/aspose.cells/systemtimeinterruptmonitor/is_interruption_requested) | Bu uygulama sadece zaman maliyetinin (bu monitörün başlatıldığı andan itibaren şu ana kadar) kullanıcı tarafından belirlenen sınırdan büyük olup olmadığını kontrol eder.|
| [terminate_without_exception](/cells/python-net/tr/aspose.cells/systemtimeinterruptmonitor/terminate_without_exception) |TerminateWithoutException'a bakın.<br/> Bu özellik, bu izleme örneği oluşturulurken kullanıcı tarafından belirtilir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/tr/aspose.cells/systemtimeinterruptmonitor/start_monitor/#int) | Monitörü belirtilen zaman sınırıyla başlatır. Zaman maliyetini hesaplamanın başlangıç zamanı, bu yöntemin çağrıldığı zamandır.<br/> Dolayısıyla izlenmesi gereken prosedür bu çağrıdan hemen sonra başlatılmalıdır.|



###  Notlar

Bu uygulama basit senaryolar için basit bir çözümdür.
Sistem saatini sık sık alıp kontrol etmesi gerektiğinden, performans üzerinde bir miktar olumsuz etkisi olabilir.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`SystemTimeInterruptMonitor`](/cells/python-net/tr/aspose.cells/systemtimeinterruptmonitor)
