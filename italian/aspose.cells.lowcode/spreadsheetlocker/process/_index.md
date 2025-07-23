---
title: Metodo process
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---
##  process(, opzioni_di_caricamento, opzioni_di_salvataggio, fornitore){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}
Blocca il file del foglio di calcolo con le impostazioni specificate.



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodeloadoptions) | Opzioni per l'input e il caricamento|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptions) | Opzioni per l'output e il salvataggio|
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/it/aspose.cells.lowcode/abstractlowcodeprotectionprovider) | Implementazione per fornire impostazioni di protezione|


##  process(, file_modello, file_risultato, password_di_apertura, password_di_scrittura){#str-str-str-str}
Blocca il file del foglio di calcolo con le impostazioni specificate.



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| template_file | str | Il file modello da bloccare|
| result_file | str | Il file risultante|
| open_password | str | Password per la crittografia dei file|
| write_password | str |Password per la protezione della modifica del foglio di calcolo|


##  process(, carica_opzioni, salva_opzioni, apri_password, scrivi_password){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}
Blocca il file del foglio di calcolo con le impostazioni specificate.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodeloadoptions) | Opzioni per l'input e il caricamento|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptions) | Opzioni per l'output e il salvataggio|
| open_password | str | Password per la crittografia dei file|
| write_password | str |Password per la protezione della modifica del foglio di calcolo|


##  process(, opzioni_carica, opzioni_salva, password_apri, password_scrivi, password_cartella_di_lavoro, tipo_cartella_di_lavoro){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}
Blocca il file del foglio di calcolo con le impostazioni specificate.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodeloadoptions) | Opzioni per l'input e il caricamento|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/it/aspose.cells.lowcode/lowcodesaveoptions) | Opzioni per l'output e il salvataggio|
| open_password | str | Password per la crittografia dei file|
| write_password | str |Password per la protezione della modifica del foglio di calcolo|
| workbook_password | str | Password per la protezione della cartella di lavoro|
| workbook_type | [`ProtectionType`](/cells/python-net/it/aspose.cells/protectiontype) | Tipo di protezione per proteggere la cartella di lavoro|



###  Guarda anche
* modulo [`aspose.cells.lowcode`](../../)
* classe [`SpreadsheetLocker`](/cells/python-net/it/aspose.cells.lowcode/spreadsheetlocker)
