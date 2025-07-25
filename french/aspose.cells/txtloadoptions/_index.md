---
title: TxtLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1490
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
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/txtloadoptions/__init__/#) | Crée les options de chargement du fichier texte.|
| [`__init__(self, load_format)`](/cells/python-net/fr/aspose.cells/txtloadoptions/__init__/#aspose.cells.loadformat) | Crée les options de chargement du fichier texte.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [load_format](/cells/python-net/fr/aspose.cells/txtloadoptions/load_format) | Obtient le format de chargement.|
| [password](/cells/python-net/fr/aspose.cells/txtloadoptions/password) | Obtient et définit le mot de passe du classeur.|
| [parsing_formula_on_open](/cells/python-net/fr/aspose.cells/txtloadoptions/parsing_formula_on_open) | Indique si l'analyse de la formule est effectuée lors de la lecture du fichier.|
| [parsing_pivot_cached_records](/cells/python-net/fr/aspose.cells/txtloadoptions/parsing_pivot_cached_records) | Indique si l'analyse des enregistrements mis en cache pivot est effectuée lors du chargement du fichier.<br/> La valeur par défaut est false.|
| [language_code](/cells/python-net/fr/aspose.cells/txtloadoptions/language_code) | Obtient ou définit la langue de l'interface utilisateur de la version du classeur en fonction du CountryCode qui a enregistré le fichier.|
| [region](/cells/python-net/fr/aspose.cells/txtloadoptions/region) | Obtient ou définit les paramètres régionaux utilisés pour le classeur qui sera chargé.|
| [default_style_settings](/cells/python-net/fr/aspose.cells/txtloadoptions/default_style_settings) | Obtient les paramètres de style par défaut pour l'initialisation des styles du classeur|
| [standard_font](/cells/python-net/fr/aspose.cells/txtloadoptions/standard_font) | Définit le nom de police standard par défaut|
| [standard_font_size](/cells/python-net/fr/aspose.cells/txtloadoptions/standard_font_size) | Définit la taille de police standard par défaut.|
| [ignore_not_printed](/cells/python-net/fr/aspose.cells/txtloadoptions/ignore_not_printed) | Ignorer les données qui ne sont pas imprimées si vous imprimez directement le fichier|
| [check_data_valid](/cells/python-net/fr/aspose.cells/txtloadoptions/check_data_valid) | Vérifiez si les données sont valides dans le fichier modèle.|
| [check_excel_restriction](/cells/python-net/fr/aspose.cells/txtloadoptions/check_excel_restriction) | Vérifiez si la restriction du fichier Excel est vérifiée lorsque l'utilisateur modifie les objets liés aux cellules.<br/>Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.<br/>Lorsque vous saisissez une valeur supérieure à 32 Ko, comme par exemple Cell.PutValue(string), si cette propriété est vraie, vous obtiendrez une exception.<br/>Si cette propriété est fausse, nous accepterons la valeur de votre chaîne d'entrée comme valeur de la cellule afin que plus tard<br/>vous pouvez générer la valeur de chaîne complète pour d'autres formats de fichiers tels que CSV.<br/>Cependant, si vous avez défini un type de valeur qui n'est pas valide pour le format de fichier Excel,<br/>Vous ne devez pas enregistrer le classeur au format Excel ultérieurement. Sinon, une erreur inattendue pourrait se produire dans le fichier Excel généré.|
| [keep_unparsed_data](/cells/python-net/fr/aspose.cells/txtloadoptions/keep_unparsed_data) | Conserver les données non analysées en mémoire lors du chargement du classeur à partir du fichier modèle. La valeur par défaut est « true ».|
| [load_filter](/cells/python-net/fr/aspose.cells/txtloadoptions/load_filter) | Le filtre pour indiquer comment charger les données.|
| [memory_setting](/cells/python-net/fr/aspose.cells/txtloadoptions/memory_setting) | Obtient ou définit le mode mémoire pour le classeur chargé.|
| [auto_fitter_options](/cells/python-net/fr/aspose.cells/txtloadoptions/auto_fitter_options) | Obtient et définit les options d'ajustement automatique|
| [auto_filter](/cells/python-net/fr/aspose.cells/txtloadoptions/auto_filter) | Indique si le filtrage automatique des données est effectué lors du chargement des fichiers.|
| [font_configs](/cells/python-net/fr/aspose.cells/txtloadoptions/font_configs) | Obtient et définit les configurations de polices individuelles.<br/> Fonctionne uniquement pour le [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) qui utilise ce [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions) pour charger.|
| [ignore_useless_shapes](/cells/python-net/fr/aspose.cells/txtloadoptions/ignore_useless_shapes) | Indique si les formes inutiles sont ignorées.|
| [preserve_padding_spaces_in_formula](/cells/python-net/fr/aspose.cells/txtloadoptions/preserve_padding_spaces_in_formula) | Indique si les espaces et les sauts de ligne qui sont remplis entre les jetons de formule doivent être conservés<br/>tout en obtenant et en définissant des formules.<br/> La valeur par défaut est faux.|
| [encoding](/cells/python-net/fr/aspose.cells/txtloadoptions/encoding) | Obtient et définit l'encodage par défaut. S'applique uniquement aux fichiers CSV.|
| [load_style_strategy](/cells/python-net/fr/aspose.cells/txtloadoptions/load_style_strategy) | Indique la stratégie à appliquer pour appliquer le style aux valeurs analysées lors de la conversion d'une valeur de chaîne en nombre ou en date/heure.|
| [convert_numeric_data](/cells/python-net/fr/aspose.cells/txtloadoptions/convert_numeric_data) |Obtient ou définit une valeur qui indique si la chaîne du fichier texte est convertie en données numériques.|
| [convert_date_time_data](/cells/python-net/fr/aspose.cells/txtloadoptions/convert_date_time_data) | Obtient ou définit une valeur qui indique si la chaîne du fichier texte est convertie en données de date.|
| [keep_precision](/cells/python-net/fr/aspose.cells/txtloadoptions/keep_precision) | Indique s'il ne faut pas analyser une valeur de chaîne si la longueur est de 15.|
| [separator](/cells/python-net/fr/aspose.cells/txtloadoptions/separator) | Obtient et définit le séparateur de caractères du fichier texte.|
| [separator_string](/cells/python-net/fr/aspose.cells/txtloadoptions/separator_string) | Obtient et définit une valeur de chaîne comme séparateur.|
| [is_multi_encoded](/cells/python-net/fr/aspose.cells/txtloadoptions/is_multi_encoded) | Vrai signifie que le fichier contient plusieurs encodages.|
| [preferred_parsers](/cells/python-net/fr/aspose.cells/txtloadoptions/preferred_parsers) | Obtient et définit les analyseurs de valeurs préférés pour le chargement du fichier texte.|
| [has_formula](/cells/python-net/fr/aspose.cells/txtloadoptions/has_formula) | Indique si le texte est une formule s'il commence par « = ».|
| [has_text_qualifier](/cells/python-net/fr/aspose.cells/txtloadoptions/has_text_qualifier) | Indique si la valeur de la cellule contient un qualificateur de texte. La valeur par défaut est « true ».|
| [text_qualifier](/cells/python-net/fr/aspose.cells/txtloadoptions/text_qualifier) | Spécifie le qualificateur de texte pour les valeurs de cellule. Le qualificateur par défaut est « " ».|
| [treat_consecutive_delimiters_as_one](/cells/python-net/fr/aspose.cells/txtloadoptions/treat_consecutive_delimiters_as_one) | Si les délimiteurs consécutifs doivent être traités comme un seul.|
| [treat_quote_prefix_as_value](/cells/python-net/fr/aspose.cells/txtloadoptions/treat_quote_prefix_as_value) | Indique si le guillemet simple initial doit être considéré comme faisant partie de la valeur d'une cellule.<br/>La valeur par défaut est « true ». Si elle est « false », l'apostrophe initiale sera supprimée de la valeur de la cellule correspondante.<br/> et [`Style.quote_prefix`](/cells/python-net/fr/aspose.cells/style#quote_prefix) sera défini comme vrai pour la cellule.|
| [extend_to_next_sheet](/cells/python-net/fr/aspose.cells/txtloadoptions/extend_to_next_sheet) | S'étend aux données sur la feuille suivante lorsque les lignes ou les colonnes de données dépassent la limite.<br/> La valeur par défaut est faux.|
| [header_rows_count](/cells/python-net/fr/aspose.cells/txtloadoptions/header_rows_count) |Le nombre de lignes d'en-tête à répéter pour les feuilles étendues.|
| [header_columns_count](/cells/python-net/fr/aspose.cells/txtloadoptions/header_columns_count) | Le nombre de colonnes d'en-tête à répéter pour les feuilles étendues.|
| [max_row_count](/cells/python-net/fr/aspose.cells/txtloadoptions/max_row_count) | Le nombre maximal de lignes à importer pour une feuille.|
| [max_column_count](/cells/python-net/fr/aspose.cells/txtloadoptions/max_column_count) | Le nombre maximal de colonnes à importer pour une feuille.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/fr/aspose.cells/txtloadoptions/set_paper_size/#aspose.cells.papersizetype) | Définit la taille du papier d'impression par défaut à partir des paramètres par défaut de l'imprimante.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`AbstractTextLoadOptions`](/cells/python-net/fr/aspose.cells/abstracttextloadoptions)
* classe [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)
* classe [`TxtLoadOptions`](/cells/python-net/fr/aspose.cells/txtloadoptions)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
