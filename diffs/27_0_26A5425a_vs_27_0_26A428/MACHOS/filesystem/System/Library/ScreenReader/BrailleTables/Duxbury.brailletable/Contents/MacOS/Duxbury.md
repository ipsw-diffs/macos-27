## Duxbury

> `/System/Library/ScreenReader/BrailleTables/Duxbury.brailletable/Contents/MacOS/Duxbury`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 126.0.0.0.0
-  __TEXT.__text: 0x28de8
+  __TEXT.__text: 0x28a58
   __TEXT.__auth_stubs: 0x5c0
   __TEXT.__objc_stubs: 0x10c0
   __TEXT.__objc_methlist: 0x95c

   __TEXT.__objc_methtype: 0x454
   __TEXT.__ustring: 0x4
   __TEXT.__gcc_except_tab: 0xc4
-  __TEXT.__unwind_info: 0x4a0
+  __TEXT.__unwind_info: 0x5f8
   __DATA_CONST.__const: 0x1b8
   __DATA_CONST.__cfstring: 0xb20
   __DATA_CONST.__objc_classlist: 0xe0
Functions:
~ -[DBTDuxburyBrailleTranslator _tableInfoForKey:] : 464 -> 452
~ -[DBTDuxburyBrailleTranslator loadNemethTable] : 96 -> 84
~ -[DBTDuxburyBrailleTranslator _populatePrintBrailleForTextLocations:inLength:outLength:translationHandle:offsetToBraille:prefixCodeLength:preprocessedMap:optimize:] : 976 -> 972
~ -[DBTDuxburyBrailleTranslator _scrubDollarCodesInBuffer:originalLength:originalLocations:newLocations:convertASCIIBrailleToUnicode:limitRange:] : 336 -> 324
~ -[DBTDuxburyBrailleTranslator _printBrailleForText:mode:locations:textPositionsRange:textFormattingRanges:optimize:] : 1288 -> 1276
~ -[DBTDuxburyBrailleTranslator printBrailleForText:mode:locations:textPositionsRange:textFormattingRanges:] : 344 -> 332
~ -[DBTDuxburyBrailleTranslator printBrailleForTechnicalText:useTechnicalTable:locations:] : 176 -> 164
~ -[DBTDuxburyBrailleTranslator _textForPrintBraille:mode:locations:optimize:] : 724 -> 712
~ -[DBTDuxburyBrailleTranslator textForPrintBraille:mode:locations:] : 224 -> 212
~ -[DBTDuxburyBrailleTranslator _eightDotPrintBrailleForText:locations:textFormattingRanges:] : 1228 -> 1208
~ -[DBTDuxburyBrailleTranslator _eightDotTextForPrintBraille:locations:] : 832 -> 812
~ -[DBTDuxburyBrailleTranslator .cxx_destruct] : 104 -> 92
~ _OUTLINED_FUNCTION_0 : 52 -> 40
~ _DBTNSStringFromWideCharBuffer : 160 -> 148
~ _DBTAppendNSStringIntoWideCharBufferAtOffset : 192 -> 180
~ _LoadEightDotTable : 60568 -> 60556
~ _BRLDISP_Translate : 228 -> 232
~ _BRLDISP_LocateSource : 392 -> 388
~ _BRLDISP_LocateSourceLinear : 392 -> 388
~ _BRLTRN_TranslateAutoString : 384 -> 376
~ _BRLTRN_TranslateStringEx : 2484 -> 2472
~ -[DBTSSeparatedByBunSetsuPreprocessor preprocessPrintString:withLocationMap:isEightDot:textFormattingRanges:] : 1680 -> 1668
~ _chiini_strdup : 112 -> 100
~ -[DBTDuxburyFormatNode firstChildMatchingBlock:] : 248 -> 236
~ -[DBTDuxburyFormatNode LaTeXRepresentation] : 320 -> 308
~ -[DBTDuxburyFormatNode _debugDescriptionWithIndent:] : 488 -> 476
~ +[DBTDuxburyFormatTextNode LaTeXCommandForString:] : 208 -> 196
~ ___50+[DBTDuxburyFormatTextNode LaTeXCommandForString:]_block_invoke : 160 -> 148
~ -[DBTDuxburyFormatTextNode description] : 152 -> 140
~ -[DBTDuxburyFormatBNode LaTeXRepresentation] : 136 -> 124
~ -[DBTDuxburyFormatENode LaTeXRepresentation] : 308 -> 296
~ -[DBTDuxburyFormatENode expressionNode] : 44 -> 32
~ -[DBTDuxburyFormatFNode LaTeXRepresentation] : 264 -> 252
~ -[DBTDuxburyFormatIXRTNode LaTeXRepresentation] : 244 -> 232
~ -[DBTDuxburyFormatPNode LaTeXRepresentation] : 136 -> 124
~ -[DBTDuxburyFormatSQRTNode LaTeXRepresentation] : 136 -> 124
~ _dxchi_unimap_destroy : 140 -> 128
~ -[DBTComposedCharactersPreprocessor preprocessPrintString:withLocationMap:isEightDot:textFormattingRanges:] : 520 -> 508
~ _dxxins : 220 -> 208
~ _getprm : 692 -> 672
~ _preder : 108 -> 96
~ _erm : 832 -> 808
~ _fopes : 192 -> 180
~ _dxios_stream_printf : 2268 -> 2260
~ _dxios_buf_write : 256 -> 252
~ _dxios_buf_read : 96 -> 92
~ _dxios_stream_activate_fp : 200 -> 188
~ -[NSMutableDictionary(BRLHelper) setArrayObject:forKey:] : 176 -> 164
~ -[DBTTextFormatterPreprocessor preprocessPrintString:withLocationMap:isEightDot:textFormattingRanges:] : 2164 -> 2152
~ _jreaf : 76 -> 64
~ _lfiniq : 92 -> 80
~ _linecq : 368 -> 344
~ +[DBTDuxburyFormatParser allCodeNodes] : 372 -> 360
~ -[DBTDuxburyFormatParser LaTeXRepresentationOfString:error:] : 108 -> 96
~ -[DBTDuxburyFormatParser _parseInputString:error:] : 2072 -> 2060
~ _dxnin_engine_destroy : 68 -> 56
~ _dxnin_engine_create : 96 -> 84
~ _dxnin_engine_reactivate : 128 -> 116
~ _prdtf : 160 -> 148
~ _DBTLog : 68 -> 56
~ ___DBTLog_block_invoke : 72 -> 60
~ _DBTLogFormatParser : 68 -> 56
~ ___DBTLogFormatParser_block_invoke : 72 -> 60
~ -[DBTSSepratedBySpacesPreprocessor preprocessPrintString:withLocationMap:isEightDot:textFormattingRanges:] : 708 -> 696
~ _stacq : 1540 -> 1492
~ _scswp : 396 -> 384
~ _ttmark : 112 -> 100
~ _ttgesp : 328 -> 316
~ _ttsng : 116 -> 104
~ _trcedbc : 916 -> 912
~ _whraii : 176 -> 152
~ -[DBTStringTransformPrintPreprocessor preprocessPrintString:withLocationMap:isEightDot:textFormattingRanges:] : 1420 -> 1408
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
```
