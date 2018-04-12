---
title: "Menu Element"


manager: soliver
ms.date: 3/9/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Server Ribbon schema
api_type:
- schema
ms.assetid: 1bc70fb9-bcf5-4758-a3dd-a3af3b4a745f
description: "Last modified: March 09, 2015"
---

# Menu Element

 
  
 **Applies to:** SharePoint 2016 | SharePoint Foundation 2013 | SharePoint Online | SharePoint Server 2013
  
Defines a menu control.
  
```
<Menu
  Id="Text"
  MaxWidth="Integer"
/>
```

## Elements and attributes

The following sections describe attributes, child elements, and parent elements.

### Attributes

|**Attribute**|**Description**|
|:-----|:-----|
|**Id** <br/> |Required. A string that identifies the element, such as "Ribbon.WikiPageTab.EditAndCheckout.SaveEdit.Menu".  <br/> |
|**MaxWidth** <br/> |Optional. The maximum width in pixels.  <br/> |
   
### Child elements

||
|:-----|
|[MenuSection](menusection-element.md)|
   
### Parent elements

||
|:-----|
|[CommandUIDefinition](commanduidefinition-element.md) <br/> |
|[ComboBox](combobox-element.md) <br/> |
|[DropDown](dropdown-element.md) <br/> |
|[FlyoutAnchor](flyoutanchor-element.md) <br/> |
|[Jewel](jewel-element.md) <br/> |
|[MRUSplitButton](mrusplitbutton-element.md) <br/> |
|[SplitButton](splitbutton-element.md) <br/> |
   
### Occurrences

||
|:-----|
|Minimum: 0  <br/> Maximum: 1  <br/> |
   
