---
title: Config classe
second_title: Aspose.Cells.GridJs for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cellsgridjs/config/
is_root: false
---
##  Config classe

Représente tous les paramètres de GridJs



Le type Config expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cellsgridjs/config/__init__/#) | Construit une nouvelle instance de Config|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [save_html_as_zip](/cells/python-net/fr/aspose.cellsgridjs/config/save_html_as_zip) | Définit/Obtient s'il faut enregistrer le fichier HTML en tant qu'archive zip, la valeur par défaut est false.|
| [same_image_detecting](/cells/python-net/fr/aspose.cellsgridjs/config/same_image_detecting) | Définit/Obtient s'il faut vérifier si l'image a la même source, la valeur par défaut est vraie<br/> la valeur par défaut est vraie.|
| [auto_optimize_for_large_cells](/cells/python-net/fr/aspose.cellsgridjs/config/auto_optimize_for_large_cells) | Définit/Obtient s'il faut optimiser automatiquement les performances de chargement pour une feuille de calcul comportant de grandes cellules<br/> ignorer certains styles/bordures pour réduire le temps de chargement<br/> la valeur par défaut est vraie.|
| [islimit_shape_or_image](/cells/python-net/fr/aspose.cellsgridjs/config/islimit_shape_or_image) |Définit/Obtient s'il faut limiter le nombre total de formes d'affichage/d'images dans une feuille de calcul, si défini sur true,<br/> GridJs limitera la forme d'affichage totale/taille de l'image dans une feuille de calcul à MaxShapeOrImageCount<br/> la valeur par défaut est vraie.|
| [max_shape_or_image_count](/cells/python-net/fr/aspose.cellsgridjs/config/max_shape_or_image_count) | Définit/obtient le nombre total de formes d'affichage/d'images à l'intérieur de la feuille active, cela prendra effet lorsque IslimitShapes=true.<br/> la valeur par défaut est 100.|
| [max_total_shape_or_image_count](/cells/python-net/fr/aspose.cellsgridjs/config/max_total_shape_or_image_count) | Définit/obtient le nombre total de formes d'affichage/d'images dans l'ensemble du classeur, cela prendra effet lorsque IslimitShapes=true.<br/> la valeur par défaut est 300.|
| [max_shape_or_image_width_or_height](/cells/python-net/fr/aspose.cellsgridjs/config/max_shape_or_image_width_or_height) | Définit/obtient la largeur ou la hauteur maximale d'une forme/image, GridJs ignorera la forme/image dont la largeur ou la hauteur est supérieure à cela, cela prendra effet lorsque IslimitShapes=true.<br/> la valeur par défaut est 10 000.|
| [max_pdf_save_seconds](/cells/python-net/fr/aspose.cellsgridjs/config/max_pdf_save_seconds) | Définit/obtient le nombre maximum de secondes d'expiration lors de l'enregistrement au format PDF.<br/> la valeur par défaut est 10.|
| [ignore_empty_content](/cells/python-net/fr/aspose.cellsgridjs/config/ignore_empty_content) | Définit/Obtient s'il faut afficher la plage maximale qui comprend les données, le style, les cellules fusionnées et les formes.<br/> si la dernière ligne ou colonne contient des cellules sans valeur ni formule mais avec un style personnalisé<br/>alors nous n'afficherons pas cette ligne/colonne lorsque cette valeur est vraie.<br/> la valeur par défaut est true .|
| [use_print_area](/cells/python-net/fr/aspose.cellsgridjs/config/use_print_area) |Définit/Obtient s'il faut utiliser PageSetup.PrintArea pour la plage d'affichage de l'interface utilisateur lorsque la feuille de calcul a un paramètre PageSetup pour PrintArea.<br/> la valeur par défaut est false .|
| [load_time_out](/cells/python-net/fr/aspose.cellsgridjs/config/load_time_out) | Définit/obtient une interruption de délai d'attente en millisecondes lors du chargement du fichier, lorsque la période de coût du chargement du fichier est plus longue que les attentes, cela déclenche une exception.<br/> la valeur par défaut est -1, ce qui signifie qu'aucune interruption de délai d'attente n'est définie.|
| [show_chart_sheet](/cells/python-net/fr/aspose.cellsgridjs/config/show_chart_sheet) | Définit/Obtient s’il faut afficher la feuille de calcul graphique.<br/> la valeur par défaut est false .|
| [page_size](/cells/python-net/fr/aspose.cellsgridjs/config/page_size) | Définit/Obtient s'il faut effectuer la pagination<br/> GridJs limitera la taille des lignes en fonction de PageSize, si PageSize est -1, il ne fera pas de pagination<br/> la valeur par défaut est -1|
| [empty_sheet_max_row](/cells/python-net/fr/aspose.cellsgridjs/config/empty_sheet_max_row) | Définit/obtient la ligne maximale par défaut pour une feuille de calcul vide.<br/> la valeur par défaut est 12.|
| [empty_sheet_max_col](/cells/python-net/fr/aspose.cellsgridjs/config/empty_sheet_max_col) | Définit/obtient la colonne maximale par défaut pour une feuille de calcul vide.<br/> la valeur par défaut est 15.|
| [picture_cache_directory](/cells/python-net/fr/aspose.cellsgridjs/config/picture_cache_directory) | Définit/obtient le répertoire de cache pour les images. (cela prendra effet lorsque GridJsWorkbook.CacheImp est nul)<br/> le chemin par défaut sera "_piccache" dans FileCacheDirectory.|
| [file_cache_directory](/cells/python-net/fr/aspose.cellsgridjs/config/file_cache_directory) |Définit/obtient le répertoire de cache pour le fichier de feuille de calcul.<br/> Nous devons le définir sur un chemin spécifique avant d'utiliser GridJs.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [set_license](/cells/python-net/fr/aspose.cellsgridjs/config/set_license/#str) |  |
| [set_license](/cells/python-net/fr/aspose.cellsgridjs/config/set_license/#io.RawIOBase) | Licence pour le composant.|
| [set_font_folder](/cells/python-net/fr/aspose.cellsgridjs/config/set_font_folder/#str-bool) | Définit le dossier des polices|
| [set_font_folders](/cells/python-net/fr/aspose.cellsgridjs/config/set_font_folders/#list-bool) | Définit les dossiers de polices|



###  Voir également
* module [`aspose.cellsgridjs`](..)
