---
description: "Learn more about: Duration.TotalSeconds"
title: "Duration.TotalSeconds | Microsoft Docs"
ms.date: 3/11/2022
ms.service: powerquery

ms.reviewer: ehvonleh
ms.topic: reference
author: dougklopfenstein
ms.author: dougklo

---
# Duration.TotalSeconds

## Syntax

<pre>
Duration.TotalSeconds(<b>duration</b> as nullable duration) as nullable number
</pre>
  
## About

Returns the total seconds spanned by the provided `duration` value, `duration`.

## Example 1

Find the total seconds spanned in #duration(5, 4, 3, 2).

**Usage**

```powerquery-m
Duration.TotalSeconds(#duration(5, 4, 3, 2))
```

**Output**

`446582`
