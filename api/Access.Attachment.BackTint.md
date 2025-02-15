---
title: Attachment.BackTint property (Access)
keywords: vbaac10.chm14632
f1_keywords:
- vbaac10.chm14632
ms.prod: access
api_name:
- Access.Attachment.BackTint
ms.assetid: f81ef313-0b84-a061-c58d-e433b01167f4
ms.date: 02/07/2019
ms.localizationpriority: medium
---


# Attachment.BackTint property (Access)

Gets or sets the tint that is applied to the theme color in the **[BackColor](access.attachment.backcolor.md)** property of the specified object. Read/write **Single**.


## Syntax

_expression_.**BackTint**

_expression_ A variable that represents an **[Attachment](Access.Attachment.md)** object.


## Remarks

The **BackTint** property contains a numeric expression that can be used to lighten the theme color in the **BackColor** property. The default value of the **BackTint** property is 100, which is neutral, and does not change the theme color. 

To lighten the color, first determine the percentage by which to lighten from 1 to 100, and then subtract that value as a whole number from 100 and use the remainder. For example, to lighten the theme color tint by 75%, subtract 75 from 100 and use the remainder, which is 25.

This property is not surfaced in the property sheet.


## Example

The following code example lightens the **BackColor** property by 75%.

```vb
Me.ctl.BackTint=25
```


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]