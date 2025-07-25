---
title: TxtSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1500
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
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/txtsaveoptions/__init__/#) | Crée des options d'enregistrement de fichier texte.|
| [`__init__(self, save_format)`](/cells/python-net/fr/aspose.cells/txtsaveoptions/__init__/#aspose.cells.saveformat) | Crée des options d'enregistrement de fichier texte.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [save_format](/cells/python-net/fr/aspose.cells/txtsaveoptions/save_format) | Obtient le format du fichier de sauvegarde.|
| [clear_data](/cells/python-net/fr/aspose.cells/txtsaveoptions/clear_data) | Videz le classeur après avoir enregistré le fichier.|
| [cached_file_folder](/cells/python-net/fr/aspose.cells/txtsaveoptions/cached_file_folder) | Le dossier pour les fichiers temporaires qui peuvent être utilisés comme cache de données.|
| [validate_merged_areas](/cells/python-net/fr/aspose.cells/txtsaveoptions/validate_merged_areas) | Indique si les cellules fusionnées doivent être validées avant d'enregistrer le fichier.|
| [merge_areas](/cells/python-net/fr/aspose.cells/txtsaveoptions/merge_areas) | Indique si les zones de mise en forme conditionnelle et de validation doivent être fusionnées avant d'enregistrer le fichier.|
| [create_directory](/cells/python-net/fr/aspose.cells/txtsaveoptions/create_directory) | Si vrai et que le répertoire n'existe pas, le répertoire sera automatiquement créé avant d'enregistrer le fichier.|
| [sort_names](/cells/python-net/fr/aspose.cells/txtsaveoptions/sort_names) |Indique si les noms définis doivent être triés avant l'enregistrement du fichier.|
| [sort_external_names](/cells/python-net/fr/aspose.cells/txtsaveoptions/sort_external_names) | Indique si les noms externes définis doivent être triés avant l'enregistrement du fichier.|
| [refresh_chart_cache](/cells/python-net/fr/aspose.cells/txtsaveoptions/refresh_chart_cache) | Indique si l'actualisation des données du cache du graphique|
| [check_excel_restriction](/cells/python-net/fr/aspose.cells/txtsaveoptions/check_excel_restriction) | Vérifiez si la restriction du fichier Excel est vérifiée lorsque l'utilisateur modifie les objets liés aux cellules.<br/>Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.<br/> Lorsque vous saisissez une valeur supérieure à 32 Ko, elle sera tronquée.|
| [update_smart_art](/cells/python-net/fr/aspose.cells/txtsaveoptions/update_smart_art) | Indique si la mise à jour du paramètre Smart Art est en cours.<br/> La valeur par défaut est false.|
| [encrypt_document_properties](/cells/python-net/fr/aspose.cells/txtsaveoptions/encrypt_document_properties) | Indique si les propriétés du document doivent être cryptées lors de l'enregistrement en tant que fichier .xls.<br/> La valeur par défaut est vrai.|
| [separator](/cells/python-net/fr/aspose.cells/txtsaveoptions/separator) | Obtient et définit le délimiteur de caractères du fichier texte.|
| [separator_string](/cells/python-net/fr/aspose.cells/txtsaveoptions/separator_string) | Obtient et définit une valeur de chaîne comme séparateur.|
| [encoding](/cells/python-net/fr/aspose.cells/txtsaveoptions/encoding) | Obtient et définit l'encodage par défaut.|
| [always_quoted](/cells/python-net/fr/aspose.cells/txtsaveoptions/always_quoted) | Indique s'il faut toujours ajouter '"' pour chaque champ.<br/>Si vrai, toutes les valeurs seront citées ;<br/>Si la valeur est fausse, les valeurs ne seront citées que lorsque cela est nécessaire (par exemple,<br/>lorsque les valeurs contiennent des caractères spéciaux tels que '"', '\n' ou un caractère séparateur).<br/> La valeur par défaut est faux.|
| [quote_type](/cells/python-net/fr/aspose.cells/txtsaveoptions/quote_type) |Obtient ou définit comment citer les valeurs dans le fichier texte exporté.|
| [format_strategy](/cells/python-net/fr/aspose.cells/txtsaveoptions/format_strategy) | Obtient et définit la stratégie de format lors de l'exportation de la valeur de la cellule sous forme de chaîne.|
| [trim_leading_blank_row_and_column](/cells/python-net/fr/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) | Indique si les lignes et les colonnes vides de début doivent être coupées comme le fait MS Excel.<br/> La valeur par défaut est vrai.|
| [trim_tailing_blank_cells](/cells/python-net/fr/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) | Indique si les cellules vides en fin de ligne doivent être supprimées. La valeur par défaut est « false ».|
| [keep_separators_for_blank_row](/cells/python-net/fr/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) | Indique si les séparateurs doivent être affichés pour la ligne vide.<br/> La valeur par défaut est false, donc par défaut le contenu de la ligne vide sera vide.|
| [export_area](/cells/python-net/fr/aspose.cells/txtsaveoptions/export_area) | La plage de cellules à exporter.|
| [export_quote_prefix](/cells/python-net/fr/aspose.cells/txtsaveoptions/export_quote_prefix) | Indique si le guillemet simple doit être exporté dans le cadre de la valeur d'une cellule<br/> lorsque [`Style.quote_prefix`](/cells/python-net/fr/aspose.cells/style#quote_prefix) est vrai. La valeur par défaut est false.|
| [export_all_sheets](/cells/python-net/fr/aspose.cells/txtsaveoptions/export_all_sheets) | Indique si toutes les feuilles doivent être exportées vers le fichier texte.<br/> Si c'est faux, exportez uniquement la feuille active, tout comme MS Excel.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)
* classe [`TxtSaveOptions`](/cells/python-net/fr/aspose.cells/txtsaveoptions)
