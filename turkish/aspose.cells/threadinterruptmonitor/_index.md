---
title: ThreadInterruptMonitor sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1410
url: /tr/aspose.cells/threadinterruptmonitor/
is_root: false
---
##  ThreadInterruptMonitor sınıfı
Kullanıcı tarafından belirlenen uyku sınırından sonra kesintiyi gerektirecek başka bir iş parçacığı başlatarak AbstractInterruptMonitor'un basit uygulaması.



**Miras:** [`ThreadInterruptMonitor`](/cells/python-net/tr/aspose.cells/threadinterruptmonitor)



ThreadInterruptMonitor türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/tr/aspose.cells/threadinterruptmonitor/__init__/#bool) | Bir kesinti izleyicisi oluşturur.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_interruption_requested](/cells/python-net/tr/aspose.cells/threadinterruptmonitor/is_interruption_requested) | Bu uygulama sadece zaman maliyetinin (bu monitörün başlatıldığı andan itibaren şu ana kadar) kullanıcı tarafından belirlenen sınırdan büyük olup olmadığını kontrol eder.|
| [terminate_without_exception](/cells/python-net/tr/aspose.cells/threadinterruptmonitor/terminate_without_exception) |TerminateWithoutException'a bakın.<br/> Bu özellik, bu izleme örneği oluşturulurken kullanıcı tarafından belirtilir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/tr/aspose.cells/threadinterruptmonitor/start_monitor/#int) | Monitörü belirtilen zaman sınırıyla başlatır. Zaman maliyetini hesaplamanın başlangıç zamanı, bu yöntemin çağrıldığı zamandır.<br/> Dolayısıyla izlenmesi gereken prosedür bu çağrıdan hemen sonra başlatılmalıdır.|
| [`finish_monitor(self)`](/cells/python-net/tr/aspose.cells/threadinterruptmonitor/finish_monitor/#) | Bir prosedür için monitörü tamamlar.|



###  Notlar

Her bir işlemi sırayla izlediğiniz sürece, bir izleme örneği tekrar tekrar kullanılabilir.
Çoklu iş parçacıklarında birden fazla prosedürü aynı anda izlemek için kullanılmamalıdır.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`ThreadInterruptMonitor`](/cells/python-net/tr/aspose.cells/threadinterruptmonitor)
