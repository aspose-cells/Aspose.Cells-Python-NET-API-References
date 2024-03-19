---
title: PdfSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1220
url: /fr/aspose.cells/pdfsaveoptions/
is_root: false
---
##  PdfSaveOptions classe
Représente les options d'enregistrement du fichier pdf.



**Héritage:** [`PdfSaveOptions`](/cells/python-net/aspose.cells/pdfsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)



Le type PdfSaveOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/pdfsaveoptions/__init__/#) | Crée les options d'enregistrement du fichier pdf.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [save_format](/cells/python-net/fr/aspose.cells/pdfsaveoptions/save_format) | Obtient le format du fichier de sauvegarde.|
| [clear_data](/cells/python-net/fr/aspose.cells/pdfsaveoptions/clear_data) | Rendez le classeur vide après avoir enregistré le fichier.|
| [cached_file_folder](/cells/python-net/fr/aspose.cells/pdfsaveoptions/cached_file_folder) | Le dossier de fichiers mis en cache est utilisé pour stocker des données volumineuses.|
| [validate_merged_areas](/cells/python-net/fr/aspose.cells/pdfsaveoptions/validate_merged_areas) | Indique si vous validez les cellules fusionnées avant d'enregistrer le fichier.|
| [merge_areas](/cells/python-net/fr/aspose.cells/pdfsaveoptions/merge_areas) | Indique si fusionner les zones de mise en forme conditionnelle et de validation avant d'enregistrer le fichier.|
| [create_directory](/cells/python-net/fr/aspose.cells/pdfsaveoptions/create_directory) | Si vrai et que le répertoire n'existe pas, le répertoire sera automatiquement créé avant d'enregistrer le fichier.|
| [sort_names](/cells/python-net/fr/aspose.cells/pdfsaveoptions/sort_names) | Indique si le tri des noms définis avant d'enregistrer le fichier.|
| [sort_external_names](/cells/python-net/fr/aspose.cells/pdfsaveoptions/sort_external_names) | Indique si le tri des noms définis externes avant d'enregistrer le fichier.|
| [refresh_chart_cache](/cells/python-net/fr/aspose.cells/pdfsaveoptions/refresh_chart_cache) | Indique si l'actualisation des données du cache de graphique|
| [warning_callback](/cells/python-net/fr/aspose.cells/pdfsaveoptions/warning_callback) | Obtient ou définit un rappel d’avertissement.|
| [update_smart_art](/cells/python-net/fr/aspose.cells/pdfsaveoptions/update_smart_art) | Indique si la mise à jour des paramètres d'art intelligent est effectuée.<br/> La valeur par défaut est fausse.|
| [default_font](/cells/python-net/fr/aspose.cells/pdfsaveoptions/default_font) | Lorsque les caractères dans Excel sont Unicode et ne sont pas définis avec la police correcte dans le style de cellule,<br/>Ils peuvent apparaître sous forme de bloc dans pdf,image.<br/>Définissez DefaultFont tel que MingLiu ou MS Gothic pour afficher ces caractères.<br/> Si cette propriété n'est pas définie, Aspose.Cells utilisera la police par défaut du système pour afficher ces caractères Unicode.|
| [check_workbook_default_font](/cells/python-net/fr/aspose.cells/pdfsaveoptions/check_workbook_default_font) | Lorsque les caractères dans Excel sont Unicode et ne sont pas définis avec la police correcte dans le style de cellule,<br/>Ils peuvent apparaître sous forme de bloc dans pdf,image.<br/> Définissez cette valeur sur true pour essayer d'utiliser la police par défaut du classeur pour afficher ces caractères en premier.|
| [check_font_compatibility](/cells/python-net/fr/aspose.cells/pdfsaveoptions/check_font_compatibility) | Indique s’il faut vérifier la compatibilité des polices pour chaque caractère du texte.|
| [is_font_substitution_char_granularity](/cells/python-net/fr/aspose.cells/pdfsaveoptions/is_font_substitution_char_granularity) |Indique s'il convient de remplacer la police de caractère uniquement lorsque la police de la cellule n'est pas compatible avec celui-ci.|
| [one_page_per_sheet](/cells/python-net/fr/aspose.cells/pdfsaveoptions/one_page_per_sheet) | Si OnePagePerSheet est true , tout le contenu d’une feuille sera affiché sur une seule page.<br/> Le format de papier de la configuration de la page sera invalide et les autres paramètres de la configuration de la page<br/> prendra toujours effet.|
| [all_columns_in_one_page_per_sheet](/cells/python-net/fr/aspose.cells/pdfsaveoptions/all_columns_in_one_page_per_sheet) | Si AllColumnsInOnePagePerSheet est true , tout le contenu des colonnes d’une feuille sera affiché sur une seule page dans le résultat.<br/> La largeur du format de papier de pagesetup sera ignorée et les autres paramètres de pagesetup<br/> prendra toujours effet.|
| [ignore_error](/cells/python-net/fr/aspose.cells/pdfsaveoptions/ignore_error) | Indique si vous devez masquer l'erreur lors du rendu.<br/> L'erreur peut être une erreur de forme, d'image, de rendu du graphique, etc.|
| [output_blank_page_when_nothing_to_print](/cells/python-net/fr/aspose.cells/pdfsaveoptions/output_blank_page_when_nothing_to_print) | Indique s’il faut imprimer une page vierge lorsqu’il n’y a rien à imprimer.|
| [page_index](/cells/python-net/fr/aspose.cells/pdfsaveoptions/page_index) | Obtient ou définit l'index de base 0 de la première page à enregistrer.|
| [page_count](/cells/python-net/fr/aspose.cells/pdfsaveoptions/page_count) | Obtient ou définit le nombre de pages à enregistrer.|
| [printing_page_type](/cells/python-net/fr/aspose.cells/pdfsaveoptions/printing_page_type) | Indique quelles pages ne seront pas imprimées.|
| [gridline_type](/cells/python-net/fr/aspose.cells/pdfsaveoptions/gridline_type) | Obtient ou définit le type de quadrillage.|
| [text_cross_type](/cells/python-net/fr/aspose.cells/pdfsaveoptions/text_cross_type) | Obtient ou définit l'affichage du type de texte lorsque la largeur du texte est supérieure à la largeur de la cellule.|
| [default_edit_language](/cells/python-net/fr/aspose.cells/pdfsaveoptions/default_edit_language) | Obtient ou définit la langue d'édition par défaut.|
| [sheet_set](/cells/python-net/fr/aspose.cells/pdfsaveoptions/sheet_set) |Obtient ou définit les feuilles à restituer. La valeur par défaut correspond à toutes les feuilles visibles dans le classeur : [`SheetSet.visible`](/cells/python-net/fr/aspose.cells.rendering/sheetset#visible).|
| [draw_object_event_handler](/cells/python-net/fr/aspose.cells/pdfsaveoptions/draw_object_event_handler) | Implémente cette interface pour obtenir DrawObject et Bound lors du rendu.|
| [page_saving_callback](/cells/python-net/fr/aspose.cells/pdfsaveoptions/page_saving_callback) | Contrôler/indiquer la progression du processus d’enregistrement des pages.|
| [emf_render_setting](/cells/python-net/fr/aspose.cells/pdfsaveoptions/emf_render_setting) | Paramètre de rendu du métafichier Emf.|
| [embed_standard_windows_fonts](/cells/python-net/fr/aspose.cells/pdfsaveoptions/embed_standard_windows_fonts) | True pour intégrer des polices True Type.<br/>Affecte uniquement les caractères ASCII 32-127.<br/>Les polices pour les codes de caractères supérieurs à 127 sont toujours intégrées.<br/>Les polices sont toujours intégrées pour les normes PDF/A-1a, PDF/A-1b.<br/> La valeur par défaut est vraie.|
| [bookmark](/cells/python-net/fr/aspose.cells/pdfsaveoptions/bookmark) | Obtient et définit l'objet [`PdfBookmarkEntry`](/cells/python-net/fr/aspose.cells.rendering/pdfbookmarkentry).|
| [compliance](/cells/python-net/fr/aspose.cells/pdfsaveoptions/compliance) | Obtient ou définit le niveau de conformité aux normes PDF pour les documents de sortie.|
| [security_options](/cells/python-net/fr/aspose.cells/pdfsaveoptions/security_options) | Définissez ces options lorsque la sécurité est nécessaire dans le résultat xls2pdf.|
| [image_type](/cells/python-net/fr/aspose.cells/pdfsaveoptions/image_type) |Représente le type d'image lors de la conversion du graphique et de la forme.|
| [calculate_formula](/cells/python-net/fr/aspose.cells/pdfsaveoptions/calculate_formula) | Indique s'il faut calculer les formules avant d'enregistrer le fichier pdf.|
| [pdf_compression](/cells/python-net/fr/aspose.cells/pdfsaveoptions/pdf_compression) | Indiquer l'algorithme de compression|
| [created_time](/cells/python-net/fr/aspose.cells/pdfsaveoptions/created_time) | Obtient et définit l'heure de génération du document pdf.|
| [producer](/cells/python-net/fr/aspose.cells/pdfsaveoptions/producer) | Obtient et définit le producteur du document PDF généré.|
| [optimization_type](/cells/python-net/fr/aspose.cells/pdfsaveoptions/optimization_type) | Obtient et définit le type d'optimisation PDF.|
| [custom_properties_export](/cells/python-net/fr/aspose.cells/pdfsaveoptions/custom_properties_export) | Obtient ou définit une valeur déterminant la manière dont les [`CustomDocumentPropertyCollection`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection) sont exportés vers le fichier PDF. La valeur par défaut est Aucun.|
| [export_document_structure](/cells/python-net/fr/aspose.cells/pdfsaveoptions/export_document_structure) | Indique s’il faut exporter la structure du document.|
| [display_doc_title](/cells/python-net/fr/aspose.cells/pdfsaveoptions/display_doc_title) | Indique si la barre de titre de la fenêtre doit afficher le titre du document.|
| [font_encoding](/cells/python-net/fr/aspose.cells/pdfsaveoptions/font_encoding) | Obtient ou définit l’encodage des polices intégrées au format PDF.|
| [watermark](/cells/python-net/fr/aspose.cells/pdfsaveoptions/watermark) | Obtient ou définit le filigrane à afficher.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [set_image_resample](/cells/python-net/fr/aspose.cells/pdfsaveoptions/set_image_resample/#int-int) | Définit le PPI (pixels par pouce) souhaité pour les images de rééchantillonnage et la qualité JPEG.<br/> Toutes les images seront converties en JPEG avec le paramètre de qualité spécifié,<br/> et les images supérieures au PPI spécifié (pixels par pouce) seront rééchantillonnées.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`CustomDocumentPropertyCollection`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection)
* classe [`PaginatedSaveOptions`](/cells/python-net/fr/aspose.cells/paginatedsaveoptions)
* classe [`PdfBookmarkEntry`](/cells/python-net/fr/aspose.cells.rendering/pdfbookmarkentry)
* classe [`PdfSaveOptions`](/cells/python-net/fr/aspose.cells/pdfsaveoptions)
* classe [`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)
