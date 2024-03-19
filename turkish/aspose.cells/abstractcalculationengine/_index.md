---
title: AbstractCalculationEngine sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/abstractcalculationengine/
is_root: false
---
##  AbstractCalculationEngine sınıfı
Aspose.Cells varsayılan hesaplama motorunu genişletmek için kullanıcının özel hesaplama motorunu temsil eder.



AbstractCalculationEngine türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_param_literal_required](/cells/python-net/tr/aspose.cells/abstractcalculationengine/is_param_literal_required) |Bu motorun hesaplama yaparken parametrenin tam metnine ihtiyacı olup olmadığını gösterir. Varsayılan değer false'tur.|
| [is_param_array_mode_required](/cells/python-net/tr/aspose.cells/abstractcalculationengine/is_param_array_mode_required) | Bu motorun dizi modunda hesaplanması için parametreye ihtiyacı olup olmadığını gösterir. Varsayılan değer false'tur.<br/>Özel hesaplama yaparken [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/tr/aspose.cells/calculationdata/get_param_value_in_array_mode) gerekiyorsa<br/>işlevler ve kullanıcı bunların tanımını güncellemedi<br/>([`Workbook.update_custom_function_definition`](/cells/python-net/tr/aspose.cells/workbook/update_custom_function_definition) tarafından),<br/> bu özelliğin true olarak ayarlanması gerekiyor.|
| [process_built_in_functions](/cells/python-net/tr/aspose.cells/abstractcalculationengine/process_built_in_functions) | Yerleşik motor tarafından desteklenen yerleşik işlevlerin olup olmadığı<br/>Bu uygulama tarafından kontrol edilmeli ve işlenmelidir.<br/> Varsayılan yanlıştır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [calculate](/cells/python-net/tr/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) | Verilen verilerle bir fonksiyonu hesaplar.|



###  Notlar

Kullanıcı, Çalışma Kitabının herhangi bir bölümünü doğrudan bu uygulamada değiştirmemelidir (hariç
CalculationData.CalculatedValue özelliği tarafından ayarlanabilen özel işlevin hesaplanan sonucu).
Aksi takdirde beklenmeyen bir sonuç veya İstisna meydana gelebilir.
Kullanıcının bazı özel işlevler için uygulamada hesaplanan sonuçtan başka verileri değiştirmesi gerekiyorsa,
örneğin, hücrenin formülünü, stilini vb. değiştirin, kullanıcının bu verileri bu uygulamada toplaması gerekir
ve bunları formül hesaplamasının kapsamı dışında değiştirin.

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
