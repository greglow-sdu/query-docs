---
description: "Learn more about: Duration.TotalMinutes"
title: "Duration.TotalMinutes | Microsoft Docs"
ms.date: 3/11/2022
ms.service: powerquery

ms.reviewer: ehvonleh
ms.topic: reference
author: dougklopfenstein
ms.author: dougklo

---
# Duration.TotalMinutes

## Syntax

<pre>
Duration.TotalMinutes(<b>duration</b> as nullable duration) as nullable number 
</pre>
  
## About

Returns the total minutes spanned by the provided `duration` value, `duration`.

## Example 1

Find the total minutes spanned in #duration(5, 4, 3, 2).

**Usage**

```powerquery-m
Duration.TotalMinutes(#duration(5, 4, 3, 2))
```

**Output**

`7443.0333333333338`
