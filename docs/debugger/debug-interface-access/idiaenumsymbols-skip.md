---
description: "Skips a specified number of symbols in an enumeration sequence."
title: "IDiaEnumSymbols::Skip"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaEnumSymbols::Skip method"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaEnumSymbols::Skip

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Skips a specified number of symbols in an enumeration sequence.

## Syntax

```C++
HRESULT Skip ( 
   ULONG celt
);
```

#### Parameters
 celt

[in] The number of symbols in the enumeration sequence to skip.

## Return Value
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` if there are no more symbols to skip.

## See also
- [IDiaEnumSymbols](../../debugger/debug-interface-access/idiaenumsymbols.md)
