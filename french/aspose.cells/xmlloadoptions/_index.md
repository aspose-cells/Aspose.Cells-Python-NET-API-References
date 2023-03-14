---
title: XmlLoadOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1690
url: /fr/aspose.cells/xmlloadoptions/
is_root: false
---
##  XmlLoadOptions classe
Représente les options de chargement de xml.



**Héritage:** [XmlLoadOptions](/cells/python-net/aspose.cells/xmlloadoptions) → 
[LoadOptions](/cells/python-net/fr/aspose.cells/loadoptions)



Le type XmlLoadOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [XmlLoadOptions()](/cells/python-net/fr/aspose.cells/xmlloadoptions/__init__/#) | Représente les options de chargement du fichier xml.|
| [XmlLoadOptions(type)](/cells/python-net/fr/aspose.cells/xmlloadoptions/__init__/#LoadFormat) | Représente les options de chargement du fichier xml.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [load_format](/cells/python-net/fr/aspose.cells/xmlloadoptions/load_format) | Obtient le format de chargement.|
| [password](/cells/python-net/fr/aspose.cells/xmlloadoptions/password) | Obtient et définit le mot de passe du classeur.|
| [parsing_formula_on_open](/cells/python-net/fr/aspose.cells/xmlloadoptions/parsing_formula_on_open) | Indique si l'analyse de la formule lors de la lecture du fichier.|
| [parsing_pivot_cached_records](/cells/python-net/fr/aspose.cells/xmlloadoptions/parsing_pivot_cached_records) | Indique si l'analyse du pivot a mis en cache les enregistrements lors du chargement du fichier.<br/> La valeur par défaut est faux.|
| [language_code](/cells/python-net/fr/aspose.cells/xmlloadoptions/language_code) | Obtient ou définit la langue de l'interface utilisateur de la version de Workbook basée sur CountryCode qui a enregistré le fichier.|
| [region](/cells/python-net/fr/aspose.cells/xmlloadoptions/region) | Obtient ou définit les paramètres régionaux du système en fonction de CountryCode au moment du chargement du fichier.|
| [default_style_settings](/cells/python-net/fr/aspose.cells/xmlloadoptions/default_style_settings) | Obtient les paramètres de style par défaut pour initialiser les styles du classeur|
| [standard_font](/cells/python-net/fr/aspose.cells/xmlloadoptions/standard_font) | Définit le nom de police standard par défaut|
| [standard_font_size](/cells/python-net/fr/aspose.cells/xmlloadoptions/standard_font_size) | Définit la taille de police standard par défaut.|
| [interrupt_monitor](/cells/python-net/fr/aspose.cells/xmlloadoptions/interrupt_monitor) | Obtient et définit le moniteur d'interruption.|
| [ignore_not_printed](/cells/python-net/fr/aspose.cells/xmlloadoptions/ignore_not_printed) | Ignorer les données qui ne sont pas imprimées en cas d'impression directe du fichier|
| [check_data_valid](/cells/python-net/fr/aspose.cells/xmlloadoptions/check_data_valid) |Vérifiez si les données sont valides dans le fichier modèle.|
| [check_excel_restriction](/cells/python-net/fr/aspose.cells/xmlloadoptions/check_excel_restriction) | Si vérifier la restriction du fichier Excel lorsque l'utilisateur modifie les objets liés aux cellules.<br/>Par exemple, Excel n'autorise pas la saisie d'une valeur de chaîne supérieure à 32 Ko.<br/>Lorsque vous saisissez une valeur supérieure à 32 Ko, par exemple Cell.PutValue(string), si cette propriété est vraie, vous obtiendrez une exception.<br/>Si cette propriété est fausse, nous accepterons votre valeur de chaîne d'entrée comme valeur de la cellule afin que plus tard<br/>vous pouvez générer la valeur de chaîne complète pour d'autres formats de fichier tels que CSV.<br/>Cependant, si vous avez défini un type de valeur non valide pour le format de fichier Excel,<br/> vous ne devez pas enregistrer le classeur au format de fichier Excel ultérieurement. Sinon, il peut y avoir une erreur inattendue pour le fichier Excel généré.|
| [keep_unparsed_data](/cells/python-net/fr/aspose.cells/xmlloadoptions/keep_unparsed_data) | Indique si les données non analysées sont conservées en mémoire pour le classeur lorsqu'il est chargé à partir du fichier de modèle. La valeur par défaut est true.|
| [load_filter](/cells/python-net/fr/aspose.cells/xmlloadoptions/load_filter) | Le filtre pour indiquer comment charger les données.|
| [light_cells_data_handler](/cells/python-net/fr/aspose.cells/xmlloadoptions/light_cells_data_handler) | Le gestionnaire de données pour le traitement des données des cellules lors de la lecture du fichier de modèle.|
| [memory_setting](/cells/python-net/fr/aspose.cells/xmlloadoptions/memory_setting) | Obtient ou définit les options d'utilisation de la mémoire.|
| [warning_callback](/cells/python-net/fr/aspose.cells/xmlloadoptions/warning_callback) | Obtient ou définit un rappel d'avertissement.|
| [auto_fitter_options](/cells/python-net/fr/aspose.cells/xmlloadoptions/auto_fitter_options) | Obtient et définit les options d'ajustement automatique|
| [auto_filter](/cells/python-net/fr/aspose.cells/xmlloadoptions/auto_filter) | Indique si le filtrage automatique des données lors du chargement des fichiers.|
| [font_configs](/cells/python-net/fr/aspose.cells/xmlloadoptions/font_configs) | Obtient et définit des configurations de police individuelles.<br/> Ne fonctionne que pour le [Workbook](/cells/python-net/fr/aspose.cells/workbook) qui utilise ce [LoadOptions](/cells/python-net/fr/aspose.cells/loadoptions) pour charger.|
| [start_cell](/cells/python-net/fr/aspose.cells/xmlloadoptions/start_cell) | Obtient et définit la cellule de départ.|
| [is_xml_map](/cells/python-net/fr/aspose.cells/xmlloadoptions/is_xml_map) |Indique si le mappage xml vers Excel.<br/> La valeur par défaut est faux.|
| [contains_multiple_worksheets](/cells/python-net/fr/aspose.cells/xmlloadoptions/contains_multiple_worksheets) | Indique si vous importez du xml en tant que plusieurs feuilles de calcul.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/fr/aspose.cells/xmlloadoptions/set_paper_size/#PaperSizeType) | Définit le format de papier d'impression par défaut à partir des paramètres par défaut de l'imprimante.|



###  Voir également
* module [aspose.cells](..)
* classe [LoadOptions](/cells/python-net/fr/aspose.cells/loadoptions)
* classe [Workbook](/cells/python-net/fr/aspose.cells/workbook)
* classe [XmlLoadOptions](/cells/python-net/fr/aspose.cells/xmlloadoptions)
