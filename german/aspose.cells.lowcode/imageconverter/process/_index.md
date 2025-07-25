---
title: process Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.lowcode/imageconverter/process/
is_root: false
---
##  process(, Vorlagendatei, Ergebnisdatei){#str-str}
Konvertiert Vorlagendateien in Bilder.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| template_file | str | Die in Bilder zu konvertierende Vorlagendatei.|
| result_file | str | Die resultierende Datei (Namensmuster) für generierte Bilder.|
###  Bemerkungen

Die Ausgabedateien werden aus der angegebenen Ergebnisdatei erstellt
durch Anhängen der laufenden Nummer des Blattes und des geteilten Teils.
Wenn die angegebene Ausgabedatei beispielsweise Image.png ist, dann wird das generierte Bild
Die Dateien lauten Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, Ladeoptionen, Speicheroptionen){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}
Konvertiert Vorlagendateien in Bilder



```python

@staticmethod
def process(load_options, save_options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodeloadoptions) | Optionen für Eingabe und Beladung|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptions) | Ausgabe- und Speicheroptionen|
###  Bemerkungen

Beim Konvertieren in ein Bildformat, das mehrere Seiten unterstützt (z. B. TIFF),
die angegebene [`LowCodeSaveOptions.output_file`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptions#output_file)
oder [`LowCodeSaveOptions.output_stream`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptions#output_stream) wird direkt für das resultierende Bild verwendet.


Für andere Bildtypen gilt: Wenn in den Speicheroptionen „Stream“ als Ausgabe angegeben ist,
dann werden alle resultierenden Bilder im selben Stream gespeichert.
Andernfalls werden die Ausgabedateien aus der angegebenen Ausgabedatei erstellt
der Speicheroptionen durch Anhängen der Sequenznummer des Blattes und des geteilten Teils.
Wenn die angegebene Ausgabedatei beispielsweise Image.png ist, dann wird das generierte Bild
Die Dateien lauten Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, Ladeoptionen, Speicheroptionen, Anbieter){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-AbstractLowCodeSaveOptionsProvider}




```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodeloadoptions) |  |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/de/aspose.cells.lowcode/lowcodesaveoptions) |  |
| provider | AbstractLowCodeSaveOptionsProvider |  |



###  Siehe auch
* Modul [`aspose.cells.lowcode`](../../)
* Klasse [`ImageConverter`](/cells/python-net/de/aspose.cells.lowcode/imageconverter)
