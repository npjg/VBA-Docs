---
title: NavigationButton.ThemeFontIndex property (Access)
keywords: vbaac10.chm14610
f1_keywords:
- vbaac10.chm14610
ms.prod: access
api_name:
- Access.NavigationButton.ThemeFontIndex
ms.assetid: fb9dab70-239b-f5c9-a160-f2ce23678598
ms.date: 03/02/2019
ms.localizationpriority: medium
---


# NavigationButton.ThemeFontIndex property (Access)

Gets or sets the font index that represents a font in the applied theme associated with the **FontName** property of the specified object. Read/write **Long**.


## Syntax

_expression_.**ThemeFontIndex**

_expression_ A variable that represents a **[NavigationButton](Access.NavigationButton.md)** object.


## Remarks

The **ThemeFontIndex** property uses one of the values listed in the following table.

|Value|Description|
|:-----|:-----|
|0|Header font|
|1 (Default)|Detail font|

If no theme is applied, the **ThemeFontIndex** property contains -1.

This property is not surfaced in the property sheet.



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]