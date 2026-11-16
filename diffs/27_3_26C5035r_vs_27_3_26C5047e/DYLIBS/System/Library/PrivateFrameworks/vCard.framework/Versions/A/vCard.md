## vCard

> `/System/Library/PrivateFrameworks/vCard.framework/Versions/A/vCard`

```diff

-3846.300.31.0.0
-  __TEXT.__text: 0x251c0
+3846.300.54.0.0
+  __TEXT.__text: 0x252d0
   __TEXT.__objc_methlist: 0x3a38
   __TEXT.__const: 0x1d8
   __TEXT.__cstring: 0x1ba1
Functions:
~ +[CNVCardDataAnalyzer data:byteAtIndex:] : 52 -> 112
~ -[CNVCardLexer initWithData:] : 380 -> 388
~ -[CNVCardLexer nextQuotedPrintableData] : 488 -> 496
~ -[CNVCardLexer nextEscapedCharacter] : 192 -> 240
~ -[CNVCardLexer nextSingleByteStringInEncoding:quotedPrintable:stopTokens:trim:maximumValueLength:] : 896 -> 908
~ -[CNVCardLexer nextQuotedStringValueInEncoding:] : 216 -> 272
~ -[CNVCardLexer expandRange:untilNextByteIs:] : 256 -> 228
~ -[CNVCardLexer tokenAtCursor] : 408 -> 448
~ -[CNVCardLexer charAtPosition:withOffset:] : 56 -> 100
~ sub_227d9700c -> sub_229930104 : 260 -> 284
```
