---
title: OleObject classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 380
url: /fr/aspose.cells.drawing/oleobject/
is_root: false
---
##  OleObject classe
Représente un OleObject dans une feuille de calcul.



**Héritage:** [`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject) → 
[`Shape`](/cells/python-net/fr/aspose.cells.drawing/shape)



Le type OleObject expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [macro_name](/cells/python-net/fr/aspose.cells.drawing/oleobject/macro_name) | Obtient et définit le nom de la macro.|
| [is_equation](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_equation) | Indique si la forme contient uniquement une équation.|
| [is_smart_art](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_smart_art) | Indique si la forme est un art intelligent.|
| [z_order_position](/cells/python-net/fr/aspose.cells.drawing/oleobject/z_order_position) | Renvoie la position d'une forme dans l'ordre z.|
| [name](/cells/python-net/fr/aspose.cells.drawing/oleobject/name) | Obtient et définit le nom de la forme.|
| [alternative_text](/cells/python-net/fr/aspose.cells.drawing/oleobject/alternative_text) | Renvoie ou définit la chaîne de texte descriptive (alternative) de l'objet [`Shape`](/cells/python-net/fr/aspose.cells.drawing/shape).|
| [title](/cells/python-net/fr/aspose.cells.drawing/oleobject/title) | Spécifie le titre (légende) de l'objet de forme actuel.|
| [line_format](/cells/python-net/fr/aspose.cells.drawing/oleobject/line_format) | Renvoie un objet MsoLineFormat qui contient les propriétés de mise en forme de ligne pour la forme spécifiée.|
| [fill_format](/cells/python-net/fr/aspose.cells.drawing/oleobject/fill_format) | Renvoie un objet MsoFillFormat qui contient les propriétés de mise en forme de remplissage pour la forme spécifiée.|
| [line](/cells/python-net/fr/aspose.cells.drawing/oleobject/line) | Obtient le style de ligne|
| [fill](/cells/python-net/fr/aspose.cells.drawing/oleobject/fill) | Renvoie un objet [`Shape.fill_format`](/cells/python-net/fr/aspose.cells.drawing/shape#fill_format) qui contient les propriétés de formatage de remplissage pour la forme spécifiée.|
| [shadow_effect](/cells/python-net/fr/aspose.cells.drawing/oleobject/shadow_effect) | Représente un objet [`ShadowEffect`](/cells/python-net/fr/aspose.cells.drawing/shadoweffect) qui spécifie l'effet d'ombre pour l'élément ou la forme du graphique.|
| [reflection](/cells/python-net/fr/aspose.cells.drawing/oleobject/reflection) |Représente un objet [`ReflectionEffect`](/cells/python-net/fr/aspose.cells.drawing/reflectioneffect) qui spécifie l'effet de réflexion pour l'élément ou la forme du graphique.|
| [glow](/cells/python-net/fr/aspose.cells.drawing/oleobject/glow) | Représente un objet [`GlowEffect`](/cells/python-net/fr/aspose.cells.drawing/gloweffect) qui spécifie l'effet de lueur pour l'élément ou la forme du graphique.|
| [soft_edges](/cells/python-net/fr/aspose.cells.drawing/oleobject/soft_edges) | Obtient et définit le rayon de flou à appliquer aux bords, en unités de points.|
| [three_d_format](/cells/python-net/fr/aspose.cells.drawing/oleobject/three_d_format) | Obtient et définit le format 3D de la forme.|
| [format_picture](/cells/python-net/fr/aspose.cells.drawing/oleobject/format_picture) | Obtient et définit les options du format d'image.|
| [is_hidden](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_hidden) | Indique si l'objet est visible.|
| [is_lock_aspect_ratio](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_lock_aspect_ratio) | Vrai signifie que le rapport hauteur/largeur de la forme est verrouillé.|
| [is_aspect_ratio_locked](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_aspect_ratio_locked) | Vrai signifie que le rapport hauteur/largeur de la forme est verrouillé.|
| [rotation_angle](/cells/python-net/fr/aspose.cells.drawing/oleobject/rotation_angle) | Obtient et définit la rotation de la forme.|
| [hyperlink](/cells/python-net/fr/aspose.cells.drawing/oleobject/hyperlink) | Obtient l'hyperlien de la forme.|
| [id](/cells/python-net/fr/aspose.cells.drawing/oleobject/id) | Obtient l'identifiant de cette forme.|
| [spid](/cells/python-net/fr/aspose.cells.drawing/oleobject/spid) | Spécifie un identifiant de chaîne facultatif qu'une application peut utiliser pour identifier la forme particulière.|
| [spt](/cells/python-net/fr/aspose.cells.drawing/oleobject/spt) | Spécifie un numéro facultatif qu'une application peut utiliser pour associer la forme particulière à un type de forme défini.|
| [worksheet](/cells/python-net/fr/aspose.cells.drawing/oleobject/worksheet) | Obtient l'objet [`Shape.worksheet`](/cells/python-net/fr/aspose.cells.drawing/shape#worksheet) qui contient cette forme.|
| [is_group](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_group) | Indique si cette forme est une forme de groupe.|
| [is_in_group](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_in_group) | Indique si la forme est groupée.|
| [is_word_art](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_word_art) |Indique si cette forme est un mot artistique.|
| [text_effect](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_effect) | Renvoie un objet TextEffectFormat qui contient des propriétés de mise en forme d'effet de texte pour la forme spécifiée.<br/> S'applique aux objets Shape qui représentent WordArt.|
| [is_locked](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_locked) | Vrai signifie que l'objet ne peut pas être modifié lorsque la feuille est protégée.<br/> Notez que cette valeur n'a de sens que si la feuille de calcul ou les objets de la feuille de calcul sont protégés.|
| [is_printable](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_printable) | Indique si l'objet est imprimable.<br/> Si Faux, cette forme ne sera pas imprimée lors de l'impression.|
| [mso_drawing_type](/cells/python-net/fr/aspose.cells.drawing/oleobject/mso_drawing_type) | Obtient le type de dessin.|
| [auto_shape_type](/cells/python-net/fr/aspose.cells.drawing/oleobject/auto_shape_type) | Obtient et définit le type de forme automatique.|
| [anchor_type](/cells/python-net/fr/aspose.cells.drawing/oleobject/anchor_type) | Obtient et définit le type de l'espace réservé d'ancrage de forme.|
| [placement](/cells/python-net/fr/aspose.cells.drawing/oleobject/placement) | Représente la manière dont l'objet de dessin est attaché aux cellules situées en dessous.<br/> La propriété contrôle le placement d'un objet sur une feuille de calcul.|
| [upper_left_row](/cells/python-net/fr/aspose.cells.drawing/oleobject/upper_left_row) | Représente l'index de la ligne supérieure.|
| [upper_delta_y](/cells/python-net/fr/aspose.cells.drawing/oleobject/upper_delta_y) | Obtient ou définit le décalage vertical de la forme par rapport à sa rangée du coin supérieur gauche.|
| [upper_left_column](/cells/python-net/fr/aspose.cells.drawing/oleobject/upper_left_column) | Représente l'index de la colonne du coin supérieur gauche.|
| [upper_delta_x](/cells/python-net/fr/aspose.cells.drawing/oleobject/upper_delta_x) |Obtient ou définit le décalage horizontal de la forme par rapport à sa colonne d'angle supérieur gauche.|
| [lower_right_row](/cells/python-net/fr/aspose.cells.drawing/oleobject/lower_right_row) | Représente l'index de la ligne du coin inférieur droit.|
| [lower_delta_y](/cells/python-net/fr/aspose.cells.drawing/oleobject/lower_delta_y) | Obtient ou définit le décalage vertical de la forme par rapport à sa rangée du coin inférieur droit.|
| [lower_right_column](/cells/python-net/fr/aspose.cells.drawing/oleobject/lower_right_column) | Représente l'index de la colonne du coin inférieur droit.|
| [lower_delta_x](/cells/python-net/fr/aspose.cells.drawing/oleobject/lower_delta_x) | Obtient ou définit le décalage horizontal de la forme par rapport à sa colonne d'angle inférieur droit.|
| [right](/cells/python-net/fr/aspose.cells.drawing/oleobject/right) | Représente la largeur du décalage horizontal de la forme à partir de sa colonne d'angle inférieur droit, en unités de pixels.|
| [bottom](/cells/python-net/fr/aspose.cells.drawing/oleobject/bottom) | Représente la largeur du décalage vertical de la forme par rapport à sa rangée de coin inférieur, en unités de pixels.|
| [width](/cells/python-net/fr/aspose.cells.drawing/oleobject/width) | Représente la largeur de la forme, en unité de pixels.|
| [width_inch](/cells/python-net/fr/aspose.cells.drawing/oleobject/width_inch) | Représente la largeur de la forme, en unité de pouce.|
| [width_pt](/cells/python-net/fr/aspose.cells.drawing/oleobject/width_pt) | Représente la largeur de la forme, en unité de point.|
| [width_cm](/cells/python-net/fr/aspose.cells.drawing/oleobject/width_cm) | Représente la largeur de la forme, en centimètres.|
| [height](/cells/python-net/fr/aspose.cells.drawing/oleobject/height) | Représente la hauteur de la forme, en unité de pixel.|
| [height_inch](/cells/python-net/fr/aspose.cells.drawing/oleobject/height_inch) | Représente la hauteur de la forme, en pouces.|
| [height_pt](/cells/python-net/fr/aspose.cells.drawing/oleobject/height_pt) |Représente la hauteur de la forme, en unité de points.|
| [height_cm](/cells/python-net/fr/aspose.cells.drawing/oleobject/height_cm) | Représente la hauteur de la forme, en unités de centimètres.|
| [left](/cells/python-net/fr/aspose.cells.drawing/oleobject/left) | Représente le décalage horizontal de la forme par rapport à sa colonne de gauche, en unités de pixels.|
| [left_inch](/cells/python-net/fr/aspose.cells.drawing/oleobject/left_inch) | Représente le décalage horizontal de la forme par rapport à sa colonne de gauche, en pouces.|
| [left_cm](/cells/python-net/fr/aspose.cells.drawing/oleobject/left_cm) | Représente le décalage horizontal de la forme par rapport à sa colonne de gauche, en centimètres.|
| [top](/cells/python-net/fr/aspose.cells.drawing/oleobject/top) | Représente le décalage vertical de la forme par rapport à sa rangée supérieure, en unités de pixels.|
| [top_inch](/cells/python-net/fr/aspose.cells.drawing/oleobject/top_inch) | Représente le décalage vertical de la forme par rapport à sa rangée supérieure, en pouces.|
| [top_cm](/cells/python-net/fr/aspose.cells.drawing/oleobject/top_cm) | Représente le décalage vertical de la forme par rapport à sa rangée supérieure, en centimètres.|
| [top_to_corner](/cells/python-net/fr/aspose.cells.drawing/oleobject/top_to_corner) | Obtient et définit le décalage vertical de la forme par rapport à la bordure supérieure de la feuille de calcul, en unités de pixels.|
| [left_to_corner](/cells/python-net/fr/aspose.cells.drawing/oleobject/left_to_corner) | Obtient et définit le décalage horizontal de la forme à partir de la bordure gauche de la feuille de calcul.|
| [x](/cells/python-net/fr/aspose.cells.drawing/oleobject/x) | Obtient et définit le décalage horizontal de la forme à partir de la bordure gauche de la feuille de calcul, en unités de pixels.|
| [y](/cells/python-net/fr/aspose.cells.drawing/oleobject/y) |Obtient et définit le décalage vertical de la forme à partir de la bordure supérieure de la feuille de calcul, en unités de pixels.|
| [width_scale](/cells/python-net/fr/aspose.cells.drawing/oleobject/width_scale) | Obtient et définit l'échelle de largeur, en pourcentage de la largeur de l'image d'origine.<br/> Si la forme n'est pas une image, la propriété WidthScale renvoie uniquement 100 ;|
| [height_scale](/cells/python-net/fr/aspose.cells.drawing/oleobject/height_scale) | Obtient et définit l'échelle de hauteur, en unité de pourcentage de la hauteur de l'image d'origine.<br/> Si la forme n'est pas une image, la propriété HeightScale renvoie uniquement 100 ;|
| [top_in_shape](/cells/python-net/fr/aspose.cells.drawing/oleobject/top_in_shape) | Représente le décalage vertical de la forme par rapport à la bordure supérieure de la forme parent,<br/> en unité de 1/4000 de la hauteur de la forme parente.|
| [left_in_shape](/cells/python-net/fr/aspose.cells.drawing/oleobject/left_in_shape) | Représente le décalage horizontal de la forme par rapport à la bordure gauche de la forme parent,<br/> en unité de 1/4000 de la largeur de la forme parente.|
| [width_in_shape](/cells/python-net/fr/aspose.cells.drawing/oleobject/width_in_shape) | Représente la largeur de la forme, en unité de 1/4000 de la forme parent.|
| [height_in_shape](/cells/python-net/fr/aspose.cells.drawing/oleobject/height_in_shape) | Représente le décalage vertical de la forme par rapport à la bordure supérieure de la forme parente, en unité de 1/4000 de la hauteur de la forme parente.|
| [group](/cells/python-net/fr/aspose.cells.drawing/oleobject/group) | Obtient la forme du groupe qui contient cette forme.|
| [type](/cells/python-net/fr/aspose.cells.drawing/oleobject/type) |Obtient le type de forme automatique.|
| [has_line](/cells/python-net/fr/aspose.cells.drawing/oleobject/has_line) | Obtient et définit la bordure de ligne de la forme visible.|
| [is_filled](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_filled) | Indique si le format de remplissage est visible.|
| [is_flipped_horizontally](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_flipped_horizontally) | Obtient et définit si la forme est inversée horizontalement.|
| [is_flipped_vertically](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_flipped_vertically) | Obtient et définit si la forme est inversée verticalement.|
| [actual_lower_right_row](/cells/python-net/fr/aspose.cells.drawing/oleobject/actual_lower_right_row) | Obtenez la rangée du bas réelle.|
| [relative_to_original_picture_size](/cells/python-net/fr/aspose.cells.drawing/oleobject/relative_to_original_picture_size) | Indique si la forme est relative à la taille de l'image d'origine.|
| [linked_cell](/cells/python-net/fr/aspose.cells.drawing/oleobject/linked_cell) | Obtient ou définit la plage de feuille de calcul liée à la valeur du contrôle.|
| [input_range](/cells/python-net/fr/aspose.cells.drawing/oleobject/input_range) | Obtient ou définit la plage de feuille de calcul utilisée pour remplir la zone de liste déroulante spécifiée.|
| [text_shape_type](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_shape_type) | Obtient et définit le type de forme de texte prédéfini.|
| [text_body](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_body) | Obtient et définit le paramètre du texte de la forme.|
| [font](/cells/python-net/fr/aspose.cells.drawing/oleobject/font) | Représente la police de la forme.|
| [text_options](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_options) | Représente les options de texte de la forme.|
| [text](/cells/python-net/fr/aspose.cells.drawing/oleobject/text) | Obtient et définit le texte de cette forme.|
| [is_rich_text](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_rich_text) | Que le texte soit ou non du texte enrichi.|
| [html_text](/cells/python-net/fr/aspose.cells.drawing/oleobject/html_text) | Obtient et définit la chaîne HTML qui contient des données et certains formats dans cette zone de texte.|
| [text_vertical_overflow](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_vertical_overflow) | Obtient et définit le type de débordement vertical du texte de la forme qui contient le texte.|
| [text_horizontal_overflow](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_horizontal_overflow) |Obtient et définit le type de débordement horizontal du texte de la forme qui contient le texte.|
| [is_text_wrapped](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_text_wrapped) | Obtient et définit le type de texte enveloppé de la forme qui contient du texte.|
| [text_orientation_type](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_orientation_type) | Obtient et définit le type d'orientation du texte de la forme.|
| [text_horizontal_alignment](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_horizontal_alignment) | Obtient et définit le type d'alignement horizontal du texte de la forme.|
| [text_vertical_alignment](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_vertical_alignment) | Obtient et définit le type d'alignement vertical du texte de la forme.|
| [text_direction](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_direction) | Obtient/définit la direction du flux de texte pour cet objet.|
| [text_box_options](/cells/python-net/fr/aspose.cells.drawing/oleobject/text_box_options) | Obtient les informations textuelles dans la forme|
| [control_data](/cells/python-net/fr/aspose.cells.drawing/oleobject/control_data) | Obtient les données de contrôle.|
| [active_x_control](/cells/python-net/fr/aspose.cells.drawing/oleobject/active_x_control) | Obtient le contrôle ActiveX.|
| [paths](/cells/python-net/fr/aspose.cells.drawing/oleobject/paths) | Obtient les chemins d'une forme géométrique personnalisée.|
| [create_id](/cells/python-net/fr/aspose.cells.drawing/oleobject/create_id) | Obtient et définit l'identifiant de création pour cette forme.|
| [is_decorative](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_decorative) | Indique si l'objet est décoratif.|
| [is_auto_size](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_auto_size) | True indique que la taille de l'objet OLE sera automatiquement modifiée en fonction de la taille de l'instantané du contenu intégré<br/> lorsque l'objet ole est activé.|
| [is_link](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_link) | Renvoie vrai si l'OleObject est lié au fichier.|
| [display_as_icon](/cells/python-net/fr/aspose.cells.drawing/oleobject/display_as_icon) | Vrai si l'objet spécifié est affiché sous forme d'icône<br/> et l'image ne sera pas modifiée automatiquement.|
| [image_data](/cells/python-net/fr/aspose.cells.drawing/oleobject/image_data) | Représente l'image de l'objet ole sous forme de tableau d'octets.|
| [object_data](/cells/python-net/fr/aspose.cells.drawing/oleobject/object_data) | Représente les données d'objet OLE intégrées sous forme de tableau d'octets.|
| [full_object_bin](/cells/python-net/fr/aspose.cells.drawing/oleobject/full_object_bin) | Obtient les données binaires complètes de l'objet OLE intégré dans le fichier modèle.|
| [image_source_full_name](/cells/python-net/fr/aspose.cells.drawing/oleobject/image_source_full_name) |Obtient ou définit le chemin et le nom du fichier source de l'image liée.|
| [prog_id](/cells/python-net/fr/aspose.cells.drawing/oleobject/prog_id) | Obtient ou définit le ProgID de l'objet OLE.|
| [file_format_type](/cells/python-net/fr/aspose.cells.drawing/oleobject/file_format_type) | Obtient et définit le type de fichier des données de l'objet OLE intégré|
| [object_source_full_name](/cells/python-net/fr/aspose.cells.drawing/oleobject/object_source_full_name) | Renvoie le nom complet de la source du fichier source pour l'objet OLE lié.|
| [label](/cells/python-net/fr/aspose.cells.drawing/oleobject/label) | Obtient et définit l'étiquette d'affichage de l'objet ole lié.|
| [source_full_name](/cells/python-net/fr/aspose.cells.drawing/oleobject/source_full_name) | Renvoie le nom complet de la source du fichier source pour l'objet OLE lié.|
| [auto_update](/cells/python-net/fr/aspose.cells.drawing/oleobject/auto_update) | Spécifie si le lien vers l'OleObject est automatiquement mis à jour ou non.|
| [auto_load](/cells/python-net/fr/aspose.cells.drawing/oleobject/auto_load) | Spécifie si l'application hôte pour l'objet incorporé doit être appelée pour charger<br/> les données de l'objet automatiquement lorsque le classeur parent est ouvert.|
| [class_identifier](/cells/python-net/fr/aspose.cells.drawing/oleobject/class_identifier) | Obtient et définit l'identifiant de classe de l'objet incorporé.<br/> Cela signifie quelle application ouvre le fichier intégré.|
| [image_type](/cells/python-net/fr/aspose.cells.drawing/oleobject/image_type) | Obtient le format d'image de l'objet ole.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`to_image(self, stream, image_type)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/to_image/#io.rawiobase-aspose.cells.drawing.imagetype) | Crée l'image de forme et l'enregistre dans un flux au format spécifié.|
| [`to_image(self, image_file, options)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/to_image/#str-aspose.cells.rendering.imageorprintoptions) | Enregistre la forme dans un fichier.|
| [`to_image(self, stream, options)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | Enregistre la forme dans un flux.|
| [`set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/set_embedded_object/#bool-bytes-str-bool-str) | Définit les données d'objet intégrées.|
| [`set_embedded_object(self, link_to_file, object_data, source_file_name, display_as_icon, label, update_icon)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/set_embedded_object/#bool-bytes-str-bool-str-bool) | Définit les données d'objet intégrées.|
| [`get_result_of_smart_art(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/get_result_of_smart_art/#) | Conversion d'art intelligent en formes groupées.|
| [`to_front_or_back(self, orders)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/to_front_or_back/#int) | Amène la forme vers l'avant ou envoie la forme vers l'arrière.|
| [`get_locked_property(self, type)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/get_locked_property/#aspose.cells.drawing.shapelocktype) | Obtient la valeur de la propriété verrouillée.|
| [`set_locked_property(self, type, value)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/set_locked_property/#aspose.cells.drawing.shapelocktype-bool) | Définissez la propriété verrouillée.|
| [`add_hyperlink(self, address)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/add_hyperlink/#str) | Ajoute un lien hypertexte à la forme.|
| [`remove_hyperlink(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/remove_hyperlink/#) | Supprime l'hyperlien de la forme.|
| [`move_to_range(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/move_to_range/#int-int-int-int) | Déplace la forme vers une plage spécifiée.|
| [`align_top_right_corner(self, top_row, right_column)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/align_top_right_corner/#int-int) | Déplace l'image vers le coin supérieur droit.|
| [`get_connection_points(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/get_connection_points/#) | Obtenez les points de connexion|
| [`get_linked_cell(self, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/get_linked_cell/#bool-bool) | Obtient la plage liée à la valeur du contrôle.|
| [`set_linked_cell(self, formula, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/set_linked_cell/#str-bool-bool) | Définit la plage liée à la valeur du contrôle.|
| [`get_input_range(self, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/get_input_range/#bool-bool) | Obtient la plage utilisée pour remplir le contrôle.|
| [`set_input_range(self, formula, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/set_input_range/#str-bool-bool) | Définit la plage utilisée pour remplir le contrôle.|
| [`update_selected_value(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/update_selected_value/#) | Mettre à jour la valeur sélectionnée par la valeur de la cellule liée.|
| [`calculate_text_size(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/calculate_text_size/#) | Recalculer la zone de texte|
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Formate certains caractères avec le paramètre de police.|
| [`characters(self, start_index, length)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/characters/#int-int) |Renvoie un objet Characters qui représente une plage de caractères dans le texte.|
| [`get_characters(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/get_characters/#) | Renvoie tous les objets Characters<br/>qui représente une plage de caractères dans le texte.|
| [`get_rich_formattings(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/get_rich_formattings/#) | Renvoie tous les objets Characters<br/>qui représente une plage de caractères dans le texte.|
| [`remove_active_x_control(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/remove_active_x_control/#) | Supprimer le contrôle ActiveX.|
| [`is_same_setting(self, obj)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/is_same_setting/#any) | Renvoie si la forme est la même.|
| [`get_actual_box(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/get_actual_box/#) | Obtenez la position et la taille réelles de la forme (après avoir appliqué la rotation, le retournement, etc.)|
| [`fit_to_text_size(self)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/fit_to_text_size/#) | Recalculer une zone de texte adaptée à l'affichage de tout le contenu textuel.|
| [`set_native_source_full_name(self, source_full_name)`](/cells/python-net/fr/aspose.cells.drawing/oleobject/set_native_source_full_name/#str) | Définit le nom complet du fichier source natif avec le chemin.|



###  Exemple

```python
from aspose.cells import Workbook
import bytearray

# Instantiate a new Workbook.
workbook = Workbook()
# Get the first worksheet.
sheet = workbook.worksheets[0]
# Define a string variable to store the image path.
ImageUrl = "school.jpg"
# Get the picture into the streams.
fs = open(ImageUrl, "rb")
# Define a byte array.
imageData = bytearray(utils.filesize(fs))
# Obtain the picture into the array of bytes from streams.
fs.readinto(imageData)
# Close the stream.
fs.close()
# Get an excel file path in a variable.
path = "Book1.xls"
# Get the file into the streams.
fs = open(path, "rb")
# Define an array of bytes.
objectData = bytearray(utils.filesize(fs))
# Store the file from streams.
fs.readinto(objectData)
# Close the stream.
fs.close()
# Add an Ole object into the worksheet with the image
# shown in MS Excel.
sheet.ole_objects.add(14, 3, 200, 220, imageData)
# Set embedded ole object data.
sheet.ole_objects[0].object_data = objectData
# Save the excel file
workbook.save(r"oleobjects.xls")

```

###  Voir également
* module [`aspose.cells.drawing`](..)
* classe [`GlowEffect`](/cells/python-net/fr/aspose.cells.drawing/gloweffect)
* classe [`OleObject`](/cells/python-net/fr/aspose.cells.drawing/oleobject)
* classe [`ReflectionEffect`](/cells/python-net/fr/aspose.cells.drawing/reflectioneffect)
* classe [`ShadowEffect`](/cells/python-net/fr/aspose.cells.drawing/shadoweffect)
* classe [`Shape`](/cells/python-net/fr/aspose.cells.drawing/shape)
