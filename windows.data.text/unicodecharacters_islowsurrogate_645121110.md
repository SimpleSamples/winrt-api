---
-api-id: M:Windows.Data.Text.UnicodeCharacters.IsLowSurrogate(System.UInt32)
-api-type: winrt method
-api-device-family-note: xbox
---

<!-- Method syntax
public bool IsLowSurrogate(System.UInt32 codepoint)
-->

# Windows.Data.Text.UnicodeCharacters.IsLowSurrogate

## -description
Determines if a specified Unicode character is a low surrogate.

## -parameters
### -param codepoint
A Unicode character. This must be in the proper range: 0 &lt;= *codepoint* &lt;= 0x10FFFF.

## -returns
**TRUE** if *codepoint* is a low surrogate; otherwise **FALSE**.

## -remarks


## -examples

## -see-also
[GetCodepointFromSurrogatePair](unicodecharacters_getcodepointfromsurrogatepair.md), [Surrogates and Supplementary Characters](http://msdn.microsoft.com/library/0dea39e2-a2b4-47fc-b44a-56af8ba1e346)