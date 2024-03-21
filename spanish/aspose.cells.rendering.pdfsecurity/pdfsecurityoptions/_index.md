---
title: PdfSecurityOptions clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
##  PdfSecurityOptions clase
Opciones de cifrado y permisos de acceso para un documento PDF.
PDF/A no permite la configuración de seguridad.



El tipo PdfSecurityOptions expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) | El constructor de PdfSecurityOptions|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [user_password](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Obtiene o establece la contraseña de usuario necesaria para abrir el documento cifrado PDF.|
| [owner_password](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Obtiene o establece la contraseña del propietario para el documento cifrado PDF.|
| [print_permission](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Indica si se permite imprimir el documento.|
| [modify_document_permission](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) |Indica si se permitirá modificar el contenido del documento mediante operaciones distintas a las controladas<br/> por [`PdfSecurityOptions.annotations_permission`](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) y [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | Permiso para copiar o extraer contenido Obsoleto según referencia PDF.|
| [annotations_permission](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Indica si se permite agregar o modificar anotaciones de texto, completar campos de formulario interactivo.|
| [fill_forms_permission](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Indica si se debe permitir completar los campos del formulario interactivo existente (incluidos los campos de firma),<br/> incluso si [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) está claro.|
| [extract_content_permission](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Indica si se permite copiar o extraer texto y gráficos del documento.<br/> por operaciones distintas a la controlada por [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content).|
| [accessibility_extract_content](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) | Indica si se permitirá extraer texto y gráficos (para apoyar la accesibilidad de usuarios con discapacidades o para otros fines).|
| [assemble_document_permission](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Indica si se permite ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o imágenes en miniatura),<br/> incluso si [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) está claro.|
| [full_quality_print_permission](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Indica si se permitirá imprimir el documento en una representación desde<br/>el cual se podría generar una copia digital fiel del contenido de PDF.|



###  Ver también
* módulo [`aspose.cells.rendering.pdfsecurity`](..)
