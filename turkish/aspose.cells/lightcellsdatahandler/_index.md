---
title: LightCellsDataHandler sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1030
url: /tr/aspose.cells/lightcellsdatahandler/
is_root: false
---
##  LightCellsDataHandler sınıfı
Büyük elektronik tablo dosyalarını hafif modda okumak için hücre veri işleyicisini temsil eder.



LightCellsDataHandler türü aşağıdaki üyeleri ortaya çıkarır:

###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [start_sheet](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/start_sheet/#aspose.cells.Worksheet) | Bir çalışma sayfasını işlemeye başlar.|
| [start_row](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/start_row/#int) | Bir satırı işlemeye hazırlanır.|
| [process_row](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/process_row/#aspose.cells.Row) | Bir satırı işlemeye başlar.|
| [start_cell](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/start_cell/#int) | Bir hücreyi işlemeye hazırlanır.|
| [process_cell](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/process_cell/#aspose.cells.Cell) | Bir hücreyi işlemeye başlar.|



###  Notlar

Bu modda bir çalışma kitabı okurken, çalışma kitabındaki her çalışma sayfasını okurken [`LightCellsDataHandler.start_sheet`](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/start_sheet) işaretlenecektir.
Bir sayfa için, [`LightCellsDataHandler.start_sheet`](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/start_sheet) doğru verirse, bu sayfanın satır/hücrelerinin tüm verileri ve özellikleri kontrol edilecektir.
ve bu arayüzün uygulanmasıyla işlenir. Her satır için, işlenmesi gerekip gerekmediğini kontrol etmek için [`LightCellsDataHandler.start_row`](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/start_row) çağrılacaktır.
Bir satırın işlenmesi gerekiyorsa öncelikle bu satırın özellikleri okunacak ve kullanıcı [`LightCellsDataHandler.process_row`](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/process_row) numaralı telefondan bu satırın özelliklerine ulaşabilecektir.
satırın hücrelerinin de işlenmesi gerekiyorsa, [`LightCellsDataHandler.process_row`](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/process_row) true değerini döndürmelidir ve ardından [`LightCellsDataHandler.start_cell`](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/start_cell) olacaktır.
Bir hücrenin işlenmesi gerekip gerekmediğini kontrol etmek için bu satırdaki her mevcut hücreyi çağırdı. Bir hücrenin işlenmesi gerekiyorsa,
daha sonra bu arayüzün uygulanmasıyla hücreyi işlemek için [`LightCellsDataHandler.process_cell`](/cells/python-net/tr/aspose.cells/lightcellsdatahandler/process_cell) çağrılacaktır.


Kullanıcının yalnızca ilgili yöntemle sağlanan geçerli Row/Cell nesnesinin değerleri ve özellikleri üzerinde işlem yapması gerektiğini lütfen unutmayın.
Hücre verileri şablon dosyasından akış halinde okunduğu için diğer nesnelerin çoğu daha sonra sıfırlanabilir/güncellenebilir
Hücre verileri yüklendikten sonra. Yani kullanıcı bu uygulamada diğer nesneleri çalıştırırken,
bu işlemler çalışma kitabında bulunan nesneleri etkilemeyebilir. Daha da kötüsü, bu operasyonlar
çalışma kitabında tutarsız verilere neden olur ve daha sonra beklenmeyen soruna veya özel duruma neden olur.
Yani şekiller, sütun genişliği ve stilleri, koşullu biçimlendirmeler vb. gibi diğer tüm nesneler için,
lütfen bunları bu uygulamanın herhangi bir yönteminde çalıştırmayın.
Bunun yerine lütfen bunları çalışma kitabı oluşturulduktan sonra yönetin.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
