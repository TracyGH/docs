---
title: "Value types table - C# Reference"
ms.custom: seodec18

ms.date: 08/24/2018
helpviewer_keywords: 
  - "value types [C#], table"
  - "types [C#], value types"
  - "types [C#], suffixes"
ms.assetid: 67d8f631-b6e3-4d83-9910-5ec497f8c5f3
---
# Value types table (C# Reference)

The following table shows the C# value types:

|Value type|Category|Type suffix|
|----------------|--------------|-----------------|
|[bool](bool.md)|Boolean||
|[byte](../builtin-types/integral-numeric-types.md)|Unsigned, numeric, [integral](../builtin-types/integral-numeric-types.md)||
|[char](char.md)|Unsigned, numeric, [integral](../builtin-types/integral-numeric-types.md)
)||
|[decimal](decimal.md)|Numeric, [floating-point](floating-point-types-table.md)|M or m|
|[double](double.md)|Numeric, [floating-point](floating-point-types-table.md)|D or d|
|[enum](enum.md)|Enumeration||
|[float](float.md)|Numeric, [floating-point](floating-point-types-table.md)|F or f|
|[int](../builtin-types/integral-numeric-types.md)|Signed, numeric, [integral](../builtin-types/integral-numeric-types.md)||
|[long](../builtin-types/integral-numeric-types.md)|Signed, numeric, [integral](../builtin-types/integral-numeric-types.md)|L or l|
|[sbyte](../builtin-types/integral-numeric-types.md)|Signed, numeric, [integral](../builtin-types/integral-numeric-types.md)||
|[short](../builtin-types/integral-numeric-types.md)|Signed, numeric, [integral](../builtin-types/integral-numeric-types.md)||
|[struct](struct.md)|User-defined structure||
|[uint](../builtin-types/integral-numeric-types.md)|Unsigned, numeric, [integral](../builtin-types/integral-numeric-types.md)|U or u|
|[ulong](../builtin-types/integral-numeric-types.md)|Unsigned, numeric, [integral](../builtin-types/integral-numeric-types.md)|UL, Ul, uL, ul, LU, Lu, lU, or lu|
|[ushort](../builtin-types/integral-numeric-types.md)|Unsigned, numeric, [integral](../builtin-types/integral-numeric-types.md)||

## Remarks

You use a type suffix to specify a type of a numerical literal. For example:

```csharp
decimal a = 0.1M;
```

If an [integer numerical literal](~/_csharplang/spec/lexical-structure.md#integer-literals) has no suffix, it has the first of the following types in which its value can be represented: `int`, `uint`, `long`, `ulong`.

If a [real numerical literal](~/_csharplang/spec/lexical-structure.md#real-literals) has no suffix, it's of type `double`.

## See also

- [C# Reference](../index.md)
- [C# Programming Guide](../../programming-guide/index.md)
- [Default values table](default-values-table.md)
- [Value types](value-types.md)
- [Formatting numeric results table](formatting-numeric-results-table.md)
