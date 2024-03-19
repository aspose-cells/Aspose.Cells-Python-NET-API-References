---
title: TxtSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1590
url: /fr/aspose.cells/txtsaveoptions/
is_root: false
---
##  TxtSaveOptions classe
Représente les options d'enregistrement pour le format de texte csv/délimité par des tabulations/autre.



**Héritage:** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)



Le type TxtSaveOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/txtsaveoptions/__init__/#) | Crée des options d'enregistrement de fichier texte.|
| [__init__](/cells/python-net/fr/aspose.cells/txtsaveoptions/__init__/#aspose.cells.SaveFormat) | Crée des options d'enregistrement de fichier texte.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [save_format](/cells/python-net/fr/aspose.cells/txtsaveoptions/save_format) | Obtient le format du fichier de sauvegarde.|
| [clear_data](/cells/python-net/fr/aspose.cells/txtsaveoptions/clear_data) | Rendez le classeur vide après avoir enregistré le fichier.|
| [cached_file_folder](/cells/python-net/fr/aspose.cells/txtsaveoptions/cached_file_folder) | Le dossier de fichiers mis en cache est utilisé pour stocker des données volumineuses.|
| [validate_merged_areas](/cells/python-net/fr/aspose.cells/txtsaveoptions/validate_merged_areas) | Indique si vous validez les cellules fusionnées avant d'enregistrer le fichier.|
| [merge_areas](/cells/python-net/fr/aspose.cells/txtsaveoptions/merge_areas) | Indique si fusionner les zones de mise en forme conditionnelle et de validation avant d'enregistrer le fichier.|
| [create_directory](/cells/python-net/fr/aspose.cells/txtsaveoptions/create_directory) | Si vrai et que le répertoire n'existe pas, le répertoire sera automatiquement créé avant d'enregistrer le fichier.|
| [sort_names](/cells/python-net/fr/aspose.cells/txtsaveoptions/sort_names) | Indique si le tri des noms définis avant d'enregistrer le fichier.|
| [sort_external_names](/cells/python-net/fr/aspose.cells/txtsaveoptions/sort_external_names) | Indique si le tri des noms définis externes avant d'enregistrer le fichier.|
| [refresh_chart_cache](/cells/python-net/fr/aspose.cells/txtsaveoptions/refresh_chart_cache) | Indique si l'actualisation des données du cache de graphique|
| [warning_callback](/cells/python-net/fr/aspose.cells/txtsaveoptions/warning_callback) | Obtient ou définit un rappel d’avertissement.|
| [update_smart_art](/cells/python-net/fr/aspose.cells/txtsaveoptions/update_smart_art) | Indique si la mise à jour des paramètres d'art intelligent est effectuée.<br/> La valeur par défaut est fausse.|
| [separator](/cells/python-net/fr/aspose.cells/txtsaveoptions/separator) | Obtient et définit le délimiteur de caractères du fichier texte.|
| [separator_string](/cells/python-net/fr/aspose.cells/txtsaveoptions/separator_string) | Obtient et définit une valeur de chaîne comme séparateur.|
| [encoding](/cells/python-net/fr/aspose.cells/txtsaveoptions/encoding) | Obtient et définit l'encodage par défaut.|
| [always_quoted](/cells/python-net/fr/aspose.cells/txtsaveoptions/always_quoted) | Indique s'il faut toujours ajouter '"' pour chaque champ.<br/>Si c'est vrai, toutes les valeurs seront citées ;<br/>Si faux, les valeurs ne seront citées qu'en cas de besoin (par exemple,<br/>lorsque les valeurs contiennent des caractères spéciaux tels que '"' , '\n' ou un caractère séparateur).<br/> La valeur par défaut est fausse.|
| [quote_type](/cells/python-net/fr/aspose.cells/txtsaveoptions/quote_type) | Obtient ou définit comment citer les valeurs dans le fichier texte exporté.|
| [format_strategy](/cells/python-net/fr/aspose.cells/txtsaveoptions/format_strategy) | Obtient et définit la stratégie de format lors de l'exportation de la valeur de cellule sous forme de chaîne.|
| [light_cells_data_provider](/cells/python-net/fr/aspose.cells/txtsaveoptions/light_cells_data_provider) | Le fournisseur de données pour enregistrer le classeur en mode léger.|
| [trim_leading_blank_row_and_column](/cells/python-net/fr/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Indique si les premières lignes et colonnes vides doivent être tronquées comme le fait MS Excel.<br/> La valeur par défaut est vraie.|
| [trim_tailing_blank_cells](/cells/python-net/fr/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Indique si les cellules vides de fin d’une ligne doivent être tronquées. La valeur par défaut est fausse.|
| [keep_separators_for_blank_row](/cells/python-net/fr/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) |Indique si les séparateurs doivent être affichés pour la ligne vide.<br/> La valeur par défaut est false, donc par défaut le contenu de la ligne vide sera vide.|
| [export_area](/cells/python-net/fr/aspose.cells/txtsaveoptions/export_area) | La plage de cellules à exporter.|
| [export_quote_prefix](/cells/python-net/fr/aspose.cells/txtsaveoptions/export_quote_prefix) | Indique si le signe guillemet simple doit être exporté dans le cadre de la valeur d'une cellule<br/> quand [`Style.quote_prefix`](/cells/python-net/fr/aspose.cells/style#quote_prefix) est vrai pour cela. La valeur par défaut est fausse.|
| [export_all_sheets](/cells/python-net/fr/aspose.cells/txtsaveoptions/export_all_sheets) | Indique si l'exportation de toutes les feuilles vers le fichier texte est effectuée.<br/> Si c'est faux, exportez uniquement la feuille active, tout comme MS Excel.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)
* classe [`TxtSaveOptions`](/cells/python-net/fr/aspose.cells/txtsaveoptions)
