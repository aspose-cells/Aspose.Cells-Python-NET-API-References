---
title: Workbook classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1660
url: /fr/aspose.cells/workbook/
is_root: false
---
##  Workbook classe
Représente un objet racine pour créer une feuille de calcul Excel.



Le type Workbook expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/workbook/__init__/#) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook).|
| [__init__](/cells/python-net/fr/aspose.cells/workbook/__init__/#aspose.cells.FileFormatType) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook).|
| [__init__](/cells/python-net/fr/aspose.cells/workbook/__init__/#str) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre un fichier.|
| [__init__](/cells/python-net/fr/aspose.cells/workbook/__init__/#io.RawIOBase) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre un flux.|
| [__init__](/cells/python-net/fr/aspose.cells/workbook/__init__/#str-aspose.cells.LoadOptions) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et ouvre un fichier.|
| [__init__](/cells/python-net/fr/aspose.cells/workbook/__init__/#io.RawIOBase-aspose.cells.LoadOptions) | Initialise une nouvelle instance de la classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook) et un flux ouvert.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [settings](/cells/python-net/fr/aspose.cells/workbook/settings) | Représente les paramètres du classeur.|
| [worksheets](/cells/python-net/fr/aspose.cells/workbook/worksheets) | Obtient la collection [`WorksheetCollection`](/cells/python-net/fr/aspose.cells/worksheetcollection) dans la feuille de calcul.|
| [is_licensed](/cells/python-net/fr/aspose.cells/workbook/is_licensed) | Indique si la licence est définie.|
| [colors](/cells/python-net/fr/aspose.cells/workbook/colors) | Renvoie les couleurs dans la palette de la feuille de calcul.|
| [count_of_styles_in_pool](/cells/python-net/fr/aspose.cells/workbook/count_of_styles_in_pool) | Obtient le nombre de styles dans le pool de styles.|
| [default_style](/cells/python-net/fr/aspose.cells/workbook/default_style) |Obtient ou définit l'objet [`Style`](/cells/python-net/fr/aspose.cells/style) par défaut du classeur.|
| [is_digitally_signed](/cells/python-net/fr/aspose.cells/workbook/is_digitally_signed) | Indique si cette feuille de calcul est signée numériquement.|
| [is_workbook_protected_with_password](/cells/python-net/fr/aspose.cells/workbook/is_workbook_protected_with_password) | Indique si la structure ou la fenêtre est protégée par mot de passe.|
| [vba_project](/cells/python-net/fr/aspose.cells/workbook/vba_project) | Obtient le [`Workbook.vba_project`](/cells/python-net/fr/aspose.cells/workbook#vba_project) dans une feuille de calcul.|
| [has_macro](/cells/python-net/fr/aspose.cells/workbook/has_macro) | Indique si cette feuille de calcul contient une macro/VBA.|
| [has_revisions](/cells/python-net/fr/aspose.cells/workbook/has_revisions) | Obtient si le classeur a des modifications suivies|
| [file_name](/cells/python-net/fr/aspose.cells/workbook/file_name) | Obtient et définit le nom du fichier actuel.|
| [cells_data_table_factory](/cells/python-net/fr/aspose.cells/workbook/cells_data_table_factory) | Obtient la fabrique pour créer ICellsDataTable à partir d'objets personnalisés|
| [data_sorter](/cells/python-net/fr/aspose.cells/workbook/data_sorter) | Obtient un objet DataSorter pour trier les données.|
| [theme](/cells/python-net/fr/aspose.cells/workbook/theme) | Obtient le nom du thème.|
| [built_in_document_properties](/cells/python-net/fr/aspose.cells/workbook/built_in_document_properties) | Renvoie une collection [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document intégrées de la feuille de calcul.|
| [custom_document_properties](/cells/python-net/fr/aspose.cells/workbook/custom_document_properties) | Renvoie une collection [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document personnalisées de la feuille de calcul.|
| [file_format](/cells/python-net/fr/aspose.cells/workbook/file_format) | Obtient et définit le format de fichier.|
| [interrupt_monitor](/cells/python-net/fr/aspose.cells/workbook/interrupt_monitor) | Obtient et définit le moniteur d'interruption.|
| [content_type_properties](/cells/python-net/fr/aspose.cells/workbook/content_type_properties) | Obtient la liste des objets [`ContentTypeProperty`](/cells/python-net/fr/aspose.cells.properties/contenttypeproperty) dans le classeur.|
| [custom_xml_parts](/cells/python-net/fr/aspose.cells/workbook/custom_xml_parts) | Représente une partie de stockage de données XML personnalisée (données XML personnalisées dans un package).|
| [data_mashup](/cells/python-net/fr/aspose.cells/workbook/data_mashup) | Obtient des données d'application composite.|
| [ribbon_xml](/cells/python-net/fr/aspose.cells/workbook/ribbon_xml) |Obtient et définit le fichier XML qui définit l'interface utilisateur du ruban.|
| [absolute_path](/cells/python-net/fr/aspose.cells/workbook/absolute_path) | Obtient et définit le chemin absolu du fichier.|
| [data_connections](/cells/python-net/fr/aspose.cells/workbook/data_connections) | Obtient la collection [`ExternalConnection`](/cells/python-net/fr/aspose.cells.externalconnections/externalconnection).|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [save](/cells/python-net/fr/aspose.cells/workbook/save/#str-aspose.cells.SaveFormat) | Enregistre le classeur sur le disque.|
| [save](/cells/python-net/fr/aspose.cells/workbook/save/#str) | Enregistrez le classeur sur le disque.|
| [save](/cells/python-net/fr/aspose.cells/workbook/save/#str-aspose.cells.SaveOptions) | Enregistre le classeur sur le disque.|
| [save](/cells/python-net/fr/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveFormat) | Enregistre le classeur dans le flux.|
| [save](/cells/python-net/fr/aspose.cells/workbook/save/#io.RawIOBase-aspose.cells.SaveOptions) | Enregistre le classeur dans le flux.|
| [replace](/cells/python-net/fr/aspose.cells/workbook/replace/#str-str) | Remplace la valeur d'une cellule par une nouvelle chaîne.|
| [replace](/cells/python-net/fr/aspose.cells/workbook/replace/#str-int) | Remplace la valeur d'une cellule par un nouvel entier.|
| [replace](/cells/python-net/fr/aspose.cells/workbook/replace/#str-float) | Remplace la valeur d'une cellule par un nouveau double.|
| [replace](/cells/python-net/fr/aspose.cells/workbook/replace/#str-list-bool) | Remplace la valeur d'une cellule par un nouveau tableau de chaînes.|
| [replace](/cells/python-net/fr/aspose.cells/workbook/replace/#str-list-bool) | Remplace les valeurs des cellules par un tableau d'entiers.|
| [replace](/cells/python-net/fr/aspose.cells/workbook/replace/#str-list-bool) | Remplace les valeurs des cellules par un double tableau.|
| [replace](/cells/python-net/fr/aspose.cells/workbook/replace/#bool-any) | Remplace les valeurs des cellules par de nouvelles données.|
| [replace](/cells/python-net/fr/aspose.cells/workbook/replace/#int-any) | Remplace les valeurs des cellules par de nouvelles données.|
| [replace](/cells/python-net/fr/aspose.cells/workbook/replace/#str-str-aspose.cells.ReplaceOptions) | Remplace la valeur d'une cellule par une nouvelle chaîne.|
| [copy](/cells/python-net/fr/aspose.cells/workbook/copy/#aspose.cells.Workbook-aspose.cells.CopyOptions) | Copie un autre objet Workbook.|
| [copy](/cells/python-net/fr/aspose.cells/workbook/copy/#aspose.cells.Workbook) | Copie les données d'un objet Workbook source.|
| [calculate_formula](/cells/python-net/fr/aspose.cells/workbook/calculate_formula/#) | Calcule le résultat des formules.|
| [calculate_formula](/cells/python-net/fr/aspose.cells/workbook/calculate_formula/#bool) | Calcule le résultat des formules.|
| [calculate_formula](/cells/python-net/fr/aspose.cells/workbook/calculate_formula/#aspose.cells.CalculationOptions) | Calculer des formules dans ce classeur.|
| [refresh_dynamic_array_formulas](/cells/python-net/fr/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool) | Actualise les formules de tableau dynamique (déversement dans une nouvelle plage de cellules voisines en fonction des données actuelles)<br/>Les autres formules du classeur ne seront pas calculées de manière récursive même si elles ont été utilisées par des formules matricielles dynamiques.|
| [refresh_dynamic_array_formulas](/cells/python-net/fr/aspose.cells/workbook/refresh_dynamic_array_formulas/#bool-aspose.cells.CalculationOptions) | Actualise les formules de tableau dynamique (déversement dans une nouvelle plage de cellules voisines en fonction des données actuelles)|
| [import_xml](/cells/python-net/fr/aspose.cells/workbook/import_xml/#str-str-int-int) | Importe/met à jour un fichier de données XML dans le classeur.|
| [import_xml](/cells/python-net/fr/aspose.cells/workbook/import_xml/#io.RawIOBase-str-int-int) | Importe/met à jour un fichier de données XML dans le classeur.|
| [export_xml](/cells/python-net/fr/aspose.cells/workbook/export_xml/#str-str) | Exportez les données XML liées par la carte XML spécifiée.|
| [export_xml](/cells/python-net/fr/aspose.cells/workbook/export_xml/#str-io.RawIOBase) | Exportez des données XML.|
| [parse_formulas](/cells/python-net/fr/aspose.cells/workbook/parse_formulas/#bool) | Analyse toutes les formules qui n'ont pas été analysées lorsqu'elles ont été chargées à partir d'un fichier modèle ou définies dans une cellule.|
| [start_access_cache](/cells/python-net/fr/aspose.cells/workbook/start_access_cache/#aspose.cells.AccessCacheOptions) | Démarre la session qui utilise les caches pour accéder aux données.|
| [close_access_cache](/cells/python-net/fr/aspose.cells/workbook/close_access_cache/#aspose.cells.AccessCacheOptions) | Ferme la session qui utilise les caches pour accéder aux données.|
| [remove_unused_styles](/cells/python-net/fr/aspose.cells/workbook/remove_unused_styles/#) | Supprimez tous les styles inutilisés.|
| [create_style](/cells/python-net/fr/aspose.cells/workbook/create_style/#) | Crée un nouveau style.|
| [create_builtin_style](/cells/python-net/fr/aspose.cells/workbook/create_builtin_style/#aspose.cells.BuiltinStyleType) | Crée un style intégré par type donné.|
| [create_cells_color](/cells/python-net/fr/aspose.cells/workbook/create_cells_color/#) | Crée un objet [`CellsColor`](/cells/python-net/fr/aspose.cells/cellscolor).|
| [combine](/cells/python-net/fr/aspose.cells/workbook/combine/#aspose.cells.Workbook) | Combine un autre objet Workbook.|
| [get_style_in_pool](/cells/python-net/fr/aspose.cells/workbook/get_style_in_pool/#int) | Obtient le style dans le pool de styles.<br/>Tous les styles du classeur seront regroupés dans un pool.<br/> Il n’y a qu’un simple index de référence dans les cellules.|
| [get_fonts](/cells/python-net/fr/aspose.cells/workbook/get_fonts/#) | Obtient toutes les polices du pool de styles.|
| [get_named_style](/cells/python-net/fr/aspose.cells/workbook/get_named_style/#str) | Obtient le style nommé dans le pool de styles.|
| [change_palette](/cells/python-net/fr/aspose.cells/workbook/change_palette/#aspose.pydrawing.Color-int) |Modifie la palette de la feuille de calcul dans l'index spécifié.|
| [is_color_in_palette](/cells/python-net/fr/aspose.cells/workbook/is_color_in_palette/#aspose.pydrawing.Color) | Vérifie si une couleur est dans la palette de la feuille de calcul.|
| [get_matching_color](/cells/python-net/fr/aspose.cells/workbook/get_matching_color/#aspose.pydrawing.Color) | Trouvez la couleur la mieux assortie dans la palette actuelle.|
| [set_encryption_options](/cells/python-net/fr/aspose.cells/workbook/set_encryption_options/#aspose.cells.EncryptionType-int) | Définissez les options de cryptage.|
| [protect](/cells/python-net/fr/aspose.cells/workbook/protect/#aspose.cells.ProtectionType-str) | Protège un classeur.|
| [protect_shared_workbook](/cells/python-net/fr/aspose.cells/workbook/protect_shared_workbook/#str) | Protège un classeur partagé.|
| [unprotect](/cells/python-net/fr/aspose.cells/workbook/unprotect/#str) | Déprotège un classeur.|
| [unprotect_shared_workbook](/cells/python-net/fr/aspose.cells/workbook/unprotect_shared_workbook/#str) | Déprotège un classeur partagé.|
| [remove_macro](/cells/python-net/fr/aspose.cells/workbook/remove_macro/#) | Supprime VBA/macro de cette feuille de calcul.|
| [remove_digital_signature](/cells/python-net/fr/aspose.cells/workbook/remove_digital_signature/#) | Supprime la signature numérique de cette feuille de calcul.|
| [accept_all_revisions](/cells/python-net/fr/aspose.cells/workbook/accept_all_revisions/#) | Accepte toutes les modifications suivies dans le classeur.|
| [remove_external_links](/cells/python-net/fr/aspose.cells/workbook/remove_external_links/#) | Supprime tous les liens externes du classeur.|
| [get_theme_color](/cells/python-net/fr/aspose.cells/workbook/get_theme_color/#aspose.cells.ThemeColorType) | Obtient la couleur du thème.|
| [set_theme_color](/cells/python-net/fr/aspose.cells/workbook/set_theme_color/#aspose.cells.ThemeColorType-aspose.pydrawing.Color) | Définit la couleur du thème|
| [custom_theme](/cells/python-net/fr/aspose.cells/workbook/custom_theme/#str-aspose.pydrawing.Color[]) | Personnalisez le thème.|
| [copy_theme](/cells/python-net/fr/aspose.cells/workbook/copy_theme/#aspose.cells.Workbook) | Copie le thème d'un autre classeur.|
| [has_exernal_links](/cells/python-net/fr/aspose.cells/workbook/has_exernal_links/#) | Indique si ce classeur contient des liens externes vers d'autres sources de données.|
| [update_custom_function_definition](/cells/python-net/fr/aspose.cells/workbook/update_custom_function_definition/#aspose.cells.CustomFunctionDefinition) | Met à jour la définition des fonctions personnalisées.|
| [update_linked_data_source](/cells/python-net/fr/aspose.cells/workbook/update_linked_data_source/#list) | Si ce classeur contient des liens externes vers une autre source de données,<br/> Aspose.Cells tentera de récupérer les dernières données à partir de sources données.|
| [set_digital_signature](/cells/python-net/fr/aspose.cells/workbook/set_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) |Définit la signature numérique sur un fichier de feuille de calcul (Excel2007 et versions ultérieures).|
| [add_digital_signature](/cells/python-net/fr/aspose.cells/workbook/add_digital_signature/#aspose.cells.digitalsignatures.DigitalSignatureCollection) | Ajoute une signature numérique à un fichier de feuille de calcul OOXML (Excel2007 et versions ultérieures).|
| [get_digital_signature](/cells/python-net/fr/aspose.cells/workbook/get_digital_signature/#) | Obtient la signature numérique du fichier.|
| [remove_personal_information](/cells/python-net/fr/aspose.cells/workbook/remove_personal_information/#) | Supprime les informations personnelles.|



###  Remarques

La classe Workbook désigne une feuille de calcul Excel. Chaque feuille de calcul peut contenir plusieurs feuilles de calcul.
La fonctionnalité de base du cours est d'ouvrir et de sauvegarder des fichiers Excel natifs.
La classe possède des fonctionnalités avancées telles que la copie de données à partir d'autres classeurs, la combinaison de deux classeurs, la conversion d'Excel en PDF, le rendu d'Excel en image et la protection de la feuille de calcul Excel.

###  Exemple

L'exemple suivant charge un Workbook à partir d'un fichier Excel nommé designer.xls et rend les barres de défilement horizontale et verticale invisibles.
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
* classe [`ExternalConnection`](/cells/python-net/fr/aspose.cells.externalconnections/externalconnection)
* classe [`Style`](/cells/python-net/fr/aspose.cells/style)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
* classe [`WorksheetCollection`](/cells/python-net/fr/aspose.cells/worksheetcollection)
