## WebContentRestrictions

> `/System/Library/PrivateFrameworks/WebContentRestrictions.framework/Versions/A/WebContentRestrictions`

```diff

-79.0.0.0.0
-  __TEXT.__text: 0x110a8
-  __TEXT.__objc_methlist: 0xc90
-  __TEXT.__const: 0x670
-  __TEXT.__cstring: 0x15d1
-  __TEXT.__gcc_except_tab: 0x1cc
+79.2.2.0.0
+  __TEXT.__text: 0x11f90
+  __TEXT.__objc_methlist: 0xd28
+  __TEXT.__const: 0x660
+  __TEXT.__cstring: 0x1621
+  __TEXT.__gcc_except_tab: 0x1d0
   __TEXT.__oslogstring: 0x4d6
   __TEXT.__ustring: 0x1bc
   __TEXT.__swift5_typeref: 0x102

   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_proto: 0x34
-  __TEXT.__unwind_info: 0x5a0
+  __TEXT.__unwind_info: 0x5c8
   __TEXT.__eh_frame: 0x2b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x130
+  __DATA_CONST.__const: 0x110
   __DATA_CONST.__objc_classlist: 0x78
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8e8
+  __DATA_CONST.__objc_selrefs: 0x9f8
   __DATA_CONST.__objc_superrefs: 0x38
   __DATA_CONST.__objc_arraydata: 0x78
-  __DATA_CONST.__got: 0x1b0
-  __AUTH_CONST.__const: 0x669
-  __AUTH_CONST.__cfstring: 0x1920
-  __AUTH_CONST.__objc_const: 0x15d0
+  __DATA_CONST.__got: 0x1b8
+  __AUTH_CONST.__const: 0x699
+  __AUTH_CONST.__cfstring: 0x1a40
+  __AUTH_CONST.__objc_const: 0x1600
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__auth_got: 0x4e8
   __AUTH.__objc_data: 0x4a0
   __AUTH.__data: 0x168
-  __DATA.__objc_ivar: 0xd8
+  __DATA.__objc_ivar: 0xdc
   __DATA.__data: 0x2a8
   __DATA.__bss: 0x690
   __DATA_DIRTY.__objc_data: 0x50

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 445
-  Symbols:   1288
-  CStrings:  266
+  Functions: 457
+  Symbols:   1335
+  CStrings:  275
 
Symbols:
+ +[WCRBrowserEngineClient _askToBrowseURLForURL:state:matchedEntry:]
+ +[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:matchedEntry:]
+ +[WCRBrowserEngineClient _displayStringForMatchedEntry:]
+ +[WCRBrowserEngineClient _matchedEntry:isOnSiteOfURL:]
+ +[WCRBrowserEngineClient _matchedEntryFromReferrer:forURL:]
+ +[WCRBrowserEngineClient _queryValueForMatchedEntry:]
+ +[WCRBrowserEngineClient _schemelessMatchedEntry:]
+ +[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:matchedEntry:language:]
+ +[WCRURLList _entry:matchesBrowserURLString:browserURLHost:]
+ +[WCRURLList _indexOfEntryInList:matchingURLString:longest:]
+ +[WCRURLList entry:matchesURLString:]
+ -[WCRURLList longestMatchingEntryForURLString:]
+ -[WCRURLList originalURLStringList]
+ -[WCRURLList setOriginalURLStringList:]
+ GCC_except_table68
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_IVAR_$_WCRURLList._originalURLStringList
+ ___131+[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:matchedEntry:language:]_block_invoke
+ ___132+[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:matchedEntry:]_block_invoke
+ ___block_descriptor_105_e8_32s40s48s56s64s72s80bs_e21_v24?0Q8"NSString"16l
+ ___block_descriptor_57_e8_32s_e28_"NSString"16?0"NSString"8l
+ _objc_msgSend$URLQueryAllowedCharacterSet
+ _objc_msgSend$_askToBrowseURLForURL:state:matchedEntry:
+ _objc_msgSend$_blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:matchedEntry:
+ _objc_msgSend$_displayStringForMatchedEntry:
+ _objc_msgSend$_entry:matchesBrowserURLString:browserURLHost:
+ _objc_msgSend$_indexOfEntryInList:matchingURLString:longest:
+ _objc_msgSend$_lp_highLevelDomain
+ _objc_msgSend$_lp_stringForcingLeftToRightDirection
+ _objc_msgSend$_matchedEntry:isOnSiteOfURL:
+ _objc_msgSend$_matchedEntryFromReferrer:forURL:
+ _objc_msgSend$_queryValueForMatchedEntry:
+ _objc_msgSend$_schemelessMatchedEntry:
+ _objc_msgSend$caseInsensitiveCompare:
+ _objc_msgSend$characterSetWithCharactersInString:
+ _objc_msgSend$decimalDigitCharacterSet
+ _objc_msgSend$entry:matchesURLString:
+ _objc_msgSend$invertedSet
+ _objc_msgSend$length
+ _objc_msgSend$longestMatchingEntryForURLString:
+ _objc_msgSend$mutableCopy
+ _objc_msgSend$objectAtIndexedSubscript:
+ _objc_msgSend$originalURLStringList
+ _objc_msgSend$rangeOfCharacterFromSet:
+ _objc_msgSend$rangeOfString:
+ _objc_msgSend$rangeOfString:options:
+ _objc_msgSend$removeCharactersInString:
+ _objc_msgSend$setHost:
+ _objc_msgSend$setScheme:
+ _objc_msgSend$shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:matchedEntry:language:
+ _objc_msgSend$stringByAddingPercentEncodingWithAllowedCharacters:
+ _objc_msgSend$stringByAppendingFormat:
+ _objc_msgSend$stringByTrimmingCharactersInSet:
+ _objc_msgSend$substringFromIndex:
+ _objc_msgSend$substringToIndex:
+ _objc_msgSend$whitespaceAndNewlineCharacterSet
- +[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:]
- +[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:language:]
- GCC_except_table61
- ___118+[WCRBrowserEngineClient shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:language:]_block_invoke
- ___119+[WCRBrowserEngineClient _blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:]_block_invoke
- ___block_descriptor_105_e8_32s40s48s56s64s72s80bs_e8_v16?0Q8l
- ___block_descriptor_41_e28_"NSString"16?0"NSString"8l
- _objc_msgSend$_blockPageForURL:inLanguage:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:
- _objc_msgSend$shieldStateForURL:shieldType:overridePolicy:iframe:ageVerificationText:isSensitive:language:
CStrings:
+ "&=+#'\"<>"
+ "&matchedEntry=%@"
+ ":"
+ "://"
+ "<>\"'&"
+ "?#"
+ "https"
+ "https://"
+ "matchedEntry"
+ "v24@?0Q8@\"NSString\"16"
- "v16@?0Q8"
```
