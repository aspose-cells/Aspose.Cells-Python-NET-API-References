---
title: Metodo set_footer
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 180
url: /it/aspose.cells/pagesetup/set_footer/
is_root: false
---
##  set_footer(self, section, footer_script) {#int-str}
Imposta uno script per formattare il piè di pagina di un file Excel.



```python

def set_footer(self, section, footer_script):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| section | int |0: Sezione sinistra, 1: Sezione centrale, 2: Sezione destra.|
| footer_script | str | Script di formattazione del piè di pagina.|
###  Osservazioni

Comandi script:

| Comando| Descrizione|
| :- | :- |
| &P| Numero di pagina corrente|
| &N| Numero di pagine|
| &D| Data corrente|
| &T| Ora corrente|
| &UN| Nome del foglio|
| &F| Nome file senza percorso|
| &"<FontName>"|Nome del font, ad esempio: &"Arial"|
| &"<FontName>, <FontStyle>"| Nome e stile del carattere, ad esempio: &"Arial,Bold"|
| &<FontSize>| Dimensione del carattere. Se questo comando è seguito da un numero semplice da stampare nell'intestazione, questo sarà separato dall'altezza del carattere con uno spazio.|
| &K<RRGGBB>| Colore del carattere, ad esempio (ROSSO): &KFF0000|
| &G| Script dell'immagine|

Ad esempio: "&Arial,Grassetto&8Nota a piè di pagina"


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`PageSetup`](/cells/python-net/it/aspose.cells/pagesetup)
