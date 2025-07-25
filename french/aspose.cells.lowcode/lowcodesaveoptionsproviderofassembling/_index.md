---
title: LowCodeSaveOptionsProviderOfAssembling classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/
is_root: false
---
##  LowCodeSaveOptionsProviderOfAssembling classe
Mise en œuvre pour fournir des options de sauvegarde qui enregistrent les parties divisées dans des fichiers
et le chemin du fichier résultant est nommé comme (il peut contenir des répertoires) :
[`LowCodeSaveOptionsProviderOfAssembling.path_header`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_header)+[`LowCodeSaveOptionsProviderOfAssembling.sheet_prefix`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#sheet_prefix)+SheetIndex(ou SheetName)
+[`LowCodeSaveOptionsProviderOfAssembling.split_part_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#split_part_prefix)+SplitPartIndex+[`LowCodeSaveOptionsProviderOfAssembling.path_tail`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_tail).



**Héritage:** [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)



Le type LowCodeSaveOptionsProviderOfAssembling expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/__init__/#) | Construit une nouvelle instance de LowCodeSaveOptionsProviderOfAssembling|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [path_header](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_header) | Partie d'en-tête (avant le contenu ajouté de la feuille et la partie divisée) du chemin du fichier.|
| [path_tail](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_tail) | Partie de queue (après les numéros de séquence) du chemin du fichier.<br/> Il doit inclure l'extension du nom de fichier.|
| [use_sheet_name](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/use_sheet_name) | Le chemin d'accès au fichier est généré avec le nom de la feuille plutôt qu'avec son index. La valeur par défaut est « false ».|
| [sheet_prefix](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_prefix) |Préfixe pour l'index de la feuille de calcul.|
| [split_part_prefix](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_prefix) | Préfixe pour l'index de la partie divisée.|
| [sheet_index_offset](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_index_offset) | Décalage de l'index de la feuille par rapport à celui utilisé dans le chemin du fichier<br/> et sa valeur réelle ([`SplitPartInfo.sheet_index`](/cells/python-net/fr/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_index_offset) | Décalage de l'index de la partie divisée par rapport à ce qui est utilisé dans le chemin du fichier<br/> et sa valeur réelle ([`SplitPartInfo.part_index`](/cells/python-net/fr/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_sheet_always) | Ajoutez toujours un index de feuille ou un nom au chemin du fichier.<br/>La valeur par défaut est false, c'est-à-dire lorsqu'il n'y a qu'une seule feuille,<br/> l'index de la feuille (ou le nom) et le préfixe correspondant ne seront pas ajoutés au chemin du fichier.|
| [build_path_with_split_part_always](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_split_part_always) | Ajoutez-vous toujours un index de partie fractionnée au chemin du fichier ?<br/>La valeur par défaut est false, c'est-à-dire lorsqu'il n'y a qu'une seule partie divisée,<br/> l'index de la partie divisée et le préfixe correspondant ne seront pas ajoutés au chemin du fichier.|
| [save_options_template](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/save_options_template) | Le modèle pour créer une instance d'options de sauvegarde dans [`LowCodeSaveOptionsProviderOfAssembling.get_save_options`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options).|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Obtient les options d'enregistrement à partir desquelles obtenir les paramètres de sortie pour la partie actuellement divisée.|
| [`finish(self, part)`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  Voir également
* module [`aspose.cells.lowcode`](..)
* classe [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/fr/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)
