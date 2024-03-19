---
title: XmlLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1760
url: /fr/aspose.cells/xmlloadoptions/
is_root: false
---
##  XmlLoadOptions classe
Représente les options de chargement de XML.



**Héritage:** [`XmlLoadOptions`](/cells/python-net/aspose.cells/xmlloadoptions) → 
[`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)



Le type XmlLoadOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/xmlloadoptions/__init__/#) | Représente les options de chargement du fichier XML.|
| [__init__](/cells/python-net/fr/aspose.cells/xmlloadoptions/__init__/#aspose.cells.LoadFormat) | Représente les options de chargement du fichier XML.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [load_format](/cells/python-net/fr/aspose.cells/xmlloadoptions/load_format) | Obtient le format de chargement.|
| [password](/cells/python-net/fr/aspose.cells/xmlloadoptions/password) | Obtient et définit le mot de passe du classeur.|
| [parsing_formula_on_open](/cells/python-net/fr/aspose.cells/xmlloadoptions/parsing_formula_on_open) | Indique si l'analyse de la formule lors de la lecture du fichier.|
| [parsing_pivot_cached_records](/cells/python-net/fr/aspose.cells/xmlloadoptions/parsing_pivot_cached_records) | Indique si l’analyse des enregistrements mis en cache par pivot lors du chargement du fichier.<br/> La valeur par défaut est fausse.|
| [language_code](/cells/python-net/fr/aspose.cells/xmlloadoptions/language_code) | Obtient ou définit la langue de l'interface utilisateur de la version du Workbook en fonction du CountryCode qui a enregistré le fichier.|
| [region](/cells/python-net/fr/aspose.cells/xmlloadoptions/region) |Obtient ou définit les paramètres régionaux du système en fonction de CountryCode au moment du chargement du fichier.|
| [default_style_settings](/cells/python-net/fr/aspose.cells/xmlloadoptions/default_style_settings) | Obtient les paramètres de style par défaut pour initialiser les styles du classeur|
| [standard_font](/cells/python-net/fr/aspose.cells/xmlloadoptions/standard_font) | Définit le nom de police standard par défaut|
| [standard_font_size](/cells/python-net/fr/aspose.cells/xmlloadoptions/standard_font_size) | Définit la taille de police standard par défaut.|
| [interrupt_monitor](/cells/python-net/fr/aspose.cells/xmlloadoptions/interrupt_monitor) | Obtient et définit le moniteur d'interruption.|
| [ignore_not_printed](/cells/python-net/fr/aspose.cells/xmlloadoptions/ignore_not_printed) | Ignorer les données qui ne sont pas imprimées si vous imprimez directement le fichier|
| [check_data_valid](/cells/python-net/fr/aspose.cells/xmlloadoptions/check_data_valid) | Vérifiez si les données sont valides dans le fichier modèle.|
| [check_excel_restriction](/cells/python-net/fr/aspose.cells/xmlloadoptions/check_excel_restriction) | Vérifier ou non la restriction du fichier Excel lorsque l'utilisateur modifie les objets liés aux cellules.<br/>Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.<br/>Lorsque vous saisissez une valeur supérieure à 32 Ko, par exemple Cell.PutValue(string), si cette propriété est vraie, vous obtiendrez une exception.<br/>Si cette propriété est fausse, nous accepterons la valeur de votre chaîne d'entrée comme valeur de la cellule afin que plus tard<br/>vous pouvez afficher la valeur de chaîne complète pour d'autres formats de fichiers tels que CSV.<br/>Cependant, si vous avez défini un type de valeur non valide pour le format de fichier Excel,<br/> vous ne devez pas enregistrer le classeur au format de fichier Excel ultérieurement. Sinon, une erreur inattendue pourrait se produire pour le fichier Excel généré.|
| [keep_unparsed_data](/cells/python-net/fr/aspose.cells/xmlloadoptions/keep_unparsed_data) | Indique si les données non analysées sont conservées en mémoire pour le classeur lorsqu'il est chargé à partir du fichier modèle. La valeur par défaut est vraie.|
| [load_filter](/cells/python-net/fr/aspose.cells/xmlloadoptions/load_filter) | Le filtre pour indiquer comment charger les données.|
| [light_cells_data_handler](/cells/python-net/fr/aspose.cells/xmlloadoptions/light_cells_data_handler) | Le gestionnaire de données pour traiter les données des cellules lors de la lecture du fichier modèle.|
| [memory_setting](/cells/python-net/fr/aspose.cells/xmlloadoptions/memory_setting) | Obtient ou définit les options d'utilisation de la mémoire.|
| [warning_callback](/cells/python-net/fr/aspose.cells/xmlloadoptions/warning_callback) | Obtient ou définit un rappel d’avertissement.|
| [auto_fitter_options](/cells/python-net/fr/aspose.cells/xmlloadoptions/auto_fitter_options) | Obtient et définit les options d'ajustement automatique|
| [auto_filter](/cells/python-net/fr/aspose.cells/xmlloadoptions/auto_filter) | Indique si le filtrage automatique des données lors du chargement des fichiers est effectué.|
| [font_configs](/cells/python-net/fr/aspose.cells/xmlloadoptions/font_configs) | Obtient et définit des configurations de police individuelles.<br/> Fonctionne uniquement pour le [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) qui utilise ce [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions) pour charger.|
| [ignore_useless_shapes](/cells/python-net/fr/aspose.cells/xmlloadoptions/ignore_useless_shapes) | Indique si les formes inutiles sont ignorées.|
| [preserve_padding_spaces_in_formula](/cells/python-net/fr/aspose.cells/xmlloadoptions/preserve_padding_spaces_in_formula) | Indique si les espaces et les sauts de ligne qui sont remplis entre les jetons de formule sont conservés<br/>tout en obtenant et en définissant des formules.<br/> La valeur par défaut est fausse.|
| [start_cell](/cells/python-net/fr/aspose.cells/xmlloadoptions/start_cell) | Obtient et définit la cellule de départ.|
| [is_xml_map](/cells/python-net/fr/aspose.cells/xmlloadoptions/is_xml_map) | Indique si le mappage XML vers Excel.<br/> La valeur par défaut est fausse.|
| [contains_multiple_worksheets](/cells/python-net/fr/aspose.cells/xmlloadoptions/contains_multiple_worksheets) | Indique si vous importez du XML sous forme de plusieurs feuilles de calcul.|
| [convert_numeric_or_date](/cells/python-net/fr/aspose.cells/xmlloadoptions/convert_numeric_or_date) | Indique si la valeur du fichier XML est convertie en numérique ou en date.|
| [number_format](/cells/python-net/fr/aspose.cells/xmlloadoptions/number_format) | Obtient et définit le format de la valeur numérique.|
| [date_format](/cells/python-net/fr/aspose.cells/xmlloadoptions/date_format) | Obtient et définit le format de la valeur de date.|
| [ignore_root_attributes](/cells/python-net/fr/aspose.cells/xmlloadoptions/ignore_root_attributes) | Indique si les attributs de l'élément racine sont ignorés.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [set_paper_size](/cells/python-net/fr/aspose.cells/xmlloadoptions/set_paper_size/#aspose.cells.PaperSizeType) | Définit le format de papier d'impression par défaut à partir des paramètres par défaut de l'imprimante.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
* classe [`XmlLoadOptions`](/cells/python-net/fr/aspose.cells/xmlloadoptions)
