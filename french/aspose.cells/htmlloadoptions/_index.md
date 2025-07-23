---
title: HtmlLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 780
url: /fr/aspose.cells/htmlloadoptions/
is_root: false
---
##  HtmlLoadOptions classe
Représente les options lors de l'importation d'un fichier HTML.



**Héritage:** [`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)



Le type HtmlLoadOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/htmlloadoptions/__init__/#) | Crée une option de chargement du fichier.|
| [`__init__(self, load_format)`](/cells/python-net/fr/aspose.cells/htmlloadoptions/__init__/#aspose.cells.loadformat) | Crée une option de chargement du fichier.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [load_format](/cells/python-net/fr/aspose.cells/htmlloadoptions/load_format) | Obtient le format de chargement.|
| [password](/cells/python-net/fr/aspose.cells/htmlloadoptions/password) | Obtient et définit le mot de passe du classeur.|
| [parsing_formula_on_open](/cells/python-net/fr/aspose.cells/htmlloadoptions/parsing_formula_on_open) | Indique si l'analyse de la formule est effectuée lors de la lecture du fichier.|
| [parsing_pivot_cached_records](/cells/python-net/fr/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) | Indique si l'analyse des enregistrements mis en cache pivot est effectuée lors du chargement du fichier.<br/> La valeur par défaut est false.|
| [language_code](/cells/python-net/fr/aspose.cells/htmlloadoptions/language_code) | Obtient ou définit la langue de l'interface utilisateur de la version du classeur en fonction du CountryCode qui a enregistré le fichier.|
| [region](/cells/python-net/fr/aspose.cells/htmlloadoptions/region) | Obtient ou définit les paramètres régionaux utilisés pour le classeur qui sera chargé.|
| [default_style_settings](/cells/python-net/fr/aspose.cells/htmlloadoptions/default_style_settings) | Obtient les paramètres de style par défaut pour l'initialisation des styles du classeur|
| [standard_font](/cells/python-net/fr/aspose.cells/htmlloadoptions/standard_font) | Définit le nom de police standard par défaut|
| [standard_font_size](/cells/python-net/fr/aspose.cells/htmlloadoptions/standard_font_size) | Définit la taille de police standard par défaut.|
| [ignore_not_printed](/cells/python-net/fr/aspose.cells/htmlloadoptions/ignore_not_printed) | Ignorer les données qui ne sont pas imprimées si vous imprimez directement le fichier|
| [check_data_valid](/cells/python-net/fr/aspose.cells/htmlloadoptions/check_data_valid) | Vérifiez si les données sont valides dans le fichier modèle.|
| [check_excel_restriction](/cells/python-net/fr/aspose.cells/htmlloadoptions/check_excel_restriction) | Vérifiez si la restriction du fichier Excel est vérifiée lorsque l'utilisateur modifie les objets liés aux cellules.<br/>Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.<br/>Lorsque vous saisissez une valeur supérieure à 32 Ko, comme par exemple Cell.PutValue(string), si cette propriété est vraie, vous obtiendrez une exception.<br/>Si cette propriété est fausse, nous accepterons la valeur de votre chaîne d'entrée comme valeur de la cellule afin que plus tard<br/>vous pouvez générer la valeur de chaîne complète pour d'autres formats de fichiers tels que CSV.<br/>Cependant, si vous avez défini un type de valeur qui n'est pas valide pour le format de fichier Excel,<br/>Vous ne devez pas enregistrer le classeur au format Excel ultérieurement. Sinon, une erreur inattendue pourrait se produire dans le fichier Excel généré.|
| [keep_unparsed_data](/cells/python-net/fr/aspose.cells/htmlloadoptions/keep_unparsed_data) | Conserver les données non analysées en mémoire lors du chargement du classeur à partir du fichier modèle. La valeur par défaut est « true ».|
| [load_filter](/cells/python-net/fr/aspose.cells/htmlloadoptions/load_filter) | Le filtre pour indiquer comment charger les données.|
| [memory_setting](/cells/python-net/fr/aspose.cells/htmlloadoptions/memory_setting) | Obtient ou définit le mode mémoire pour le classeur chargé.|
| [auto_fitter_options](/cells/python-net/fr/aspose.cells/htmlloadoptions/auto_fitter_options) | Obtient et définit les options d'ajustement automatique|
| [auto_filter](/cells/python-net/fr/aspose.cells/htmlloadoptions/auto_filter) | Indique si le filtrage automatique des données est effectué lors du chargement des fichiers.|
| [font_configs](/cells/python-net/fr/aspose.cells/htmlloadoptions/font_configs) | Obtient et définit les configurations de polices individuelles.<br/> Fonctionne uniquement pour le [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) qui utilise ce [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions) pour charger.|
| [ignore_useless_shapes](/cells/python-net/fr/aspose.cells/htmlloadoptions/ignore_useless_shapes) | Indique si les formes inutiles sont ignorées.|
| [preserve_padding_spaces_in_formula](/cells/python-net/fr/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) | Indique si les espaces et les sauts de ligne qui sont remplis entre les jetons de formule doivent être conservés<br/>tout en obtenant et en définissant des formules.<br/> La valeur par défaut est faux.|
| [encoding](/cells/python-net/fr/aspose.cells/htmlloadoptions/encoding) | Obtient et définit l'encodage par défaut. S'applique uniquement aux fichiers CSV.|
| [load_style_strategy](/cells/python-net/fr/aspose.cells/htmlloadoptions/load_style_strategy) | Indique la stratégie à appliquer pour appliquer le style aux valeurs analysées lors de la conversion d'une valeur de chaîne en nombre ou en date/heure.|
| [convert_numeric_data](/cells/python-net/fr/aspose.cells/htmlloadoptions/convert_numeric_data) |Obtient ou définit une valeur qui indique si la chaîne du fichier texte est convertie en données numériques.|
| [convert_date_time_data](/cells/python-net/fr/aspose.cells/htmlloadoptions/convert_date_time_data) | Obtient ou définit une valeur qui indique si la chaîne du fichier texte est convertie en données de date.|
| [keep_precision](/cells/python-net/fr/aspose.cells/htmlloadoptions/keep_precision) | Indique s'il ne faut pas analyser une valeur de chaîne si la longueur est de 15.|
| [attached_files_directory](/cells/python-net/fr/aspose.cells/htmlloadoptions/attached_files_directory) | Le répertoire dans lequel les fichiers joints seront enregistrés.|
| [load_formulas](/cells/python-net/fr/aspose.cells/htmlloadoptions/load_formulas) | Indique si l'importation de formules si le fichier HTML d'origine contient des formules|
| [support_div_tag](/cells/python-net/fr/aspose.cells/htmlloadoptions/support_div_tag) | Indique si la mise en page de la balise `<div>` est prise en charge lorsque le fichier HTML la contient.<br/> La valeur par défaut est false.|
| [delete_redundant_spaces](/cells/python-net/fr/aspose.cells/htmlloadoptions/delete_redundant_spaces) | Indique si les espaces redondants doivent être supprimés lorsque le texte est renvoyé à la ligne à l'aide de la balise `<br>`.<br/> La valeur par défaut est false.|
| [auto_fit_cols_and_rows](/cells/python-net/fr/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) | Indique si les colonnes et les lignes doivent être ajustées automatiquement. La valeur par défaut est « false ».|
| [convert_formulas_data](/cells/python-net/fr/aspose.cells/htmlloadoptions/convert_formulas_data) |si vrai, convertit la chaîne en formule lorsque la valeur de la chaîne commence par le caractère '=', la valeur par défaut est faux.|
| [has_formula](/cells/python-net/fr/aspose.cells/htmlloadoptions/has_formula) | Indique si le texte est une formule s'il commence par « = ».|
| [prog_id](/cells/python-net/fr/aspose.cells/htmlloadoptions/prog_id) | Obtient l'ID du programme de création du fichier.<br/> Uniquement pour les fichiers MHT.|
| [table_load_options](/cells/python-net/fr/aspose.cells/htmlloadoptions/table_load_options) | Obtenir l'instance HtmlTableLoadOptionCollection|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/fr/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.papersizetype) | Définit la taille du papier d'impression par défaut à partir des paramètres par défaut de l'imprimante.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`AbstractTextLoadOptions`](/cells/python-net/fr/aspose.cells/abstracttextloadoptions)
* classe [`HtmlLoadOptions`](/cells/python-net/fr/aspose.cells/htmlloadoptions)
* classe [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
