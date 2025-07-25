---
title: PdfSecurityOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
## PdfSecurityOptions类
PDF 文档的加密和访问权限选项。
PDF/A 不允许安全设置。



PdfSecurityOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) |PdfSecurityOptions 的构造函数|


### 属性
|属性|描述|
| :- | :- |
| [user_password](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) |获取或设置打开加密的 PDF 文档所需的用户密码。|
| [owner_password](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) |获取或设置加密 PDF 文档的所有者密码。|
| [print_permission](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) |指示是否允许打印文档。|
| [modify_document_permission](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) |指示是否允许通过受控操作以外的操作修改文档内容<br/>编号为 [`PdfSecurityOptions.annotations_permission`](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission)、[`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) 和 [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission)。|
| [extract_content_permission_obsolete](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) |复制或提取内容的权限根据 PDF 参考已过时。|
| [annotations_permission](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) |指示是否允许添加或修改文本注释、填写交互式表单字段。|
| [fill_forms_permission](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) |是否允许填写现有的交互式表单字段（包括签名字段），<br/>即使 [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) 很清楚。|
| [extract_content_permission](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) |指示是否允许从文档中复制或以其他方式提取文本和图形<br/>由 [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content) 控制范围以外的操作。|
| [accessibility_extract_content](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) |指示是否允许提取文本和图形（以支持残障用户的可访问性或用于其他目的）。|
| [assemble_document_permission](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) |指示是否允许组装文档（插入、旋转或删除页面以及创建书签或缩略图），<br/>即使 [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) 很清楚。|
| [full_quality_print_permission](/cells/python-net/zh/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) |指示是否允许将文档打印到表示形式<br/>可以生成 PDF 内容的忠实数字副本。|



### 也可以看看
* 模块[`aspose.cells.rendering.pdfsecurity`](..)
