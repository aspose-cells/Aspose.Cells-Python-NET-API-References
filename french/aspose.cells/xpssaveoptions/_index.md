---
title: XpsSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1800
url: /fr/aspose.cells/xpssaveoptions/
is_root: false
---
##  XpsSaveOptions classe
Représente les options supplémentaires lors de l’enregistrement du fichier en tant que Xps.



**Héritage:** [`XpsSaveOptions`](/cells/python-net/aspose.cells/xpssaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)



Le type XpsSaveOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/xpssaveoptions/__init__/#) | Crée des options pour enregistrer le fichier XPS.|
| [__init__](/cells/python-net/fr/aspose.cells/xpssaveoptions/__init__/#aspose.cells.SaveFormat) | Crée des options pour enregistrer le fichier XPS.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [save_format](/cells/python-net/fr/aspose.cells/xpssaveoptions/save_format) | Obtient le format du fichier de sauvegarde.|
| [clear_data](/cells/python-net/fr/aspose.cells/xpssaveoptions/clear_data) | Rendez le classeur vide après avoir enregistré le fichier.|
| [cached_file_folder](/cells/python-net/fr/aspose.cells/xpssaveoptions/cached_file_folder) | Le dossier de fichiers mis en cache est utilisé pour stocker des données volumineuses.|
| [validate_merged_areas](/cells/python-net/fr/aspose.cells/xpssaveoptions/validate_merged_areas) | Indique si vous validez les cellules fusionnées avant d'enregistrer le fichier.|
| [merge_areas](/cells/python-net/fr/aspose.cells/xpssaveoptions/merge_areas) | Indique si fusionner les zones de mise en forme conditionnelle et de validation avant d'enregistrer le fichier.|
| [create_directory](/cells/python-net/fr/aspose.cells/xpssaveoptions/create_directory) | Si vrai et que le répertoire n'existe pas, le répertoire sera automatiquement créé avant d'enregistrer le fichier.|
| [sort_names](/cells/python-net/fr/aspose.cells/xpssaveoptions/sort_names) | Indique si le tri des noms définis avant d'enregistrer le fichier.|
| [sort_external_names](/cells/python-net/fr/aspose.cells/xpssaveoptions/sort_external_names) | Indique si le tri des noms définis externes avant d'enregistrer le fichier.|
| [refresh_chart_cache](/cells/python-net/fr/aspose.cells/xpssaveoptions/refresh_chart_cache) | Indique si l'actualisation des données du cache de graphique|
| [warning_callback](/cells/python-net/fr/aspose.cells/xpssaveoptions/warning_callback) | Obtient ou définit un rappel d’avertissement.|
| [update_smart_art](/cells/python-net/fr/aspose.cells/xpssaveoptions/update_smart_art) | Indique si la mise à jour des paramètres d'art intelligent est effectuée.<br/> La valeur par défaut est fausse.|
| [default_font](/cells/python-net/fr/aspose.cells/xpssaveoptions/default_font) | Lorsque les caractères dans Excel sont Unicode et ne sont pas définis avec la police correcte dans le style de cellule,<br/>Ils peuvent apparaître sous forme de bloc dans pdf,image.<br/>Définissez DefaultFont tel que MingLiu ou MS Gothic pour afficher ces caractères.<br/> Si cette propriété n'est pas définie, Aspose.Cells utilisera la police par défaut du système pour afficher ces caractères Unicode.|
| [check_workbook_default_font](/cells/python-net/fr/aspose.cells/xpssaveoptions/check_workbook_default_font) | Lorsque les caractères dans Excel sont Unicode et ne sont pas définis avec la police correcte dans le style de cellule,<br/>Ils peuvent apparaître sous forme de bloc dans pdf,image.<br/> Définissez cette valeur sur true pour essayer d'utiliser la police par défaut du classeur pour afficher ces caractères en premier.|
| [check_font_compatibility](/cells/python-net/fr/aspose.cells/xpssaveoptions/check_font_compatibility) | Indique s’il faut vérifier la compatibilité des polices pour chaque caractère du texte.|
| [is_font_substitution_char_granularity](/cells/python-net/fr/aspose.cells/xpssaveoptions/is_font_substitution_char_granularity) |Indique s'il convient de remplacer la police de caractère uniquement lorsque la police de la cellule n'est pas compatible avec celui-ci.|
| [one_page_per_sheet](/cells/python-net/fr/aspose.cells/xpssaveoptions/one_page_per_sheet) | Si OnePagePerSheet est true , tout le contenu d’une feuille sera affiché sur une seule page.<br/> Le format de papier de la configuration de la page sera invalide et les autres paramètres de la configuration de la page<br/> prendra toujours effet.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/fr/aspose.cells/xpssaveoptions/all_columns_in_one_page_per_sheet) | Si AllColumnsInOnePagePerSheet est true , tout le contenu des colonnes d’une feuille sera affiché sur une seule page dans le résultat.<br/> La largeur du format de papier de pagesetup sera ignorée et les autres paramètres de pagesetup<br/> prendra toujours effet.|
| [ignore_error](/cells/python-net/fr/aspose.cells/xpssaveoptions/ignore_error) | Indique si vous devez masquer l'erreur lors du rendu.<br/> L'erreur peut être une erreur de forme, d'image, de rendu du graphique, etc.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/fr/aspose.cells/xpssaveoptions/output_blank_page_when_nothing_to_print) | Indique s’il faut imprimer une page vierge lorsqu’il n’y a rien à imprimer.|
| [page_index](/cells/python-net/fr/aspose.cells/xpssaveoptions/page_index) | Obtient ou définit l'index de base 0 de la première page à enregistrer.|
| [page_count](/cells/python-net/fr/aspose.cells/xpssaveoptions/page_count) | Obtient ou définit le nombre de pages à enregistrer.|
| [printing_page_type](/cells/python-net/fr/aspose.cells/xpssaveoptions/printing_page_type) | Indique quelles pages ne seront pas imprimées.|
| [gridline_type](/cells/python-net/fr/aspose.cells/xpssaveoptions/gridline_type) | Obtient ou définit le type de quadrillage.|
| [text_cross_type](/cells/python-net/fr/aspose.cells/xpssaveoptions/text_cross_type) | Obtient ou définit l'affichage du type de texte lorsque la largeur du texte est supérieure à la largeur de la cellule.|
| [default_edit_language](/cells/python-net/fr/aspose.cells/xpssaveoptions/default_edit_language) | Obtient ou définit la langue d'édition par défaut.|
| [sheet_set](/cells/python-net/fr/aspose.cells/xpssaveoptions/sheet_set) |Obtient ou définit les feuilles à restituer. La valeur par défaut correspond à toutes les feuilles visibles dans le classeur : [`SheetSet.visible`](/cells/python-net/fr/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/fr/aspose.cells/xpssaveoptions/draw_object_event_handler) | Implémente cette interface pour obtenir DrawObject et Bound lors du rendu.|
| [page_saving_callback](/cells/python-net/fr/aspose.cells/xpssaveoptions/page_saving_callback) | Contrôler/indiquer la progression du processus d’enregistrement des pages.|
| [emf_render_setting](/cells/python-net/fr/aspose.cells/xpssaveoptions/emf_render_setting) | Paramètre de rendu du métafichier Emf.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`PaginatedSaveOptions`](/cells/python-net/fr/aspose.cells/paginatedsaveoptions)
* classe [`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)
* classe [`XpsSaveOptions`](/cells/python-net/fr/aspose.cells/xpssaveoptions)
