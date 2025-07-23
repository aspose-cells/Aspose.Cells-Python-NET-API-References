---
title: FontConfigs classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 670
url: /fr/aspose.cells/fontconfigs/
is_root: false
---
##  FontConfigs classe
Spécifie les paramètres de police



Le type FontConfigs expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/fontconfigs/__init__/#) | Construit une nouvelle instance de FontConfigs|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [default_font_name](/cells/python-net/fr/aspose.cells/fontconfigs/default_font_name) | Obtient ou définit le nom de police par défaut.|
| [prefer_system_font_substitutes](/cells/python-net/fr/aspose.cells/fontconfigs/prefer_system_font_substitutes) | Indiquez s'il faut utiliser en premier les substituts de polices système ou non lorsqu'une police n'est pas présentée et que le substitut de cette police n'est pas défini.<br/>Par exemple, sur Ubuntu, la police « Arial » est généralement remplacée par « Liberation Sans ».<br/> La valeur par défaut est faux.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`is_font_available(, font_name)`](/cells/python-net/fr/aspose.cells/fontconfigs/is_font_available/#str) | Indiquez si la police est disponible.|
| [`get_font_file_data_info(, font_name, is_bold, is_italic, is_exact_style)`](/cells/python-net/fr/aspose.cells/fontconfigs/get_font_file_data_info/#str-bool-bool-bool) | Obtenez des informations sur les données du fichier de police.|
| [`set_font_substitutes(, original_font_name, substitute_font_names)`](/cells/python-net/fr/aspose.cells/fontconfigs/set_font_substitutes/#str-list) | Noms de substitution de police pour le nom de police d'origine donné.|
| [`get_font_substitutes(, original_font_name)`](/cells/python-net/fr/aspose.cells/fontconfigs/get_font_substitutes/#str) |Renvoie un tableau contenant les noms de substitution de police à utiliser si la police d'origine n'est pas présentée.|
| [`set_font_folder(, font_folder, recursive)`](/cells/python-net/fr/aspose.cells/fontconfigs/set_font_folder/#str-bool) | Définit le dossier des polices|
| [`set_font_folders(, font_folders, recursive)`](/cells/python-net/fr/aspose.cells/fontconfigs/set_font_folders/#list-bool) | Définit les dossiers de polices|
| [`set_font_sources(, sources)`](/cells/python-net/fr/aspose.cells/fontconfigs/set_font_sources/#list) |  |
| [`get_font_sources()`](/cells/python-net/fr/aspose.cells/fontconfigs/get_font_sources/#) | Obtient une copie du tableau qui contient la liste des sources|



###  Voir également
* module [`aspose.cells`](..)
