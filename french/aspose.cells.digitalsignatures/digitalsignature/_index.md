---
title: DigitalSignature classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells.digitalsignatures/digitalsignature/
is_root: false
---
##  DigitalSignature classe
Signature dans le dossier.



Le type DigitalSignature expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self, certificate, comments, sign_time)`](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/__init__/#system.security.cryptography.x509certificates.x509certificate2-str-datetime) | Constructeur de signature numérique. Utilise l'implémentation .Net.|
| [`__init__(self, raw_data, password, comments, sign_time)`](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/__init__/#bytes-str-str-datetime) |Constructeur de signature numérique. Utilise l'implémentation Bouncy Castle.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [certificate](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/certificate) | Objet de certificat qui a été utilisé pour signer le document.|
| [comments](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/comments) | Le but de la signature.|
| [sign_time](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/sign_time) | L'heure à laquelle le document a été signé.|
| [id](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/id) | Spécifie un GUID qui peut être référencé avec le GUID de la ligne de signature stockée dans le contenu du document.<br/> La valeur par défaut est Vide (tous les zéros) Guid.|
| [text](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/text) | Spécifie le texte de la signature réelle dans la signature numérique.<br/> La valeur par défaut est vide.|
| [image](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/image) | Spécifie une image pour la signature numérique.<br/> La valeur par défaut est null.|
| [provider_id](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/provider_id) | Spécifie l'ID de classe du fournisseur de signature.<br/> La valeur par défaut est Vide (tous les zéros) Guid.|
| [is_valid](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/is_valid) | Si cette signature numérique est valide et que le document n’a pas été falsifié,<br/> cette valeur sera vraie.|
| [x_ad_es_type](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignature/x_ad_es_type) | Type XAdES.<br/> La valeur par défaut est Aucun (XAdES est désactivé).|



###  Voir également
* module [`aspose.cells.digitalsignatures`](..)
