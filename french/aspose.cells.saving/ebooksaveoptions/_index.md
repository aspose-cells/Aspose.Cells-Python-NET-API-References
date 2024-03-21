---
title: EbookSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells.saving/ebooksaveoptions/
is_root: false
---
##  EbookSaveOptions classe
Représente les options d’enregistrement du fichier ebook.



**Héritage:** [`EbookSaveOptions`](/cells/python-net/aspose.cells.saving/ebooksaveoptions) → 
[`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)



Le type EbookSaveOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/__init__/#) | Crée des options pour enregistrer le fichier ebook.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [save_format](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/save_format) | Obtient le format du fichier de sauvegarde.|
| [clear_data](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/clear_data) | Rendez le classeur vide après avoir enregistré le fichier.|
| [cached_file_folder](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/cached_file_folder) | Le dossier de fichiers mis en cache est utilisé pour stocker des données volumineuses.|
| [validate_merged_areas](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/validate_merged_areas) | Indique si vous validez les cellules fusionnées avant d'enregistrer le fichier.|
| [merge_areas](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/merge_areas) | Indique si fusionner les zones de mise en forme conditionnelle et de validation avant d'enregistrer le fichier.|
| [create_directory](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/create_directory) | Si vrai et que le répertoire n'existe pas, le répertoire sera automatiquement créé avant d'enregistrer le fichier.|
| [sort_names](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/sort_names) | Indique si le tri des noms définis avant d'enregistrer le fichier.|
| [sort_external_names](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/sort_external_names) | Indique si le tri des noms définis externes avant d'enregistrer le fichier.|
| [refresh_chart_cache](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/refresh_chart_cache) | Indique si l'actualisation des données du cache de graphique|
| [warning_callback](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/warning_callback) | Obtient ou définit un rappel d’avertissement.|
| [update_smart_art](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/update_smart_art) | Indique si la mise à jour des paramètres d'art intelligent est effectuée.<br/> La valeur par défaut est fausse.|
| [ignore_invisible_shapes](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/ignore_invisible_shapes) | Indiquez si vous exportez ces formes non visibles|
| [page_title](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/page_title) | Le titre de la page html.<br/> Uniquement pour l'enregistrement dans un flux HTML.|
| [attached_files_directory](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/attached_files_directory) | Le répertoire dans lequel les fichiers joints seront enregistrés.<br/> Uniquement pour l'enregistrement dans un flux HTML.|
| [attached_files_url_prefix](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/attached_files_url_prefix) | Spécifiez le préfixe Url des fichiers joints tels que l'image dans le fichier HTML.<br/> Uniquement pour l'enregistrement dans un flux HTML.|
| [default_font_name](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/default_font_name) | Spécifiez le nom de la police par défaut pour l'export html, la police par défaut sera utilisée lorsque la police de style n'existe pas,<br/>Si cette propriété est nulle, Aspose.Cells utilisera une police universelle qui a la même famille que la police d'origine,<br/> la valeur par défaut est nulle.|
| [worksheet_scalable](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/worksheet_scalable) | Indique si vous effectuez un zoom avant ou arrière sur le HTML via le niveau de zoom de la feuille de calcul lors de l'enregistrement du fichier au format HTML, la valeur par défaut est false.|
| [is_export_comments](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/is_export_comments) |Indique si vous exportez des commentaires lors de l'enregistrement du fichier au format HTML, la valeur par défaut est false.|
| [export_comments_type](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_comments_type) | Représente le type d’exportation de commentaires vers des fichiers HTML.|
| [disable_downlevel_revealed_comments](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/disable_downlevel_revealed_comments) | Indique si vous désactivez les commentaires conditionnels révélés par Downlevel lors de l'exportation du fichier au format HTML, la valeur par défaut est false.|
| [is_exp_image_to_temp_dir](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/is_exp_image_to_temp_dir) | Indique si l'exportation des fichiers image vers le répertoire temporaire.<br/> Uniquement pour l'enregistrement dans un flux HTML.|
| [image_scalable](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/image_scalable) | Indique si vous utilisez une unité évolutive pour décrire la largeur de l'image<br/>lors de l'utilisation d'une unité évolutive pour décrire la largeur de la colonne.<br/> La valeur par défaut est vraie.|
| [width_scalable](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/width_scalable) | Indique si l'exportation de la largeur de colonne en unité d'échelle vers HTML.<br/> La valeur par défaut est fausse.|
| [export_single_tab](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_single_tab) | Indique s’il faut exporter l’onglet unique lorsque le fichier ne contient qu’une seule feuille de calcul.<br/> La valeur par défaut est fausse.|
| [export_images_as_base64](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_images_as_base64) | Spécifie si les images sont enregistrées au format Base64 au format HTML, MHTML ou EPUB.|
| [export_active_worksheet_only](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_active_worksheet_only) | Indique si vous exportez uniquement la feuille de calcul active vers un fichier HTML.<br/>Si c'est vrai, seule la feuille de calcul active sera exportée vers un fichier HTML ;<br/>Si faux, l'intégralité du classeur sera exportée vers un fichier HTML.<br/> La valeur par défaut est fausse.|
| [export_print_area_only](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_print_area_only) | Indique si vous exportez uniquement la zone d'impression vers un fichier HTML. La valeur par défaut est fausse.|
| [export_area](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_area) | Obtient ou définit la CellArea d’exportation de la feuille de calcul active actuelle.<br/>Si vous définissez cet attribut, la zone d'impression de la feuille de calcul active actuelle sera omise.<br/> Seule la zone spécifiée sera exportée lors de l'enregistrement du fichier au format HTML.|
| [parse_html_tag_in_cell](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/parse_html_tag_in_cell) |Indique si la balise HTML (telle que `<div></div>`) dans la cellule doit être analysée en tant que valeur de cellule ou conservée telle quelle.<br/> La valeur par défaut est vraie.|
| [html_cross_string_type](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/html_cross_string_type) | Indique si une chaîne inter-cellules sera affichée de la même manière que MS Excel lors de l'enregistrement d'un fichier Excel au format HTML.<br/>Par défaut, la valeur est Default. Ainsi, pour les chaînes inter-cellules, il y a peu de différence entre les fichiers HTML créés par Aspose.Cells et MS Excel.<br/> Mais les performances de création de gros fichiers HTML, en définissant la valeur sur Cross, seraient plusieurs fois plus rapides que de la définir sur Default ou Fit2Cell.|
| [hidden_col_display_type](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/hidden_col_display_type) | Colonne masquée (la largeur de cette colonne est de 0) dans Excel, avant de l'enregistrer au format HTML,<br/>si HtmlHiddenColDisplayType est "Remove", la colonne masquée ne sera pas affichée,<br/> si la valeur est "Cachée", la colonne serait affichée, mais était masquée, la valeur par défaut est "Cachée"|
| [hidden_row_display_type](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/hidden_row_display_type) | Ligne cachée (la hauteur de cette ligne est 0) dans Excel, avant de l'enregistrer au format HTML,<br/>si HtmlHiddenRowDisplayType est "Remove", la ligne masquée ne sera pas affichée,<br/> si la valeur est "Cachée", la ligne serait affichée, mais était masquée, la valeur par défaut est "Cachée"|
| [encoding](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/encoding) | S’il n’est pas défini, utilisez Encoding.UTF8 comme type d’encodage par défaut.|
| [export_object_listener](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_object_listener) | Obtient ou définit le ExportObjectListener pour exporter des objets.|
| [file_path_provider](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/file_path_provider) |Obtient ou définit IFilePathProvider pour exporter séparément la feuille de calcul au format HTML.|
| [stream_provider](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/stream_provider) | Obtient ou définit le IStreamProvider pour exporter des objets.|
| [image_options](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/image_options) | Récupérez l'objet ImageOrPrintOptions avant d'exporter|
| [save_as_single_file](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/save_as_single_file) | Indique si vous enregistrez le code HTML sous forme de fichier unique.<br/> La valeur par défaut est fausse.|
| [show_all_sheets](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/show_all_sheets) | Indique si toutes les feuilles sont affichées lors de l'enregistrement en tant que fichier HTML unique.|
| [export_page_headers](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_page_headers) | Indique si vous exportez les en-têtes de page.|
| [export_page_footers](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_page_footers) | Indique si vous exportez les en-têtes de page.|
| [export_hidden_worksheet](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_hidden_worksheet) | Indique si vous exportez le contenu masqué de la feuille de calcul. La valeur par défaut est vraie.|
| [presentation_preference](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/presentation_preference) | Indiquer si le fichier HTML ou MHT est la préférence de présentation.<br/>La valeur par défaut est fausse.<br/> si vous souhaitez obtenir une plus belle présentation, veuillez définir la valeur sur true.|
| [cell_css_prefix](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/cell_css_prefix) | Obtient et définit le préfixe du nom CSS, la valeur par défaut est "".|
| [table_css_id](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/table_css_id) | Obtient et définit le préfixe du nom CSS du type tel que tr, col, td et ainsi de suite, ils sont contenus dans l'élément table<br/> qui a l'attribut spécifique TableCssId. La valeur par défaut est "".|
| [is_full_path_link](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/is_full_path_link) | Indique si vous utilisez le lien de chemin complet dans sheet00x.htm, filelist.xml et tabstrip.htm.<br/> La valeur par défaut est fausse.|
| [export_worksheet_css_separately](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_worksheet_css_separately) |Indique si vous exportez la feuille de calcul CSS séparément. La valeur par défaut est false.|
| [export_similar_border_style](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_similar_border_style) | Indique si l'exportation du style de bordure similaire lorsque le style de bordure n'est pas pris en charge par les navigateurs.<br/>Si vous souhaitez importer le fichier html ou mht vers Excel, veuillez conserver la valeur par défaut.<br/> La valeur par défaut est fausse.|
| [merge_empty_td_forcely](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/merge_empty_td_forcely) | Indique si la fusion des éléments TD vides est forcée lors de l'exportation du fichier au format HTML.<br/> La taille du fichier HTML sera considérablement réduite après avoir défini la valeur sur true. La valeur par défaut est fausse.<br/> Si vous souhaitez importer le fichier HTML vers Excel ou exporter des lignes de grille parfaites lors de l'enregistrement du fichier au format HTML,<br/> veuillez conserver la valeur par défaut.|
| [merge_empty_td_type](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/merge_empty_td_type) | Indique si l'élément TD vide sera fusionné de la même manière que MS Excel lors de l'enregistrement d'un fichier Excel au format HTML.<br/> La valeur par défaut est MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_cell_coordinate) | Indique si l'exportation des coordonnées Excel des cellules non vides lors de l'enregistrement du fichier au format HTML. La valeur par défaut est fausse.<br/> Si vous souhaitez importer le code HTML de sortie vers Excel, veuillez conserver la valeur par défaut.|
| [export_extra_headings](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_extra_headings) | Indique si l'exportation de titres supplémentaires lorsque la longueur du texte est supérieure à la colonne d'affichage maximale.<br/> La valeur par défaut est fausse. Si vous souhaitez importer le fichier html vers Excel, veuillez conserver la valeur par défaut.|
| [export_headings](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_headings) |Indique si les en-têtes de lignes et de colonnes de la feuille sont exportés lors de l'enregistrement dans des fichiers HTML.|
| [export_row_column_headings](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_row_column_headings) |Indique si les en-têtes de lignes et de colonnes de la feuille sont exportés lors de l'enregistrement dans des fichiers HTML.|
| [export_formula](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_formula) | Indique si l'exportation de la formule lors de l'enregistrement du fichier au format HTML. La valeur par défaut est vraie.<br/> Si vous souhaitez importer le code HTML de sortie vers Excel, veuillez conserver la valeur par défaut.|
| [add_tooltip_text](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/add_tooltip_text) | Indique s'il faut ajouter du texte d'info-bulle lorsque les données ne peuvent pas être entièrement affichées.<br/> La valeur par défaut est fausse.|
| [export_grid_lines](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_grid_lines) | Indique s'il faut exporter le quadrillage. La valeur par défaut est false.|
| [export_bogus_row_data](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_bogus_row_data) | Indique si l'exportation de fausses données de la ligne inférieure est exportée. La valeur par défaut est true. Si vous souhaitez importer le fichier html ou mht<br/> pour exceler, veuillez conserver la valeur par défaut.|
| [exclude_unused_styles](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles) | Indique si les styles inutilisés sont exclus.<br/>Pour les fichiers HTML générés, l'exclusion des styles inutilisés peut réduire la taille du fichier.<br/>sans affecter les effets visuels. La valeur par défaut de cette propriété est donc vraie.<br/>Si l'utilisateur doit conserver tous les styles dans le classeur pour le code HTML généré (comme le scénario dans lequel l'utilisateur<br/> doit restaurer le classeur à partir du code HTML généré ultérieurement), veuillez définir cette propriété sur false.|
| [export_document_properties](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_document_properties) | Indique si l'exportation des propriétés du document. La valeur par défaut est vraie. Si vous souhaitez importer<br/> le fichier html ou mht vers Excel, veuillez conserver la valeur par défaut.|
| [export_worksheet_properties](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_worksheet_properties) | Indique si vous exportez les propriétés de la feuille de calcul. La valeur par défaut est true. Si vous souhaitez importer<br/> le fichier html ou mht vers Excel, veuillez conserver la valeur par défaut.|
| [export_workbook_properties](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_workbook_properties) |Indique si l'exportation des propriétés du classeur. La valeur par défaut est true. Si vous souhaitez importer<br/> le fichier html ou mht vers Excel, veuillez conserver la valeur par défaut.|
| [export_frame_scripts_and_properties](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_frame_scripts_and_properties) | Indique s'il faut exporter les scripts de frame et les propriétés du document. La valeur par défaut est true. Si vous souhaitez importer le fichier html ou mht<br/> pour exceler, veuillez conserver la valeur par défaut.|
| [export_data_options](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/export_data_options) | Indiquant la règle d'exportation des données du fichier HTML. La valeur par défaut est Tout.|
| [link_target_type](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/link_target_type) | Indiquer le type d'attribut cible dans le lien `<a>`. La valeur par défaut est HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/is_ie_compatible) | Indique si la sortie HTML est compatible avec le navigateur IE.<br/> La valeur par défaut est fausse|
| [format_data_ignore_column_width](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/format_data_ignore_column_width) | Indique si l'intégralité des données formatées de la cellule est affichée lors du débordement de la colonne.<br/>Si c'est vrai, ignorez la largeur de la colonne et toutes les données de la cellule seront exportées.<br/>Si faux, les données seront exportées de la même manière qu’Excel.<br/> La valeur par défaut est fausse.|
| [calculate_formula](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/calculate_formula) | Indique s'il faut calculer les formules avant d'enregistrer le fichier HTML.|
| [is_js_browser_compatible](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/is_js_browser_compatible) | Indique si JavaScript est compatible avec les navigateurs qui ne prennent pas en charge JavaScript.<br/> La valeur par défaut est vraie.|
| [is_mobile_compatible](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/is_mobile_compatible) | Indique si la sortie HTML est compatible avec les appareils mobiles.<br/> La valeur par défaut est fausse.|
| [css_styles](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions/css_styles) | Obtient ou définit les styles CSS supplémentaires pour le formateur.<br/>Fonctionne uniquement lorsque [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/fr/aspose.cells/htmlsaveoptions#save_as_single_file) est True.<br/><br/> CssStyles="corps { rembourrage : 5px }" ;|



###  Voir également
* module [`aspose.cells.saving`](..)
* classe [`EbookSaveOptions`](/cells/python-net/fr/aspose.cells.saving/ebooksaveoptions)
* classe [`HtmlSaveOptions`](/cells/python-net/fr/aspose.cells/htmlsaveoptions)
* classe [`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)
