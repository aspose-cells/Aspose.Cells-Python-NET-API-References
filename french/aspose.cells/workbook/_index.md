---
title: Workbook classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1570
url: /fr/aspose.cells/workbook/
is_root: false
---
##  Workbook classe
Représente un objet racine pour créer une feuille de calcul Excel.



Le type Workbook expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/workbook/__init__/#) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook).|
| [`__init__(self, file_format_type)`](/cells/python-net/fr/aspose.cells/workbook/__init__/#aspose.cells.fileformattype) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook).|
| [`__init__(self, file)`](/cells/python-net/fr/aspose.cells/workbook/__init__/#str) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre un fichier.|
| [`__init__(self, stream)`](/cells/python-net/fr/aspose.cells/workbook/__init__/#io.rawiobase) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre un flux.|
| [`__init__(self, file, load_options)`](/cells/python-net/fr/aspose.cells/workbook/__init__/#str-aspose.cells.loadoptions) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre un fichier.|
| [`__init__(self, stream, load_options)`](/cells/python-net/fr/aspose.cells/workbook/__init__/#io.rawiobase-aspose.cells.loadoptions) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre le flux.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [settings](/cells/python-net/fr/aspose.cells/workbook/settings) | Représente les paramètres du classeur.|
| [worksheets](/cells/python-net/fr/aspose.cells/workbook/worksheets) | Obtient la collection [`WorksheetCollection`](/cells/python-net/fr/aspose.cells/worksheetcollection) dans la feuille de calcul.|
| [is_licensed](/cells/python-net/fr/aspose.cells/workbook/is_licensed) | Indique si la licence est définie.|
| [colors](/cells/python-net/fr/aspose.cells/workbook/colors) | Renvoie les couleurs de la palette de la feuille de calcul.|
| [count_of_styles_in_pool](/cells/python-net/fr/aspose.cells/workbook/count_of_styles_in_pool) | Obtient le nombre de styles dans le pool de styles.|
| [default_style](/cells/python-net/fr/aspose.cells/workbook/default_style) | Obtient ou définit l'objet [`Style`](/cells/python-net/fr/aspose.cells/style) par défaut du classeur.|
| [is_digitally_signed](/cells/python-net/fr/aspose.cells/workbook/is_digitally_signed) | Indique si cette feuille de calcul est signée numériquement.|
| [is_workbook_protected_with_password](/cells/python-net/fr/aspose.cells/workbook/is_workbook_protected_with_password) | Indique si la structure ou la fenêtre est protégée par un mot de passe.|
| [vba_project](/cells/python-net/fr/aspose.cells/workbook/vba_project) |Obtient le [`Workbook.vba_project`](/cells/python-net/fr/aspose.cells/workbook#vba_project) dans une feuille de calcul.|
| [has_macro](/cells/python-net/fr/aspose.cells/workbook/has_macro) | Indique si cette feuille de calcul contient des macros/VBA.|
| [has_revisions](/cells/python-net/fr/aspose.cells/workbook/has_revisions) | Obtient si le classeur a des modifications suivies|
| [file_name](/cells/python-net/fr/aspose.cells/workbook/file_name) | Obtient et définit le nom du fichier actuel.|
| [cells_data_table_factory](/cells/python-net/fr/aspose.cells/workbook/cells_data_table_factory) | Obtient l'usine pour construire ICellsDataTable à partir d'objets personnalisés|
| [data_sorter](/cells/python-net/fr/aspose.cells/workbook/data_sorter) | Obtient un objet DataSorter pour trier les données.|
| [theme](/cells/python-net/fr/aspose.cells/workbook/theme) | Obtient le nom du thème.|
| [built_in_document_properties](/cells/python-net/fr/aspose.cells/workbook/built_in_document_properties) | Renvoie une collection [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document intégrées de la feuille de calcul.|
| [custom_document_properties](/cells/python-net/fr/aspose.cells/workbook/custom_document_properties) | Renvoie une collection [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document personnalisées de la feuille de calcul.|
| [file_format](/cells/python-net/fr/aspose.cells/workbook/file_format) | Obtient et définit le format du fichier.|
| [has_custom_function](/cells/python-net/fr/aspose.cells/workbook/has_custom_function) | Détecte si une fonction personnalisée est utilisée dans ce classeur,<br/> comme dans la formule d'une cellule, dans les noms définis...|
| [content_type_properties](/cells/python-net/fr/aspose.cells/workbook/content_type_properties) | Obtient la liste des [`ContentTypeProperty`](/cells/python-net/fr/aspose.cells.properties/contenttypeproperty) objets dans le classeur.|
| [custom_xml_parts](/cells/python-net/fr/aspose.cells/workbook/custom_xml_parts) | Représente une partie de stockage de données XML personnalisée (données XML personnalisées dans un package).|
| [data_mashup](/cells/python-net/fr/aspose.cells/workbook/data_mashup) | Obtient les données de mashup.|
| [ribbon_xml](/cells/python-net/fr/aspose.cells/workbook/ribbon_xml) | Obtient et définit le fichier XML qui définit l'interface utilisateur du ruban.|
| [absolute_path](/cells/python-net/fr/aspose.cells/workbook/absolute_path) | Obtient et définit le chemin absolu du fichier.|
| [data_connections](/cells/python-net/fr/aspose.cells/workbook/data_connections) |Obtient la collection ExternalConnection.|
| [data_model](/cells/python-net/fr/aspose.cells/workbook/data_model) | Obtient le modèle de données dans le classeur.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`save(self, file_name, save_format)`](/cells/python-net/fr/aspose.cells/workbook/save/#str-aspose.cells.saveformat) | Enregistre le classeur sur le disque.|
| [`save(self, file_name)`](/cells/python-net/fr/aspose.cells/workbook/save/#str) | Enregistrez le classeur sur le disque.|
| [`save(self, file_name, save_options)`](/cells/python-net/fr/aspose.cells/workbook/save/#str-aspose.cells.saveoptions) | Enregistre le classeur sur le disque.|
| [`save(self, stream, save_format)`](/cells/python-net/fr/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveformat) | Enregistre le classeur dans le flux.|
| [`save(self, stream, save_options)`](/cells/python-net/fr/aspose.cells/workbook/save/#io.rawiobase-aspose.cells.saveoptions) | Enregistre le classeur dans le flux.|
| [`create_style(self)`](/cells/python-net/fr/aspose.cells/workbook/create_style/#) | Crée un nouveau style.|
| [`create_style(self, clone_default_style)`](/cells/python-net/fr/aspose.cells/workbook/create_style/#bool) | Crée un nouveau style.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/fr/aspose.cells/workbook/replace/#str-str) | Remplace la valeur d'une cellule par une nouvelle chaîne.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/fr/aspose.cells/workbook/replace/#str-int) | Remplace la valeur d'une cellule par un nouvel entier.|
| [`replace(self, place_holder, new_value)`](/cells/python-net/fr/aspose.cells/workbook/replace/#str-float) | Remplace la valeur d'une cellule par un nouveau double.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/fr/aspose.cells/workbook/replace/#str-list-bool) | Remplace la valeur d'une cellule par un nouveau tableau de chaînes.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/fr/aspose.cells/workbook/replace/#str-list-bool) | Remplace les valeurs des cellules par un tableau d'entiers.|
| [`replace(self, place_holder, new_values, is_vertical)`](/cells/python-net/fr/aspose.cells/workbook/replace/#str-list-bool) | Remplace les valeurs des cellules par un tableau double.|
| [`replace(self, bool_value, new_value)`](/cells/python-net/fr/aspose.cells/workbook/replace/#bool-any) | Remplace les valeurs des cellules par de nouvelles données.|
| [`replace(self, int_value, new_value)`](/cells/python-net/fr/aspose.cells/workbook/replace/#int-any) | Remplace les valeurs des cellules par de nouvelles données.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/fr/aspose.cells/workbook/replace/#str-str-aspose.cells.replaceoptions) | Remplace la valeur d'une cellule par une nouvelle chaîne.|
| [`copy(self, source, copy_options)`](/cells/python-net/fr/aspose.cells/workbook/copy/#aspose.cells.workbook-aspose.cells.copyoptions) | Copie un autre objet Workbook.|
| [`copy(self, source)`](/cells/python-net/fr/aspose.cells/workbook/copy/#aspose.cells.workbook) | Copie les données d'un objet Workbook source.|
| [`calculate_formula(self)`](/cells/python-net/fr/aspose.cells/workbook/calculate_formula/#) | Calcule le résultat des formules.|
| [`calculate_formula(self, ignore_error)`](/cells/python-net/fr/aspose.cells/workbook/calculate_formula/#bool) | Calcule le résultat des formules.|
| [`calculate_formula(self, options)`](/cells/python-net/fr/aspose.cells/workbook/calculate_formula/#aspose.cells.calculationoptions) | Calcul des formules dans ce classeur.|
| [`refresh_dynamic_array_formulas(self, calculate)`](/cells/python-net/fr/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Actualise les formules de tableau dynamiques (déversement dans une nouvelle plage de cellules voisines en fonction des données actuelles)<br/> Les autres formules du classeur ne seront pas calculées de manière récursive même si elles ont été utilisées par des formules de tableau dynamique.|
| [`refresh_dynamic_array_formulas(self, calculate, copts)`](/cells/python-net/fr/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.calculationoptions) |Actualise les formules de tableau dynamiques (déversement dans une nouvelle plage de cellules voisines en fonction des données actuelles)|
| [`import_xml(self, url, sheet_name, row, col)`](/cells/python-net/fr/aspose.cells/workbook/import_xml/#str-str-int-int) | Importe/met à jour un fichier de données XML dans le classeur.|
| [`import_xml(self, stream, sheet_name, row, col)`](/cells/python-net/fr/aspose.cells/workbook/import_xml/#io.rawiobase-str-int-int) | Importe/met à jour un fichier de données XML dans le classeur.|
| [`export_xml(self, map_name, path)`](/cells/python-net/fr/aspose.cells/workbook/export_xml/#str-str) | Exporter les données XML liées par la carte XML spécifiée.|
| [`export_xml(self, map_name, stream)`](/cells/python-net/fr/aspose.cells/workbook/export_xml/#str-io.rawiobase) | Exporter des données XML.|
| [`parse_formulas(self, ignore_error)`](/cells/python-net/fr/aspose.cells/workbook/parse_formulas/#bool) | Analyse toutes les formules qui n'ont pas été analysées lorsqu'elles ont été chargées à partir d'un fichier modèle ou définies dans une cellule.|
| [`start_access_cache(self, opts)`](/cells/python-net/fr/aspose.cells/workbook/start_access_cache/#aspose.cells.accesscacheoptions) | Démarre la session qui utilise les caches pour accéder aux données.|
| [`close_access_cache(self, opts)`](/cells/python-net/fr/aspose.cells/workbook/close_access_cache/#aspose.cells.accesscacheoptions) | Ferme la session qui utilise les caches pour accéder aux données.|
| [`remove_unused_styles(self)`](/cells/python-net/fr/aspose.cells/workbook/remove_unused_styles/#) | Supprimez tous les styles inutilisés.|
| [`create_builtin_style(self, type)`](/cells/python-net/fr/aspose.cells/workbook/create_builtin_style/#aspose.cells.builtinstyletype) | Crée un style intégré selon le type donné.|
| [`create_cells_color(self)`](/cells/python-net/fr/aspose.cells/workbook/create_cells_color/#) | Crée un objet [`CellsColor`](/cells/python-net/fr/aspose.cells/cellscolor).|
| [`combine(self, second_workbook)`](/cells/python-net/fr/aspose.cells/workbook/combine/#aspose.cells.workbook) | Combine un autre objet Workbook.|
| [`get_style_in_pool(self, index)`](/cells/python-net/fr/aspose.cells/workbook/get_style_in_pool/#int) | Obtient le style dans le pool de styles.<br/>Tous les styles du classeur seront rassemblés dans un pool.<br/> Il n'y a qu'un simple index de référence dans les cellules.|
| [`get_fonts(self)`](/cells/python-net/fr/aspose.cells/workbook/get_fonts/#) | Obtient toutes les polices du pool de styles.|
| [`get_named_style(self, name)`](/cells/python-net/fr/aspose.cells/workbook/get_named_style/#str) | Obtient le style nommé dans le pool de styles.|
| [`merge_named_styles(self, source)`](/cells/python-net/fr/aspose.cells/workbook/merge_named_styles/#aspose.cells.workbook) | Fusionne les styles nommés de l’autre fichier Excel.|
| [`change_palette(self, color, index)`](/cells/python-net/fr/aspose.cells/workbook/change_palette/#aspose.pydrawing.color-int) | Modifie la palette de la feuille de calcul dans l'index spécifié.|
| [`is_color_in_palette(self, color)`](/cells/python-net/fr/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.color) | Vérifie si une couleur est dans la palette de la feuille de calcul.|
| [`get_matching_color(self, raw_color)`](/cells/python-net/fr/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.color) |Trouvez la couleur la plus correspondante dans la palette actuelle.|
| [`set_encryption_options(self, encryption_type, key_length)`](/cells/python-net/fr/aspose.cells/workbook/set_encryption_options/#aspose.cells.encryptiontype-int) | Définir les options de cryptage.|
| [`protect(self, protection_type, password)`](/cells/python-net/fr/aspose.cells/workbook/protect/#aspose.cells.protectiontype-str) | Protège un classeur.|
| [`protect_shared_workbook(self, password)`](/cells/python-net/fr/aspose.cells/workbook/protect_shared_workbook/#str) | Protège un classeur partagé.|
| [`unprotect(self, password)`](/cells/python-net/fr/aspose.cells/workbook/unprotect/#str) | Déprotège un classeur.|
| [`unprotect_shared_workbook(self, password)`](/cells/python-net/fr/aspose.cells/workbook/unprotect_shared_workbook/#str) | Déprotège un classeur partagé.|
| [`remove_macro(self)`](/cells/python-net/fr/aspose.cells/workbook/remove_macro/#) | Supprime VBA/macro de cette feuille de calcul.|
| [`remove_digital_signature(self)`](/cells/python-net/fr/aspose.cells/workbook/remove_digital_signature/#) | Supprime la signature numérique de cette feuille de calcul.|
| [`accept_all_revisions(self)`](/cells/python-net/fr/aspose.cells/workbook/accept_all_revisions/#) | Accepte toutes les modifications suivies dans le classeur.|
| [`remove_external_links(self)`](/cells/python-net/fr/aspose.cells/workbook/remove_external_links/#) | Supprime tous les liens externes dans le classeur.|
| [`get_theme_color(self, type)`](/cells/python-net/fr/aspose.cells/workbook/get_theme_color/#aspose.cells.themecolortype) | Obtient la couleur du thème.|
| [`set_theme_color(self, type, color)`](/cells/python-net/fr/aspose.cells/workbook/set_theme_color/#aspose.cells.themecolortype-aspose.pydrawing.color) | Définit la couleur du thème|
| [`custom_theme(self, theme_name, colors)`](/cells/python-net/fr/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.color[]) | Les coutumes sont le thème.|
| [`copy_theme(self, source)`](/cells/python-net/fr/aspose.cells/workbook/copy_theme/#aspose.cells.workbook) | Copie le thème d'un autre classeur.|
| [`has_exernal_links(self)`](/cells/python-net/fr/aspose.cells/workbook/has_exernal_links/#) | Indique si ce classeur contient des liens externes vers d'autres sources de données.|
| [`update_custom_function_definition(self, definition)`](/cells/python-net/fr/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.customfunctiondefinition) | Met à jour la définition des fonctions personnalisées.|
| [`update_linked_data_source(self, external_workbooks)`](/cells/python-net/fr/aspose.cells/workbook/update_linked_data_source/#list) | Si ce classeur contient des liens externes vers d'autres sources de données,<br/> Aspose.Cells tentera de récupérer les dernières données à partir des sources données.|
| [`set_digital_signature(self, digital_signature_collection)`](/cells/python-net/fr/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Définit la signature numérique sur un fichier de feuille de calcul (Excel 2007 et versions ultérieures).|
| [`add_digital_signature(self, digital_signature_collection)`](/cells/python-net/fr/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.digitalsignaturecollection) | Ajoute une signature numérique à un fichier de feuille de calcul OOXML (Excel 2007 et versions ultérieures).|
| [`get_digital_signature(self)`](/cells/python-net/fr/aspose.cells/workbook/get_digital_signature/#) |Obtient la signature numérique du fichier.|
| [`remove_personal_information(self)`](/cells/python-net/fr/aspose.cells/workbook/remove_personal_information/#) | Supprime les informations personnelles.|
| [`close(self)`](/cells/python-net/fr/aspose.cells/workbook/close/#) | Dispose() est ignoré par le wrapper depuis le protocole Python|



###  Remarques

La classe Workbook désigne une feuille de calcul Excel. Chaque feuille de calcul peut contenir plusieurs feuilles de calcul.
La fonction de base de la classe est d'ouvrir et d'enregistrer des fichiers Excel natifs.
Le cours possède des fonctionnalités avancées telles que la copie de données à partir d'autres classeurs, la combinaison de deux classeurs, la conversion d'Excel en PDF, le rendu d'Excel en image et la protection de la feuille de calcul Excel.

###  Exemple

L'exemple suivant charge un Workbook à partir d'un fichier Excel nommé designer.xls et rend les barres de défilement horizontales et verticales invisibles.
 Il remplace ensuite deux valeurs de chaîne par une valeur entière et une valeur de chaîne respectivement dans la feuille de calcul et enregistre enfin le classeur sous forme de fichier Excel xlsx.

```python
from aspose.cells import Workbook

# Open a designer file
designerFile = "designer.xls"
workbook = Workbook(designerFile)
# Set scroll bars
workbook.settings.is_h_scroll_bar_visible = False
workbook.settings.is_v_scroll_bar_visible = False
# Replace the placeholder string with new values
newInt = 100
workbook.replace("OldInt", newInt)
newString = "Hello!"
workbook.replace("OldString", newString)
workbook.save("result.xlsx")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`CellsColor`](/cells/python-net/fr/aspose.cells/cellscolor)
* classe [`ContentTypeProperty`](/cells/python-net/fr/aspose.cells.properties/contenttypeproperty)
* classe [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty)
* classe [`Style`](/cells/python-net/fr/aspose.cells/style)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
* classe [`WorksheetCollection`](/cells/python-net/fr/aspose.cells/worksheetcollection)
