---
title: FontConfigs classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 670
url: /it/aspose.cells/fontconfigs/
is_root: false
---
##  FontConfigs classe
Specifica le impostazioni del carattere



Il tipo FontConfigs espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/fontconfigs/__init__/#) | Crea una nuova istanza di FontConfigs|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [default_font_name](/cells/python-net/it/aspose.cells/fontconfigs/default_font_name) | Ottiene o imposta il nome del font predefinito.|
| [prefer_system_font_substitutes](/cells/python-net/it/aspose.cells/fontconfigs/prefer_system_font_substitutes) | Indica se utilizzare prima o meno i sostituti dei font di sistema quando un font non è presentato e il sostituto di questo font non è impostato.<br/>Ad esempio, su Ubuntu, il font "Arial" è generalmente sostituito da "Liberation Sans".<br/> Il valore predefinito è falso.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`is_font_available(, font_name)`](/cells/python-net/it/aspose.cells/fontconfigs/is_font_available/#str) | Indica se il font è disponibile.|
| [`get_font_file_data_info(, font_name, is_bold, is_italic, is_exact_style)`](/cells/python-net/it/aspose.cells/fontconfigs/get_font_file_data_info/#str-bool-bool-bool) | Ottieni informazioni sui dati del file di font.|
| [`set_font_substitutes(, original_font_name, substitute_font_names)`](/cells/python-net/it/aspose.cells/fontconfigs/set_font_substitutes/#str-list) | Nomi sostitutivi dei font per il nome del font originale fornito.|
| [`get_font_substitutes(, original_font_name)`](/cells/python-net/it/aspose.cells/fontconfigs/get_font_substitutes/#str) |Restituisce una matrice contenente i nomi dei font sostitutivi da utilizzare se il font originale non è presentato.|
| [`set_font_folder(, font_folder, recursive)`](/cells/python-net/it/aspose.cells/fontconfigs/set_font_folder/#str-bool) | Imposta la cartella dei caratteri|
| [`set_font_folders(, font_folders, recursive)`](/cells/python-net/it/aspose.cells/fontconfigs/set_font_folders/#list-bool) | Imposta le cartelle dei caratteri|
| [`set_font_sources(, sources)`](/cells/python-net/it/aspose.cells/fontconfigs/set_font_sources/#list) |  |
| [`get_font_sources()`](/cells/python-net/it/aspose.cells/fontconfigs/get_font_sources/#) | Ottiene una copia dell'array che contiene l'elenco delle fonti|



###  Guarda anche
* modulo [`aspose.cells`](..)
