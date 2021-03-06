---
title: "Insert Element (XMLA) | Microsoft Docs"
ms.custom: ""
ms.date: "03/03/2017"
ms.prod: analysis-services
ms.prod_service: "analysis-services, azure-analysis-services"
ms.service: ""
ms.component: ""
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 
  

ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "Insert Element"
apilocation: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine"
apitype: "Schema"
applies_to: 
  - "SQL Server 2016 Preview"
f1_keywords: 
  - "urn:schemas-microsoft-com:xml-analysis#Insert"
  - "http://schemas.microsoft.com/analysisservices/2003/engine#Insert"
  - "microsoft.xml.analysis.insert"
helpviewer_keywords: 
  - "Insert command"
ms.assetid: d1137033-cc19-4bcb-b93d-8575f17bea6b
caps.latest.revision: 12
author: "Minewiskan"
ms.author: "owend"
manager: "kfile"
---
# Insert Element (XMLA)
[!INCLUDE[ssas-appliesto-sqlas-aas](../../../includes/ssas-appliesto-sqlas-aas.md)]
  Inserts attribute members into a dimension.  
  
## Syntax  
  
```xml  
  
<Command>  
   <Insert>  
      <Object>...</Object>  
      <Attributes>...</Attributes>  
   </Insert>  
</Command>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|None|  
|Default value|None|  
|Cardinality|0-n: Optional element that can occur more than once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[Command](../../../analysis-services/xmla/xml-elements-properties/command-element-xmla.md)|  
|Child elements|[Attributes](../../../analysis-services/xmla/xml-elements-properties/attributes-element-xmla.md), [Object](../../../analysis-services/xmla/xml-elements-properties/object-element-dimension-xmla.md)|  
  
## Remarks  
 The **Insert** command inserts new attribute members into a write-enabled dimension.  
  
 For more information about deleting members, see [Inserting, Updating, and Dropping Members &#40;XMLA&#41;](../../../analysis-services/multidimensional-models-scripting-language-assl-xmla/inserting-updating-and-dropping-members-xmla.md).  
  
## See Also  
 [Drop Element &#40;XMLA&#41;](../../../analysis-services/xmla/xml-elements-commands/drop-element-xmla.md)   
 [Update Element &#40;XMLA&#41;](../../../analysis-services/xmla/xml-elements-commands/update-element-xmla.md)   
 [Commands &#40;XMLA&#41;](../../../analysis-services/xmla/xml-elements-commands/xml-elements-commands.md)  
  
  
