---
title: import_excel_file yöntemi
second_title: Aspose.Cells.GridJs for Python via .NET API Referanslar
description:
type: docs
weight: 110
url: /tr/aspose.cellsgridjs/gridjsworkbook/import_excel_file/
is_root: false
---
##  import_excel_file {#str}

Excel dosyasını dosya yolundan içe aktarır.



```python
def import_excel_file(self, file_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| file_name | str | Dosyanın tam yolu.|


##  import_excel_file {#str-str}

Excel dosyasını dosya yolundan içe aktarır.



```python
def import_excel_file(self, uid, file_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| uid | str | Dosya önbelleğinin benzersiz kimliği boş olarak ayarlanırsa otomatik olarak oluşturulur.|
| file_name | str | Dosyanın tam yolu.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Excel dosyasını yükleme formatıyla dosya akışından içe aktarır.



```python
def import_excel_file(self, filestream, format):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| filestream | io.RawIOBase | Excel dosyasının akışı.|
| format | [`GridLoadFormat`](/cells/python-net/tr/aspose.cellsgridjs/gridloadformat) | Excel dosyasının LoadFormat'ı.|


##  import_excel_file {#str-str-str}

Excel dosyasını dosya yolundan ve açık paroladan içe aktarır.



```python
def import_excel_file(self, uid, file_name, password):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| uid | str | Dosya önbelleğinin benzersiz kimliği boş olarak ayarlanırsa otomatik olarak oluşturulur.|
| file_name | str | Dosyanın tam yolu.|
| password | str | Excel dosyasının açık şifresi. Herhangi bir şifre ayarlanmamışsa değer null olabilir.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Excel dosyasını dosya akışından içe aktarır.



```python
def import_excel_file(self, uid, filestream, format):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| uid | str | Dosya önbelleğinin benzersiz kimliği boş olarak ayarlanırsa otomatik olarak oluşturulur.|
| filestream | io.RawIOBase | Excel dosyasının akışı.|
| format | [`GridLoadFormat`](/cells/python-net/tr/aspose.cellsgridjs/gridloadformat) | Excel dosyasının LoadFormat'ı.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Excel dosyasını yükleme biçimi ve açma parolasıyla dosya akışından içe aktarır.



```python
def import_excel_file(self, filestream, format, password):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| filestream | io.RawIOBase | Excel dosyasının akışı.|
| format | [`GridLoadFormat`](/cells/python-net/tr/aspose.cellsgridjs/gridloadformat) | Excel dosyasının LoadFormat'ı.|
| password | str | Excel dosyasının açık şifresi. Herhangi bir şifre ayarlanmamışsa değer null olabilir.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Excel dosyasını yükleme biçimi ve açma parolasıyla dosya akışından içe aktarır.



```python
def import_excel_file(self, uid, filestream, format, password):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| uid | str | Dosya önbelleğinin benzersiz kimliği boş olarak ayarlanırsa otomatik olarak oluşturulur.|
| filestream | io.RawIOBase | Excel dosyasının akışı.|
| format | [`GridLoadFormat`](/cells/python-net/tr/aspose.cellsgridjs/gridloadformat) | Excel dosyasının LoadFormat'ı.|
| password | str | Excel dosyasının açık şifresi. Herhangi bir şifre ayarlanmadıysa değer null olabilir|



###  Ayrıca bakınız
* modül [`aspose.cellsgridjs`](../../)
* sınıf [`GridJsWorkbook`](/cells/python-net/tr/aspose.cellsgridjs/gridjsworkbook)
