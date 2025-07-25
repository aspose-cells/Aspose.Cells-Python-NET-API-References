---
title: HtmlSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 790
url: /fr/aspose.cells/htmlsaveoptions/
is_root: false
---
##  HtmlSaveOptions classe
Représente les options d'enregistrement du fichier HTML.



**Héritage:** [`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)



Le type HtmlSaveOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/htmlsaveoptions/__init__/#) | Crée des options pour enregistrer le fichier HTML.|
| [`__init__(self, save_format)`](/cells/python-net/fr/aspose.cells/htmlsaveoptions/__init__/#aspose.cells.saveformat) | Crée des options pour enregistrer le fichier htm.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [save_format](/cells/python-net/fr/aspose.cells/htmlsaveoptions/save_format) | Obtient le format du fichier de sauvegarde.|
| [clear_data](/cells/python-net/fr/aspose.cells/htmlsaveoptions/clear_data) | Videz le classeur après avoir enregistré le fichier.|
| [cached_file_folder](/cells/python-net/fr/aspose.cells/htmlsaveoptions/cached_file_folder) | Le dossier pour les fichiers temporaires qui peuvent être utilisés comme cache de données.|
| [validate_merged_areas](/cells/python-net/fr/aspose.cells/htmlsaveoptions/validate_merged_areas) | Indique si les cellules fusionnées doivent être validées avant d'enregistrer le fichier.|
| [merge_areas](/cells/python-net/fr/aspose.cells/htmlsaveoptions/merge_areas) | Indique si les zones de mise en forme conditionnelle et de validation doivent être fusionnées avant d'enregistrer le fichier.|
| [create_directory](/cells/python-net/fr/aspose.cells/htmlsaveoptions/create_directory) | Si vrai et que le répertoire n'existe pas, le répertoire sera automatiquement créé avant d'enregistrer le fichier.|
| [sort_names](/cells/python-net/fr/aspose.cells/htmlsaveoptions/sort_names) |Indique si les noms définis doivent être triés avant l'enregistrement du fichier.|
| [sort_external_names](/cells/python-net/fr/aspose.cells/htmlsaveoptions/sort_external_names) | Indique si les noms externes définis doivent être triés avant l'enregistrement du fichier.|
| [refresh_chart_cache](/cells/python-net/fr/aspose.cells/htmlsaveoptions/refresh_chart_cache) | Indique si l'actualisation des données du cache du graphique|
| [check_excel_restriction](/cells/python-net/fr/aspose.cells/htmlsaveoptions/check_excel_restriction) | Vérifiez si la restriction du fichier Excel est vérifiée lorsque l'utilisateur modifie les objets liés aux cellules.<br/>Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.<br/> Lorsque vous saisissez une valeur supérieure à 32 Ko, elle sera tronquée.|
| [update_smart_art](/cells/python-net/fr/aspose.cells/htmlsaveoptions/update_smart_art) | Indique si la mise à jour du paramètre Smart Art est en cours.<br/> La valeur par défaut est false.|
| [encrypt_document_properties](/cells/python-net/fr/aspose.cells/htmlsaveoptions/encrypt_document_properties) | Indique si les propriétés du document doivent être cryptées lors de l'enregistrement en tant que fichier .xls.<br/> La valeur par défaut est vrai.|
| [ignore_invisible_shapes](/cells/python-net/fr/aspose.cells/htmlsaveoptions/ignore_invisible_shapes) | Indiquez si vous souhaitez exporter ces formes non visibles|
| [page_title](/cells/python-net/fr/aspose.cells/htmlsaveoptions/page_title) | Le titre de la page html.<br/> Uniquement pour l'enregistrement dans un flux HTML.|
| [attached_files_directory](/cells/python-net/fr/aspose.cells/htmlsaveoptions/attached_files_directory) | Le répertoire dans lequel les fichiers joints seront enregistrés.<br/> Uniquement pour l'enregistrement dans un flux HTML.|
| [attached_files_url_prefix](/cells/python-net/fr/aspose.cells/htmlsaveoptions/attached_files_url_prefix) | Spécifiez le préfixe d'URL des fichiers joints tels que l'image dans le fichier HTML.<br/> Uniquement pour l'enregistrement dans un flux HTML.|
| [default_font_name](/cells/python-net/fr/aspose.cells/htmlsaveoptions/default_font_name) | Spécifiez le nom de police par défaut pour l'exportation HTML, la police par défaut sera utilisée lorsque la police de style n'existe pas,<br/>Si cette propriété est nulle, Aspose.Cells utilisera une police universelle qui a la même famille que la police d'origine,<br/> la valeur par défaut est null.|
| [add_generic_font](/cells/python-net/fr/aspose.cells/htmlsaveoptions/add_generic_font) |Indique s'il faut ajouter une police générique à la famille de polices CSS.<br/> La valeur par défaut est vrai|
| [worksheet_scalable](/cells/python-net/fr/aspose.cells/htmlsaveoptions/worksheet_scalable) | Indique si vous effectuez un zoom avant ou arrière sur le HTML via le niveau de zoom de la feuille de calcul lors de l'enregistrement du fichier au format HTML, la valeur par défaut est faux.|
| [is_export_comments](/cells/python-net/fr/aspose.cells/htmlsaveoptions/is_export_comments) | Indique si l'exportation des commentaires lors de l'enregistrement du fichier au format HTML est effectuée, la valeur par défaut est false.|
| [export_comments_type](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_comments_type) | Représente le type d'exportation de commentaires vers des fichiers HTML.|
| [disable_downlevel_revealed_comments](/cells/python-net/fr/aspose.cells/htmlsaveoptions/disable_downlevel_revealed_comments) | Indique si les commentaires conditionnels révélés au niveau inférieur sont désactivés lors de l'exportation du fichier au format HTML, la valeur par défaut est false.|
| [is_exp_image_to_temp_dir](/cells/python-net/fr/aspose.cells/htmlsaveoptions/is_exp_image_to_temp_dir) | Indique si les fichiers image doivent être exportés vers le répertoire temporaire.<br/> Uniquement pour l'enregistrement dans un flux HTML.|
| [image_scalable](/cells/python-net/fr/aspose.cells/htmlsaveoptions/image_scalable) | Indique si une unité évolutive est utilisée pour décrire la largeur de l'image<br/>lors de l'utilisation d'une unité évolutive pour décrire la largeur de la colonne.<br/> La valeur par défaut est vrai.|
| [width_scalable](/cells/python-net/fr/aspose.cells/htmlsaveoptions/width_scalable) | Indique si la largeur de la colonne doit être exportée en unité d'échelle vers HTML.<br/> La valeur par défaut est false.|
| [export_single_tab](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_single_tab) | Indique si l'exportation de l'onglet unique est nécessaire lorsque le fichier ne contient qu'une seule feuille de calcul.<br/> La valeur par défaut est false.|
| [export_images_as_base64](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_images_as_base64) | Spécifie si les images sont enregistrées au format Base64 au format HTML, MHTML ou EPUB.|
| [export_active_worksheet_only](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_active_worksheet_only) | Indique si seule la feuille de calcul active est exportée vers un fichier HTML.<br/>Si vrai, seule la feuille de calcul active sera exportée vers un fichier HTML ;<br/>Si faux, le classeur entier sera exporté vers un fichier HTML.<br/> La valeur par défaut est false.|
| [export_print_area_only](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_print_area_only) |Indique si seule la zone d'impression est exportée vers un fichier HTML. La valeur par défaut est « false ».|
| [export_area](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_area) | Obtient ou définit la CellArea d'exportation de la feuille de calcul active actuelle.<br/>Si vous définissez cet attribut, la zone d'impression de la feuille de calcul active actuelle sera omise.<br/> Seule la zone spécifiée sera exportée lors de l'enregistrement du fichier au format HTML.|
| [parse_html_tag_in_cell](/cells/python-net/fr/aspose.cells/htmlsaveoptions/parse_html_tag_in_cell) | Indique si la balise HTML (telle que `<div></div>`) dans la cellule doit être analysée comme valeur de cellule ou conservée telle quelle.<br/> La valeur par défaut est vrai.|
| [html_cross_string_type](/cells/python-net/fr/aspose.cells/htmlsaveoptions/html_cross_string_type) | Indique si une chaîne intercellulaire sera affichée de la même manière que MS Excel lors de l'enregistrement d'un fichier Excel au format HTML.<br/>Par défaut, la valeur est Default, donc, pour les chaînes intercellulaires, il y a peu de différence entre les fichiers HTML créés par Aspose.Cells et MS Excel.<br/> Mais les performances pour la création de fichiers HTML volumineux, en définissant la valeur sur Cross, seraient plusieurs fois plus rapides que de la définir sur Default ou Fit2Cell.|
| [hidden_col_display_type](/cells/python-net/fr/aspose.cells/htmlsaveoptions/hidden_col_display_type) | Colonne cachée (la largeur de cette colonne est 0) dans Excel, avant de l'enregistrer au format HTML,<br/>si HtmlHiddenColDisplayType est « Supprimer », la colonne masquée ne sera pas affichée,<br/> si la valeur est « Masqué », la colonne aurait été affichée, mais elle était masquée, la valeur par défaut est « Masqué »|
| [hidden_row_display_type](/cells/python-net/fr/aspose.cells/htmlsaveoptions/hidden_row_display_type) | Ligne cachée (la hauteur de cette ligne est 0) dans Excel, avant de l'enregistrer au format HTML,<br/>si HtmlHiddenRowDisplayType est « Supprimer », la ligne masquée ne sera pas affichée,<br/>si la valeur est « Masqué », la ligne aurait été affichée, mais elle était masquée, la valeur par défaut est « Masqué »|
| [encoding](/cells/python-net/fr/aspose.cells/htmlsaveoptions/encoding) | S'il n'est pas défini, utilisez Encoding.UTF8 comme type d'encodage par défaut.|
| [image_options](/cells/python-net/fr/aspose.cells/htmlsaveoptions/image_options) | Récupérez l'objet ImageOrPrintOptions avant l'exportation|
| [save_as_single_file](/cells/python-net/fr/aspose.cells/htmlsaveoptions/save_as_single_file) | Indique si le code HTML doit être enregistré sous forme de fichier unique.<br/> La valeur par défaut est false.|
| [show_all_sheets](/cells/python-net/fr/aspose.cells/htmlsaveoptions/show_all_sheets) | Indique si toutes les feuilles doivent être affichées lors de l'enregistrement sous forme de fichier HTML unique.|
| [export_page_headers](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_page_headers) | Indique si les en-têtes de page doivent être exportés.|
| [export_page_footers](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_page_footers) | Indique si les en-têtes de page doivent être exportés.|
| [export_hidden_worksheet](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_hidden_worksheet) | Indique si le contenu de la feuille de calcul masquée doit être exporté. La valeur par défaut est true.|
| [presentation_preference](/cells/python-net/fr/aspose.cells/htmlsaveoptions/presentation_preference) | Indique si le fichier HTML ou MHT est la préférence de présentation.<br/>La valeur par défaut est false.<br/> si vous souhaitez obtenir une présentation plus belle, veuillez définir la valeur sur vrai.|
| [cell_css_prefix](/cells/python-net/fr/aspose.cells/htmlsaveoptions/cell_css_prefix) | Obtient et définit le préfixe du nom CSS, la valeur par défaut est "".|
| [table_css_id](/cells/python-net/fr/aspose.cells/htmlsaveoptions/table_css_id) | Obtient et définit le préfixe du nom de type CSS tel que tr, col, td, etc., ils sont contenus dans l'élément de table<br/> qui possède l'attribut TableCssId spécifique. La valeur par défaut est « ».|
| [is_full_path_link](/cells/python-net/fr/aspose.cells/htmlsaveoptions/is_full_path_link) |Indique si le lien de chemin complet est utilisé dans sheet00x.htm, filelist.xml et tabstrip.htm.<br/> La valeur par défaut est false.|
| [export_worksheet_css_separately](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_worksheet_css_separately) | Indique si vous souhaitez exporter le CSS de la feuille de calcul séparément. La valeur par défaut est false.|
| [export_similar_border_style](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_similar_border_style) | Indique si l'exportation du style de bordure similaire est nécessaire lorsque le style de bordure n'est pas pris en charge par les navigateurs.<br/>Si vous souhaitez importer le fichier html ou mht dans Excel, veuillez conserver la valeur par défaut.<br/> La valeur par défaut est false.|
| [merge_empty_td_forcely](/cells/python-net/fr/aspose.cells/htmlsaveoptions/merge_empty_td_forcely) | Indique si la fusion de l'élément TD vide est forcée lors de l'exportation du fichier au format HTML.<br/> La taille du fichier HTML sera considérablement réduite après avoir défini la valeur sur « true ». La valeur par défaut est « false ».<br/> Si vous souhaitez importer le fichier HTML vers Excel ou exporter des lignes de grille parfaites lors de l'enregistrement du fichier au format HTML,<br/> veuillez conserver la valeur par défaut.|
| [merge_empty_td_type](/cells/python-net/fr/aspose.cells/htmlsaveoptions/merge_empty_td_type) | L'option permettant de fusionner des cellules vides contiguës (éléments td vides)<br/> La valeur par défaut est MergeEmptyTdType.Default.|
| [export_cell_coordinate](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_cell_coordinate) | Indique si les coordonnées des cellules non vides doivent être exportées lors de l'enregistrement du fichier au format HTML. La valeur par défaut est « false ».<br/> Si vous souhaitez importer la sortie HTML vers Excel, veuillez conserver la valeur par défaut.|
| [export_extra_headings](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_extra_headings) | Indique si des titres supplémentaires doivent être exportés lorsque la longueur du texte est supérieure à la colonne d'affichage maximale.<br/> La valeur par défaut est « false ». Si vous souhaitez importer le fichier HTML vers Excel, veuillez conserver la valeur par défaut.|
| [export_headings](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_headings) |Indique si les en-têtes de ligne et de colonne de la feuille sont exportés lors de l'enregistrement dans des fichiers HTML.|
| [export_row_column_headings](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_row_column_headings) |Indique si les en-têtes de ligne et de colonne de la feuille sont exportés lors de l'enregistrement dans des fichiers HTML.|
| [export_formula](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_formula) | Indique si la formule doit être exportée lors de l'enregistrement du fichier au format HTML. La valeur par défaut est « true ».<br/> Si vous souhaitez importer la sortie HTML vers Excel, veuillez conserver la valeur par défaut.|
| [add_tooltip_text](/cells/python-net/fr/aspose.cells/htmlsaveoptions/add_tooltip_text) | Indique s'il faut ajouter du texte d'info-bulle lorsque les données ne peuvent pas être entièrement affichées.<br/> La valeur par défaut est false.|
| [export_grid_lines](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_grid_lines) | Indique si les lignes de la grille doivent être exportées. La valeur par défaut est false.|
| [export_bogus_row_data](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_bogus_row_data) | Indique si les données de la ligne inférieure sont exportées. La valeur par défaut est « true ». Si vous souhaitez importer le fichier HTML ou MHT<br/> pour exceller, veuillez conserver la valeur par défaut.|
| [exclude_unused_styles](/cells/python-net/fr/aspose.cells/htmlsaveoptions/exclude_unused_styles) | Indique si les styles inutilisés sont exclus.<br/>Pour les fichiers HTML générés, l'exclusion des styles inutilisés peut réduire la taille du fichier<br/>sans affecter les effets visuels. La valeur par défaut de cette propriété est donc « true ».<br/>Si l'utilisateur doit conserver tous les styles du classeur pour le code HTML généré (comme dans le cas où l'utilisateur<br/> (vous devez restaurer le classeur à partir du code HTML généré ultérieurement), veuillez définir cette propriété sur false.|
| [export_document_properties](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_document_properties) | Indique si les propriétés du document sont exportées. La valeur par défaut est true. Si vous souhaitez importer<br/> le fichier html ou mht vers excel, veuillez conserver la valeur par défaut.|
| [export_worksheet_properties](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_worksheet_properties) | Indique si les propriétés de la feuille de calcul sont exportées. La valeur par défaut est true. Si vous souhaitez importer<br/> le fichier html ou mht vers excel, veuillez conserver la valeur par défaut.|
| [export_workbook_properties](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_workbook_properties) |Indique si les propriétés du classeur doivent être exportées. La valeur par défaut est true. Si vous souhaitez importer<br/> le fichier html ou mht vers excel, veuillez conserver la valeur par défaut.|
| [export_frame_scripts_and_properties](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_frame_scripts_and_properties) | Indique si les scripts de cadre et les propriétés du document doivent être exportés. La valeur par défaut est « true ». Si vous souhaitez importer le fichier HTML ou MHT<br/> pour exceller, veuillez conserver la valeur par défaut.|
| [export_data_options](/cells/python-net/fr/aspose.cells/htmlsaveoptions/export_data_options) | Indique la règle d'exportation des données du fichier HTML. La valeur par défaut est Tout.|
| [link_target_type](/cells/python-net/fr/aspose.cells/htmlsaveoptions/link_target_type) | Indique le type d'attribut cible dans le lien `<a>`. La valeur par défaut est HtmlLinkTargetType.Parent.|
| [is_ie_compatible](/cells/python-net/fr/aspose.cells/htmlsaveoptions/is_ie_compatible) | Indique si la sortie HTML est compatible avec le navigateur IE.<br/> La valeur par défaut est false|
| [format_data_ignore_column_width](/cells/python-net/fr/aspose.cells/htmlsaveoptions/format_data_ignore_column_width) | Indique si l'ensemble des données formatées de la cellule doit être affiché en cas de débordement de la colonne.<br/>Si vrai, ignorez la largeur de la colonne et toutes les données de la cellule seront exportées.<br/>Si faux, les données seront exportées de la même manière qu'Excel.<br/> La valeur par défaut est false.|
| [calculate_formula](/cells/python-net/fr/aspose.cells/htmlsaveoptions/calculate_formula) | Indique s'il faut calculer les formules avant d'enregistrer le fichier HTML.|
| [is_js_browser_compatible](/cells/python-net/fr/aspose.cells/htmlsaveoptions/is_js_browser_compatible) | Indique si JavaScript est compatible avec les navigateurs qui ne prennent pas en charge JavaScript.<br/> La valeur par défaut est vrai.|
| [is_mobile_compatible](/cells/python-net/fr/aspose.cells/htmlsaveoptions/is_mobile_compatible) | Indique si la sortie HTML est compatible avec les appareils mobiles.<br/> La valeur par défaut est false.|
| [css_styles](/cells/python-net/fr/aspose.cells/htmlsaveoptions/css_styles) | Obtient ou définit les styles CSS supplémentaires pour le formateur.<br/>Fonctionne uniquement lorsque [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/fr/aspose.cells/htmlsaveoptions#save_as_single_file) est vrai.<br/><br/> CssStyles="corps { rembourrage : 5px }";|
| [hide_overflow_wrapped_text](/cells/python-net/fr/aspose.cells/htmlsaveoptions/hide_overflow_wrapped_text) |Indique s'il faut masquer le texte de débordement lorsque le format de cellule est défini pour renvoyer le texte à la ligne.<br/> La valeur par défaut est false|
| [is_border_collapsed](/cells/python-net/fr/aspose.cells/htmlsaveoptions/is_border_collapsed) | Indique si les bordures du tableau sont réduites.<br/> La valeur par défaut est vrai.|
| [encode_entity_as_code](/cells/python-net/fr/aspose.cells/htmlsaveoptions/encode_entity_as_code) | Indique si les entités de caractères HTML sont remplacées par un code décimal.<br/>(par exemple, « &nbsp; » est remplacé par « &#160; »).<br/> La valeur par défaut est false.|
| [office_math_output_mode](/cells/python-net/fr/aspose.cells/htmlsaveoptions/office_math_output_mode) | Indique comment exporter les objets OfficeMath vers HTML, la valeur par défaut est Image.|
| [cell_name_attribute](/cells/python-net/fr/aspose.cells/htmlsaveoptions/cell_name_attribute) | Spécifie l'attribut qui indique le CellName à écrire.<br/>(par exemple, si la valeur est « id », alors pour la cellule « A1 », la sortie sera :<td id='A1'>).<br/> La valeur par défaut est null.|
| [disable_css](/cells/python-net/fr/aspose.cells/htmlsaveoptions/disable_css) | Indique si seuls les styles en ligne sont appliqués, sans s'appuyer sur CSS.<br/> La valeur par défaut est false.|
| [enable_css_custom_properties](/cells/python-net/fr/aspose.cells/htmlsaveoptions/enable_css_custom_properties) | Optimisez la sortie HTML en utilisant des propriétés CSS personnalisées. Par exemple, dans le cas où une image base64 présente plusieurs occurrences, les données de l'image ne doivent être enregistrées qu'une seule fois grâce à la propriété personnalisée, ce qui améliore les performances du code HTML obtenu.<br/> La valeur par défaut est false.|
| [html_version](/cells/python-net/fr/aspose.cells/htmlsaveoptions/html_version) | Spécifie la version de la norme HTML qui doit être utilisée lors de l'enregistrement du format HTML.<br/> La valeur par défaut est HtmlVersion.Default.|
| [sheet_set](/cells/python-net/fr/aspose.cells/htmlsaveoptions/sheet_set) | Obtient ou définit les feuilles à afficher. Par défaut, toutes les feuilles du classeur sont visibles : [`SheetSet.visible`](/cells/python-net/fr/aspose.cells.rendering/sheetset#visible).|



###  Voir également
* module [`aspose.cells`](..)
* classe [`HtmlSaveOptions`](/cells/python-net/fr/aspose.cells/htmlsaveoptions)
* classe [`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)
