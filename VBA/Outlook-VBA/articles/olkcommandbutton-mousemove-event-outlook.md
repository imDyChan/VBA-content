---
title: OlkCommandButton.MouseMove Event (Outlook)
keywords: vbaol11.chm1000123
f1_keywords:
- vbaol11.chm1000123
ms.prod: outlook
api_name:
- Outlook.OlkCommandButton.MouseMove
ms.assetid: 2d489bea-a8b9-bcbc-045e-696d6ef46f1f
ms.date: 06/08/2017
---


# OlkCommandButton.MouseMove Event (Outlook)

Occurs after a mouse movement has been registered over the control.


## Syntax

 _expression_ . **MouseMove**( **_Button_** , **_Shift_** , **_X_** , **_Y_** )

 _expression_ A variable that represents an **OlkCommandButton** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Button_|Required| **Integer**|An  **[OlMouseButton](olmousebutton-enumeration-outlook.md)** constant that specifies which button on the mouse has been pressed.|
| _Shift_|Required| **Integer**|A bitwise-OR mask of constants in the  **[OlShiftState](olshiftstate-enumeration-outlook.md)** enumeration that specifies whether the **SHIFT**,  **CTRL**, or  **ALT** keys have been pressed.|
| _X_|Required| **[OLE_XPOS_CONTAINER]**|Identifies the location of the mouse cursor on the X-axis relative to the form.|
| _Y_|Required| **[OLE_YPOS_CONTAINER]**|Identifies the location of the mouse cursor on the Y-axis relative to the form.|

## Remarks

Pressing the  **ALT** key fires the **MouseMove** event.


## See also


#### Concepts


[OlkCommandButton Object](olkcommandbutton-object-outlook.md)

