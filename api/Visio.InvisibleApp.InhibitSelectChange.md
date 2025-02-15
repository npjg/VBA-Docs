---
title: InvisibleApp.InhibitSelectChange property (Visio)
keywords: vis_sdr.chm17550675
f1_keywords:
- vis_sdr.chm17550675
ms.prod: visio
api_name:
- Visio.InvisibleApp.InhibitSelectChange
ms.assetid: 1e88d64d-281e-654c-7801-dfb2ac132ad8
ms.date: 06/26/2019
ms.localizationpriority: medium
---


# InvisibleApp.InhibitSelectChange property (Visio)

Determines whether shapes added to the drawing page by Automation are selected. Read/write.


## Syntax

_expression_.**InhibitSelectChange**

_expression_ A variable that represents an **[InvisibleApp](Visio.InvisibleApp.md)** object.


## Return value

Boolean


## Remarks

Use the **InhibitSelectChange** property to control shape selection and increase performance when dropping a series of shapes in the drawing window programmatically. When the **InhibitSelectChange** property is **True**, Microsoft Visio does not select any shapes after they are dropped. Your solution, however, can select shapes.

Additionally, Visio attempts to preserve currently selected shapes whenever possible, unless shapes are deselected by the solution.

If a program neglects to turn the **InhibitSelectChange** property off (**False**) after turning it on, the Visio instance turns it back off when the user performs an operation.

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]