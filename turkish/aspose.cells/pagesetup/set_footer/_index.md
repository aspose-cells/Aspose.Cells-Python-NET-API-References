---
title: set_footer yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 180
url: /tr/aspose.cells/pagesetup/set_footer/
is_root: false
---
##  set_footer(self, section, footer_script) {#int-str}
Bir Excel dosyasının alt bilgisini biçimlendiren bir betik ayarlar.



```python

def set_footer(self, section, footer_script):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| section | int |0: Sol Bölüm, 1: Orta Bölüm, 2: Sağ Bölüm.|
| footer_script | str | Altbilgi format betiği.|
###  Notlar

Komut dosyası komutları:

| Emretmek| Tanım|
| :- | :- |
| &P| Geçerli sayfa numarası|
| &N| Sayfa sayısı|
| &D| Güncel tarih|
| &T| Şu anki zaman|
| &A| Sayfa adı|
| &F| Yol bilgisi olmayan dosya adı|
| &"<FontName>"|Yazı tipi adı, örneğin: &"Arial"|
| &"<FontName>, <FontStyle>"| Yazı tipi adı ve yazı tipi stili, örneğin: &"Arial,Bold"|
| &<FontSize>| Yazı tipi boyutu. Bu komutun ardından başlıkta yazdırılacak düz bir sayı gelirse, bu sayı yazı tipi yüksekliğinden bir boşluk karakteriyle ayrılır.|
| &K<RRGGBB>| Yazı tipi rengi, örneğin(KIRMIZI): &KFF0000|
| &G| Görüntü betiği|

Örneğin: "&Arial,Bold&8Footer Note"


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`PageSetup`](/cells/python-net/tr/aspose.cells/pagesetup)
