---
title: OoxmlSaveOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1050
url: /fr/aspose.cells/ooxmlsaveoptions/
is_root: false
---
##  OoxmlSaveOptions classe
Représente les options d'enregistrement du fichier XML ouvert du bureau.



**Héritage:** [`OoxmlSaveOptions`](/cells/python-net/aspose.cells/ooxmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)



Le type OoxmlSaveOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/__init__/#) | Crée les options pour enregistrer le fichier XML ouvert du bureau.|
| [`__init__(self, save_format)`](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/__init__/#aspose.cells.saveformat) | Crée les options pour enregistrer le fichier XML ouvert du bureau.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [save_format](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/save_format) | Obtient le format du fichier de sauvegarde.|
| [clear_data](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/clear_data) | Videz le classeur après avoir enregistré le fichier.|
| [cached_file_folder](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/cached_file_folder) | Le dossier pour les fichiers temporaires qui peuvent être utilisés comme cache de données.|
| [validate_merged_areas](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/validate_merged_areas) | Indique si les cellules fusionnées doivent être validées avant d'enregistrer le fichier.|
| [merge_areas](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/merge_areas) | Indique si les zones de mise en forme conditionnelle et de validation doivent être fusionnées avant d'enregistrer le fichier.|
| [create_directory](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/create_directory) | Si vrai et que le répertoire n'existe pas, le répertoire sera automatiquement créé avant d'enregistrer le fichier.|
| [sort_names](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/sort_names) |Indique si les noms définis doivent être triés avant l'enregistrement du fichier.|
| [sort_external_names](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/sort_external_names) | Indique si les noms externes définis doivent être triés avant l'enregistrement du fichier.|
| [refresh_chart_cache](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/refresh_chart_cache) | Indique si l'actualisation des données du cache du graphique|
| [check_excel_restriction](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/check_excel_restriction) | Vérifiez si la restriction du fichier Excel est vérifiée lorsque l'utilisateur modifie les objets liés aux cellules.<br/>Par exemple, Excel ne permet pas de saisir une valeur de chaîne supérieure à 32 Ko.<br/> Lorsque vous saisissez une valeur supérieure à 32 Ko, elle sera tronquée.|
| [update_smart_art](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/update_smart_art) | Indique si la mise à jour du paramètre Smart Art est en cours.<br/> La valeur par défaut est false.|
| [encrypt_document_properties](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/encrypt_document_properties) | Indique si les propriétés du document doivent être cryptées lors de l'enregistrement en tant que fichier .xls.<br/> La valeur par défaut est vrai.|
| [export_cell_name](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/export_cell_name) | Indique si le nom de la cellule doit être exporté vers le fichier Excel2007 .xlsx (.xlsm, .xltx, .xltm).<br/>Si le fichier de sortie est accessible par SQL Server DTS, cette valeur doit être vraie.<br/>Définir la valeur sur false augmentera considérablement les performances et réduira la taille du fichier lors de la création d'un fichier volumineux.<br/> La valeur par défaut est vrai.|
| [update_zoom](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/update_zoom) | Indique si le facteur d'échelle doit être mis à jour avant d'enregistrer le fichier<br/> si les propriétés PageSetup.FitToPagesWide et PageSetup.FitToPagesTall contrôlent la façon dont la feuille de calcul est mise à l'échelle.|
| [enable_zip64](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/enable_zip64) | Utilisez toujours les extensions ZIP64 lors de l'écriture d'archives zip, même lorsque cela n'est pas nécessaire.|
| [embed_ooxml_as_ole_object](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/embed_ooxml_as_ole_object) | Indique si l'intégration des fichiers Ooxml d'OleObject en tant qu'objet ole.|
| [compression_type](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/compression_type) | Obtient et définit le type de compression pour le fichier ooxml.|
| [wps_compatibility](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions/wps_compatibility) | Indique s'il faut rendre le xls plus compatible avec WPS.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`OoxmlSaveOptions`](/cells/python-net/fr/aspose.cells/ooxmlsaveoptions)
* classe [`SaveOptions`](/cells/python-net/fr/aspose.cells/saveoptions)
