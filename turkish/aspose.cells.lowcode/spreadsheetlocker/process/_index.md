---
title: process yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---
##  process(, yükleme_seçenekleri, kaydetme_seçenekleri, sağlayıcı){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}
Belirtilen ayarlarla elektronik tablo dosyasını kilitler.



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodeloadoptions) | Giriş ve yükleme seçenekleri|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptions) | Çıktı ve kaydetme seçenekleri|
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/tr/aspose.cells.lowcode/abstractlowcodeprotectionprovider) | Koruma ayarlarını sağlamak için uygulama|


##  process(, şablon_dosyası, sonuç_dosyası, açık_şifre, yaz_şifresi){#str-str-str-str}
Belirtilen ayarlarla elektronik tablo dosyasını kilitler.



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| template_file | str | Kilitlenecek şablon dosyası|
| result_file | str | Ortaya çıkan dosya|
| open_password | str | Dosya şifrelemesi için parola|
| write_password | str |Elektronik tabloyu değiştirmeye karşı koruma için şifre|


##  process(, yükleme_seçenekleri, kaydetme_seçenekleri, açma_şifresi, yazma_şifresi){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}
Belirtilen ayarlarla elektronik tablo dosyasını kilitler.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodeloadoptions) | Giriş ve yükleme seçenekleri|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptions) | Çıktı ve kaydetme seçenekleri|
| open_password | str | Dosya şifrelemesi için parola|
| write_password | str |Elektronik tabloyu değiştirmeye karşı koruma için şifre|


##  process(, yükleme_seçenekleri, kaydetme_seçenekleri, açma_şifresi, yazma_şifresi, çalışma_kitabı_şifresi, çalışma_kitabı_türü){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}
Belirtilen ayarlarla elektronik tablo dosyasını kilitler.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodeloadoptions) | Giriş ve yükleme seçenekleri|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/tr/aspose.cells.lowcode/lowcodesaveoptions) | Çıktı ve kaydetme seçenekleri|
| open_password | str | Dosya şifrelemesi için parola|
| write_password | str |Elektronik tabloyu değiştirmeye karşı koruma için şifre|
| workbook_password | str | Çalışma kitabının korunması için şifre|
| workbook_type | [`ProtectionType`](/cells/python-net/tr/aspose.cells/protectiontype) | Çalışma kitabını korumak için koruma türü|



###  Ayrıca bakınız
* modül [`aspose.cells.lowcode`](../../)
* sınıf [`SpreadsheetLocker`](/cells/python-net/tr/aspose.cells.lowcode/spreadsheetlocker)
