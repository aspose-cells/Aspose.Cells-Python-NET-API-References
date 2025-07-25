---
title: Metodo process
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.lowcode/imageconverter/process/
is_root: false
---
##  process(, file_modello, file_risultato){#str-str}
Converte il file modello in immagini.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| template_file | str | Il file modello da convertire in immagini.|
| result_file | str | Il file risultante (modello di nome) per le immagini generate.|
###  Osservazioni

I file di output verranno creati a partire dal file di risultati specificato
aggiungendo il numero di sequenza del foglio e della parte divisa.
Ad esempio, se il file di output specificato è Image.png, l'immagine generata
i file saranno Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, carica_opzioni, salva_opzioni){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions}
Converte il file modello in immagini



```python

@staticmethod
def process(load_options, save_options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodeloadoptions) | Opzioni per l'input e il caricamento|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptions) | Opzioni per l'output e il salvataggio|
###  Osservazioni

Quando si converte in un'immagine di un formato che supporta più pagine (ad esempio tiff),
il [`LowCodeSaveOptions.output_file`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptions#output_file) specificato
oppure [`LowCodeSaveOptions.output_stream`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptions#output_stream) verrà utilizzato direttamente per l'immagine risultante.


Per altri tipi di immagine, se le opzioni di salvataggio hanno specificato Stream come output,
quindi tutte le immagini risultanti verranno salvate nello stesso Stream.
In caso contrario, i file di output verranno creati a partire dal file di output specificato
delle opzioni di salvataggio aggiungendo il numero di sequenza del foglio e della parte divisa.
Ad esempio, se il file di output specificato è Image.png, l'immagine generata
i file saranno Image_0_0.png, Image_0_1.png, ..., Image_1_0.png, ...

##  process(, opzioni_di_caricamento, opzioni_di_salvataggio, fornitore){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-AbstractLowCodeSaveOptionsProvider}




```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodeloadoptions) |  |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptions) |  |
| provider | AbstractLowCodeSaveOptionsProvider |  |



###  Guarda anche
* modulo [`aspose.cells.lowcode`](../../)
* classe [`ImageConverter`](/cells/python-net/it/aspose.cells.lowcode/imageconverter)
