---
title: process metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.lowcode/imageconverter/process/
is_root: false
---
##  process(, mallfil, resultatfil){#str-str}
Konverterar mallfil till bilder.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| template_file | str | Mallfilen som ska konverteras till bilder.|
| result_file | str | Den resulterande filen (namnmönster) för genererade bilder.|
###  Anmärkningar

Utdatafilerna kommer att byggas från den angivna resultatfilen
genom att lägga till sekvensnumret för arket och den delade delen.
Om den angivna utdatafilen till exempel är Image.png, så kommer den genererade bilden
filerna kommer att vara Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, ladda_alternativ, spara_alternativ){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}
Konverterar mallfil till bilder



```python

@staticmethod
def process(load_options, save_options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodeloadoptions) | Alternativ för inmatning och laddning|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptions) | Alternativ för utdata och sparande|
###  Anmärkningar

Vid konvertering till en bild i ett format som stöder flera sidor (t.ex. tiff),
den angivna [`LowCodeSaveOptions.output_file`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptions#output_file)
eller [`LowCodeSaveOptions.output_stream`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptions#output_stream) kommer att användas direkt för den resulterande bilden.


För andra typer av bilder, om sparalternativen har angett ström som utdata,
då sparas alla resulterande bilder i samma ström.
Annars kommer utdatafilerna att byggas från den angivna utdatafilen.
av sparalternativen genom att lägga till sekvensnumret för arket och den delade delen.
Om den angivna utdatafilen till exempel är Image.png, så kommer den genererade bilden
filerna kommer att vara Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, load_options, save_options, provider){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-AbstractLowCodeSaveOptionsProvider}




```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodeloadoptions) |  |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/sv/aspose.cells.lowcode/lowcodesaveoptions) |  |
| provider | AbstractLowCodeSaveOptionsProvider |  |



###  Se även
* modul [`aspose.cells.lowcode`](../../)
* klass [`ImageConverter`](/cells/python-net/sv/aspose.cells.lowcode/imageconverter)
