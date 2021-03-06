---
title: ValidateFieldValueEventArgs class
description: This topic describes the ValidateFieldValueEventArgs class.
author: robinarh
manager: tonyafehr
ms.date: 06/25/2020
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-platform
ms.technology: 

audience: Developer
ms.reviewer: rhaertle
ms.search.scope: Operations
ms.search.region: Global
ms.author: rhaertle
ms.search.validFrom: 2016-02-28
ms.dyn365.ops.version: AX 7.0.0
---

# Class ValidateFieldValueEventArgs

[!include [banner](../../includes/banner.md)]

```xpp
class ValidateFieldValueEventArgs extends ValidateEventArgs
```

## Remarks

## Examples

## Methods

| Method                                                         | Description |
|----------------------------------------------------------------|-------------|
| public str parmFieldName()                                     |             |
| public int parmArrayIndex()                                    |             |
| public void new(str fieldName, int arrayIndex, boolean result) |             |

## Method parmFieldName

```xpp
public str parmFieldName()
```

### Return Value - parmFieldName

## Method parmArrayIndex

```xpp
public int parmArrayIndex()
```

### Return Value - parmArrayIndex

## Method new

```xpp
public void new(str fieldName, int arrayIndex, boolean result)
```

### Parameters - new

fieldName  

<!-- -->

arrayIndex  

<!-- -->

result  

