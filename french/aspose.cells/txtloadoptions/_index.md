---
title: TxtLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1580
url: /fr/aspose.cells/txtloadoptions/
is_root: false
---
##  TxtLoadOptions classe
Représente les options de chargement du fichier texte.



**Héritage:** [`TxtLoadOptions`](/cells/python-net/aspose.cells/txtloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)



Le type TxtLoadOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/txtloadoptions/__init__/#) | Crée les options de chargement du fichier texte.|
| [__init__](/cells/python-net/fr/aspose.cells/txtloadoptions/__init__/#aspose.cells.LoadFormat) | Crée les options de chargement du fichier texte.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [load_format](/cells/python-net/fr/aspose.cells/txtloadoptions/load_format) | Obtient le format de chargement.|
| [password](/cells/python-net/fr/aspose.cells/txtloadoptions/password) | Obtient et définit le mot de passe du classeur.|
| [parsing_formula_on_open](/cells/python-net/fr/aspose.cells/txtloadoptions/parsing_formula_on_open) | Indique si l'analyse de la formule lors de la lecture du fichier.|
| [parsing_pivot_cached_records](/cells/python-net/fr/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Indique si l’analyse des enregistrements mis en cache par pivot lors du chargement du fichier.<br/> La valeur par défaut est fausse.|
| [language_code](/cells/python-net/fr/aspose.cells/txtloadoptions/language_code) | Obtient ou définit la langue de l'interface utilisateur de la version du Workbook en fonction du CountryCode qui a enregistré le fichier.|
| [region](/cells/python-net/fr/aspose.cells/txtloadoptions/region) |Obtient ou définit les paramètres régionaux du système en fonction de CountryCode au moment du chargement du fichier.|
| [default_style_settings](/cells/python-net/fr/aspose.cells/txtloadoptions/default_style_settings) | Obtient les paramètres de style par défaut pour initialiser les styles du classeur|
| [standard_font](/cells/python-net/fr/aspose.cells/txtloadoptions/standard_font) | Définit le nom de police standard par défaut|
| [standard_font_size](/cells/python-net/fr/aspose.cells/txtloadoptions/standard_font_size) | Définit la taille de police standard par défaut.|
| [interrupt_monitor](/cells/python-net/fr/aspose.cells/txtloadoptions/interrupt_monitor) | Obtient et définit le moniteur d'interruption.|
| [ignore_not_printed](/cells/python-net/fr/aspose.cells/txtloadoptions/ignore_not_printed) | Ignorer les données qui ne sont pas imprimées si vous imprimez directement le fichier|
| [check_data_valid](/cells/python-net/fr/aspose.cells/txtloadoptions/check_data_valid) | Vérifiez si les données sont valides dans le fichier modèle.|
| [check_excel_restriction](/cells/python-net/fr/aspose.cells/txtloadoptions/check_excel_restriction) | Vérifier ou non la restriction du fichier Excel lorsque l'utilisateur modifie les objets liés aux cellules.<br/>Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.<br/>Lorsque vous saisissez une valeur supérieure à 32 Ko, par exemple Cell.PutValue(string), si cette propriété est vraie, vous obtiendrez une exception.<br/>Si cette propriété est fausse, nous accepterons la valeur de votre chaîne d'entrée comme valeur de la cellule afin que plus tard<br/>vous pouvez afficher la valeur de chaîne complète pour d'autres formats de fichiers tels que CSV.<br/>Cependant, si vous avez défini un type de valeur non valide pour le format de fichier Excel,<br/> vous ne devez pas enregistrer le classeur au format de fichier Excel ultérieurement. Sinon, une erreur inattendue pourrait se produire pour le fichier Excel généré.|
| [keep_unparsed_data](/cells/python-net/fr/aspose.cells/txtloadoptions/keep_unparsed_data) | Indique si les données non analysées sont conservées en mémoire pour le classeur lorsqu'il est chargé à partir du fichier modèle. La valeur par défaut est vraie.|
| [load_filter](/cells/python-net/fr/aspose.cells/txtloadoptions/load_filter) | Le filtre pour indiquer comment charger les données.|
| [light_cells_data_handler](/cells/python-net/fr/aspose.cells/txtloadoptions/light_cells_data_handler) | Le gestionnaire de données pour traiter les données des cellules lors de la lecture du fichier modèle.|
| [memory_setting](/cells/python-net/fr/aspose.cells/txtloadoptions/memory_setting) | Obtient ou définit les options d'utilisation de la mémoire.|
| [warning_callback](/cells/python-net/fr/aspose.cells/txtloadoptions/warning_callback) | Obtient ou définit un rappel d’avertissement.|
| [auto_fitter_options](/cells/python-net/fr/aspose.cells/txtloadoptions/auto_fitter_options) | Obtient et définit les options d'ajustement automatique|
| [auto_filter](/cells/python-net/fr/aspose.cells/txtloadoptions/auto_filter) | Indique si le filtrage automatique des données lors du chargement des fichiers est effectué.|
| [font_configs](/cells/python-net/fr/aspose.cells/txtloadoptions/font_configs) | Obtient et définit des configurations de police individuelles.<br/> Fonctionne uniquement pour le [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) qui utilise ce [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions) pour charger.|
| [ignore_useless_shapes](/cells/python-net/fr/aspose.cells/txtloadoptions/ignore_useless_shapes) | Indique si les formes inutiles sont ignorées.|
| [preserve_padding_spaces_in_formula](/cells/python-net/fr/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | Indique si les espaces et les sauts de ligne qui sont remplis entre les jetons de formule sont conservés<br/>tout en obtenant et en définissant des formules.<br/> La valeur par défaut est fausse.|
| [encoding](/cells/python-net/fr/aspose.cells/txtloadoptions/encoding) |Obtient et définit l'encodage par défaut. S'applique uniquement au fichier csv.|
| [load_style_strategy](/cells/python-net/fr/aspose.cells/txtloadoptions/load_style_strategy) | Indique la stratégie pour appliquer le style aux valeurs analysées lors de la conversion d'une valeur de chaîne en nombre ou en datetime.|
| [convert_numeric_data](/cells/python-net/fr/aspose.cells/txtloadoptions/convert_numeric_data) | Obtient ou définit une valeur qui indique si la chaîne du fichier texte est convertie en données numériques.|
| [convert_date_time_data](/cells/python-net/fr/aspose.cells/txtloadoptions/convert_date_time_data) | Obtient ou définit une valeur qui indique si la chaîne du fichier texte est convertie en données de date.|
| [keep_precision](/cells/python-net/fr/aspose.cells/txtloadoptions/keep_precision) | Indique si une valeur de chaîne n'est pas analysée si la longueur est de 15.|
| [separator](/cells/python-net/fr/aspose.cells/txtloadoptions/separator) | Obtient et définit le séparateur de caractères du fichier texte.|
| [separator_string](/cells/python-net/fr/aspose.cells/txtloadoptions/separator_string) | Obtient et définit une valeur de chaîne comme séparateur.|
| [is_multi_encoded](/cells/python-net/fr/aspose.cells/txtloadoptions/is_multi_encoded) |True signifie que le fichier contient plusieurs encodages.|
| [preferred_parsers](/cells/python-net/fr/aspose.cells/txtloadoptions/preferred_parsers) | Obtient et définit les analyseurs de valeurs préférées pour le chargement du fichier texte.|
| [has_formula](/cells/python-net/fr/aspose.cells/txtloadoptions/has_formula) | Indique si le texte est une formule s'il commence par "=".|
| [has_text_qualifier](/cells/python-net/fr/aspose.cells/txtloadoptions/has_text_qualifier) | S'il existe un qualificatif de texte pour la valeur de cellule. La valeur par défaut est vraie.|
| [text_qualifier](/cells/python-net/fr/aspose.cells/txtloadoptions/text_qualifier) | Spécifie le qualificateur de texte pour les valeurs de cellule. Le qualificatif par défaut est '"'.|
| [treat_consecutive_delimiters_as_one](/cells/python-net/fr/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Indique si les délimiteurs consécutifs doivent être traités comme un seul.|
| [treat_quote_prefix_as_value](/cells/python-net/fr/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Indique si le guillemet simple de début doit être considéré comme faisant partie de la valeur d’une cellule.<br/>La valeur par défaut est vraie. S'il est faux, le guillemet simple de début sera supprimé de la valeur de la cellule correspondante<br/> et [`Style.quote_prefix`](/cells/python-net/fr/aspose.cells/style#quote_prefix) seront définis comme vrai pour la cellule.|
| [extend_to_next_sheet](/cells/python-net/fr/aspose.cells/txtloadoptions/extend_to_next_sheet) | Indique si les données s'étendent à la feuille suivante lorsque les lignes ou les colonnes de données dépassent la limite.<br/> La valeur par défaut est fausse.|
| [header_rows_count](/cells/python-net/fr/aspose.cells/txtloadoptions/header_rows_count) | Nombre de lignes d'en-tête à répéter pour les feuilles étendues.|
| [header_columns_count](/cells/python-net/fr/aspose.cells/txtloadoptions/header_columns_count) | Nombre de colonnes d'en-tête à répéter pour les feuilles étendues.|
| [max_row_count](/cells/python-net/fr/aspose.cells/txtloadoptions/max_row_count) | Nombre maximum de lignes à importer pour une feuille.|
| [max_column_count](/cells/python-net/fr/aspose.cells/txtloadoptions/max_column_count) | Nombre maximum de colonnes à importer pour une feuille.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [set_paper_size](/cells/python-net/fr/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Définit le format de papier d'impression par défaut à partir des paramètres par défaut de l'imprimante.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`AbstractTextLoadOptions`](/cells/python-net/fr/aspose.cells/abstracttextloadoptions)
* classe [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)
* classe [`TxtLoadOptions`](/cells/python-net/fr/aspose.cells/txtloadoptions)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
