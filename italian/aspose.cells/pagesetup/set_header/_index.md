---
title: Metodo set_header
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 200
url: /it/aspose.cells/pagesetup/set_header/
is_root: false
---
##  set_header(self, section, header_script) {#int-str}
Imposta uno script che formatta l'intestazione di un file Excel.



```python

def set_header(self, section, header_script):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| section | int |0: Sezione sinistra, 1: Sezione centrale, 2: Sezione destra.|
| header_script | str | Script di formato dell'intestazione.|
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

Ad esempio: "&Arial,Grassetto&8Nota di intestazione"


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`PageSetup`](/cells/python-net/it/aspose.cells/pagesetup)
