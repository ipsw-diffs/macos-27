## UIFoundation

> `/System/Library/PrivateFrameworks/UIFoundation.framework/Versions/A/UIFoundation`

```diff

 1056.0.0.0.0
-  __TEXT.__text: 0x145b40
+  __TEXT.__text: 0x145ba0
   __TEXT.__objc_methlist: 0xd10c
   __TEXT.__const: 0x12f4
   __TEXT.__cstring: 0x1743d

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 6122
+  Functions: 6124
   Symbols:   13705
   CStrings:  3979
 
Functions:
~ -[NSATSGlyphStorage setGlyphRange:characterRange:] : 3408 -> 3404
~ -[__NSATSStringSegment _setOriginalString:range:] : 256 -> 252
~ -[NSATSGlyphStorage _resolvePositionalStakeGlyphsForLineFragment:lineFragmentRect:minPosition:maxPosition:maxLineFragmentWidth:breakHint:] : 3200 -> 3116
~ -[NSLineFragmentRenderingContext drawAtPoint:inContext:] : 2576 -> 2580
~ -[NSLayoutManager(NSPrivate) _fillGlyphHoleForCharacterRange:startGlyphIndex:desiredNumberOfCharacters:] : 716 -> 728
~ -[NSLayoutManager setGlyphs:properties:characterIndexes:font:forGlyphRange:] : 400 -> 408
~ __NSGlyphTreeInsertGlyphs : 1896 -> 1928
~ -[NSATSGlyphStorage _collectElasticRangeSurroundingCharacterAtIndex:minimumCharacterIndex:] : 1956 -> 1964
~ -[NSATSLineFragment saveMorphedGlyphs:] : 2516 -> 2584
~ -[NSATSLineFragment saveWithGlyphOrigin:] : 2788 -> 2716
~ -[NSLayoutManager(NSPrivate) _insertionPointHelperForGlyphAtIndex:] : 4004 -> 4040
~ ___NSGetClusterHeadWithLimit : 1108 -> 1112
~ -[NSATSGlyphStorage childGlyphStorageWithCharacterRange:] : 384 -> 388
~ -[NSATSGlyphStorage _widthForStringRange:] : 1068 -> 1076
~ -[NSFont getBoundingRects:forCGGlyphs:count:] : 352 -> 344
~ -[NSATSGlyphStorage _createEllipsisRunWithStringRange:attributes:] : 1176 -> 1172
~ -[NSLineFragmentRenderingContext getMaximumAscender:minimumDescender:] : 364 -> 360
~ -[NSFont getBoundingRects:forGlyphs:count:] : 332 -> 336
~ -[NSFont getAdvancements:forGlyphs:count:] : 500 -> 504
~ -[NSTextLayoutManager rangeForTextContainerAtIndex:] : 108 -> 104
~ -[NSTextLayoutManager usageBoundsInTextContainerAtIndex:] : 436 -> 432
~ -[NSTextContentStorage enumerateTextElementsFromLocation:options:usingBlock:] : 4608 -> 4612
~ ___50-[NSTextContentStorage synchronizeToBackingStore:]_block_invoke : 104 -> 100
~ _____NSTextContentStorageReleaseElementsInRange_block_invoke : 72 -> 68
~ _____NSTextContentStorageFillAttributedStringWithElementsInIndexRange_block_invoke : 304 -> 300
~ _OUTLINED_FUNCTION_1 : 24 -> 12
~ -[NSATSGlyphStorage setStringIndex:forIndex:] : 384 -> 396
~ -[NSATSGlyphStorage moveGlyphsTo:from:] : 344 -> 352
~ -[NSLineFragmentRenderingContext initWithTextStorage:runs:glyphOrigin:lineFragmentWidth:elasticWidth:usesScreenFonts:isRTL:applicationFrameworkContext:] : 2608 -> 2624
~ _OUTLINED_FUNCTION_1 : 24 -> 32
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ _OUTLINED_FUNCTION_3 : 32 -> 20
~ _OUTLINED_FUNCTION_5 : 20 -> 24
~ _OUTLINED_FUNCTION_7 : 20 -> 16
~ _OUTLINED_FUNCTION_8 : 16 -> 12
~ _OUTLINED_FUNCTION_9 : 12 -> 16
~ _OUTLINED_FUNCTION_11 : 16 -> 20
~ _OUTLINED_FUNCTION_12 : 16 -> 20
~ _OUTLINED_FUNCTION_16 : 12 -> 48
~ _OUTLINED_FUNCTION_17 : 32 -> 12
~ _OUTLINED_FUNCTION_19 : 40 -> 32
~ _OUTLINED_FUNCTION_22 : 12 -> 20
~ _OUTLINED_FUNCTION_23 : 20 -> 44
~ _OUTLINED_FUNCTION_25 : 44 -> 12
~ _OUTLINED_FUNCTION_26 : 16 -> 20
~ _OUTLINED_FUNCTION_27 : 20 -> 16
~ _OUTLINED_FUNCTION_31 : 12 -> 16
~ _OUTLINED_FUNCTION_32 : 12 -> 16
~ _OUTLINED_FUNCTION_33 : 40 -> 56
~ _OUTLINED_FUNCTION_34 : 40 -> 12
~ _OUTLINED_FUNCTION_36 : 12 -> 40
~ _OUTLINED_FUNCTION_37 : 32 -> 40
~ _OUTLINED_FUNCTION_41 : 16 -> 12
~ _OUTLINED_FUNCTION_42 : 16 -> 32
~ _OUTLINED_FUNCTION_43 : 16 -> 12
~ _OUTLINED_FUNCTION_44 : 16 -> 12
~ _OUTLINED_FUNCTION_47 : 12 -> 16
~ _OUTLINED_FUNCTION_48 : 28 -> 16
~ _OUTLINED_FUNCTION_49 : 36 -> 16
~ _OUTLINED_FUNCTION_50 : 36 -> 16
~ _OUTLINED_FUNCTION_51 : 36 -> 16
~ _OUTLINED_FUNCTION_52 : 36 -> 16
~ _OUTLINED_FUNCTION_53 : 36 -> 12
~ _OUTLINED_FUNCTION_54 : 20 -> 28
~ _OUTLINED_FUNCTION_55 : 20 -> 36
~ _OUTLINED_FUNCTION_56 : 12 -> 36
~ _OUTLINED_FUNCTION_57 : 20 -> 36
~ _OUTLINED_FUNCTION_59 : 20 -> 12
~ _OUTLINED_FUNCTION_60 : 12 -> 20
~ _OUTLINED_FUNCTION_61 : 12 -> 20
~ _OUTLINED_FUNCTION_62 : 12 -> 20
~ _OUTLINED_FUNCTION_65 : 20 -> 12
+ _OUTLINED_FUNCTION_68
+ _OUTLINED_FUNCTION_71
~ -[NSConcreteGlyphGenerator generateGlyphsForGlyphStorage:desiredNumberOfCharacters:glyphIndex:characterIndex:] : 3608 -> 3612
~ ___NSFillUpBidiLevels : 128 -> 148
~ ___NSInsertNominalGlyphs : 2728 -> 2676
~ -[NSTextLineFragment drawAtPoint:graphicsContext:] : 1188 -> 1192
~ _thoroughDataHash : 140 -> 144
~ ___55-[__NSTextSelectionLineFragmentInfo _fetchCaretOffsets]_block_invoke : 996 -> 1000
~ -[NSDocFormatReader _endTableRow:] : 3636 -> 3640
~ -[NSDocFormatReader _appendTextBytes:length:encoding:attributes:] : 1212 -> 1192
~ -[NSDocFormatReader _attributes2ForPageOffset:entryOffset:blockType:baseAttributes:depth:] : 7752 -> 7828
~ -[NSDocFormatReader _parseCharacterAttributes1] : 984 -> 988
~ -[NSDocFormatWriter _writeDocumentData] : 4152 -> 4144
~ -[NSCoreTypesetter _NSFastDrawString:length:attributes:paragraphStyle:typesetterBehavior:lineBreakMode:rect:padding:graphicsContext:baselineRendering:usesFontLeading:usesScreenFont:scrollable:syncAlignment:mirrored:boundingRectPointer:baselineOffsetPointer:drawingContext:] : 5156 -> 5140
~ ___NSRunCopyStringCallback : 140 -> 144
```
