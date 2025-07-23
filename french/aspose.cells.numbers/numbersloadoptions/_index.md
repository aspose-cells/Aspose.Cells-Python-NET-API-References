---
title: NumbersLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells.numbers/numbersloadoptions/
is_root: false
---
##  NumbersLoadOptions classe
Représente les options de chargement des fichiers Apple Numbers.



**Héritage:** [`NumbersLoadOptions`](/cells/python-net/aspose.cells.numbers/numbersloadoptions) → 
[`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)



Le type NumbersLoadOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/__init__/#) | Constructeur.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [load_format](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/load_format) | Obtient le format de chargement.|
| [password](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/password) | Obtient et définit le mot de passe du classeur.|
| [parsing_formula_on_open](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/parsing_formula_on_open) | Indique si l'analyse de la formule est effectuée lors de la lecture du fichier.|
| [parsing_pivot_cached_records](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/parsing_pivot_cached_records) | Indique si l'analyse des enregistrements mis en cache pivot est effectuée lors du chargement du fichier.<br/> La valeur par défaut est false.|
| [language_code](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/language_code) | Obtient ou définit la langue de l'interface utilisateur de la version du classeur en fonction du CountryCode qui a enregistré le fichier.|
| [region](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/region) | Obtient ou définit les paramètres régionaux utilisés pour le classeur qui sera chargé.|
| [default_style_settings](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/default_style_settings) | Obtient les paramètres de style par défaut pour l'initialisation des styles du classeur|
| [standard_font](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/standard_font) | Définit le nom de police standard par défaut|
| [standard_font_size](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/standard_font_size) | Définit la taille de police standard par défaut.|
| [ignore_not_printed](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/ignore_not_printed) | Ignorer les données qui ne sont pas imprimées si vous imprimez directement le fichier|
| [check_data_valid](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/check_data_valid) | Vérifiez si les données sont valides dans le fichier modèle.|
| [check_excel_restriction](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/check_excel_restriction) | Vérifiez si la restriction du fichier Excel est vérifiée lorsque l'utilisateur modifie les objets liés aux cellules.<br/>Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.<br/>Lorsque vous saisissez une valeur supérieure à 32 Ko, comme par exemple Cell.PutValue(string), si cette propriété est vraie, vous obtiendrez une exception.<br/>Si cette propriété est fausse, nous accepterons la valeur de votre chaîne d'entrée comme valeur de la cellule afin que plus tard<br/>vous pouvez générer la valeur de chaîne complète pour d'autres formats de fichiers tels que CSV.<br/>Cependant, si vous avez défini un type de valeur qui n'est pas valide pour le format de fichier Excel,<br/>Vous ne devez pas enregistrer le classeur au format Excel ultérieurement. Sinon, une erreur inattendue pourrait se produire dans le fichier Excel généré.|
| [keep_unparsed_data](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/keep_unparsed_data) | Conserver les données non analysées en mémoire lors du chargement du classeur à partir du fichier modèle. La valeur par défaut est « true ».|
| [load_filter](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/load_filter) | Le filtre pour indiquer comment charger les données.|
| [memory_setting](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/memory_setting) | Obtient ou définit le mode mémoire pour le classeur chargé.|
| [auto_fitter_options](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/auto_fitter_options) | Obtient et définit les options d'ajustement automatique|
| [auto_filter](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/auto_filter) | Indique si le filtrage automatique des données est effectué lors du chargement des fichiers.|
| [font_configs](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/font_configs) | Obtient et définit les configurations de polices individuelles.<br/> Fonctionne uniquement pour le [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) qui utilise ce [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions) pour charger.|
| [ignore_useless_shapes](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/ignore_useless_shapes) | Indique si les formes inutiles sont ignorées.|
| [preserve_padding_spaces_in_formula](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/preserve_padding_spaces_in_formula) | Indique si les espaces et les sauts de ligne qui sont remplis entre les jetons de formule doivent être conservés<br/>tout en obtenant et en définissant des formules.<br/> La valeur par défaut est faux.|
| [load_table_type](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/load_table_type) | Obtient et définit le type de chargement de plusieurs tables dans une feuille de calcul.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions/set_paper_size/#aspose.cells.papersizetype) | Définit la taille du papier d'impression par défaut à partir des paramètres par défaut de l'imprimante.|



###  Voir également
* module [`aspose.cells.numbers`](..)
* classe [`LoadOptions`](/cells/python-net/fr/aspose.cells/loadoptions)
* classe [`NumbersLoadOptions`](/cells/python-net/fr/aspose.cells.numbers/numbersloadoptions)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
