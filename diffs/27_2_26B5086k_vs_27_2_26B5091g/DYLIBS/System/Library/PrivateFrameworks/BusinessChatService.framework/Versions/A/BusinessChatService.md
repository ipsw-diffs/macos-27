## BusinessChatService

> `/System/Library/PrivateFrameworks/BusinessChatService.framework/Versions/A/BusinessChatService`

```diff

-30123.21.8.11.3
-  __TEXT.__text: 0x74cb0
-  __TEXT.__objc_methlist: 0x8df4
+30123.21.8.11.4
+  __TEXT.__text: 0x74dd8
+  __TEXT.__objc_methlist: 0x8e14
   __TEXT.__const: 0x298
-  __TEXT.__cstring: 0x867e
-  __TEXT.__oslogstring: 0x50a4
+  __TEXT.__cstring: 0x869c
+  __TEXT.__oslogstring: 0x50e2
   __TEXT.__gcc_except_tab: 0x6a8
-  __TEXT.__unwind_info: 0x1d90
+  __TEXT.__unwind_info: 0x1d98
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x2f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3270
+  __DATA_CONST.__objc_selrefs: 0x3288
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x390
   __DATA_CONST.__got: 0x498

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 2773
-  Symbols:   6576
-  CStrings:  1312
+  Functions: 2776
+  Symbols:   6581
+  CStrings:  1313
 
Symbols:
+ -[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:cacheOnly:completion:]
+ -[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]
+ -[BCSBusinessQueryService cachedBusinessItemWithPhoneNumber:completion:]
+ GCC_except_table114
+ GCC_except_table44
+ GCC_except_table64
+ GCC_except_table78
+ GCC_except_table84
+ GCC_except_table91
+ __70-[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]_block_invoke
+ ___102-[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:cacheOnly:completion:]_block_invoke
+ ___70-[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]_block_invoke
+ _objc_msgSend$fetchBusinessItemWithPhoneNumber:forClientBundleID:cacheOnly:completion:
+ _objc_msgSend$fetchItemWithQuery:cacheOnly:completion:
- GCC_except_table112
- GCC_except_table43
- GCC_except_table62
- GCC_except_table76
- GCC_except_table82
- GCC_except_table89
- __60-[BCSBusinessQueryController fetchItemWithQuery:completion:]_block_invoke
- ___60-[BCSBusinessQueryController fetchItemWithQuery:completion:]_block_invoke
- ___92-[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:completion:]_block_invoke
Functions:
+ -[BCSBusinessQueryService cachedBusinessItemWithPhoneNumber:completion:]
~ -[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:completion:] : 592 -> 12
+ -[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:cacheOnly:completion:]
~ -[BCSBusinessQueryController fetchItemWithQuery:completion:] : 736 -> 12
+ -[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]
CStrings:
+ "%s - Cache only lookup. Did not find item in cache - type: %@"
+ "-[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:cacheOnly:completion:]"
+ "-[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]"
+ "-[BCSBusinessQueryController fetchItemWithQuery:cacheOnly:completion:]_block_invoke"
- "-[BCSBusinessQueryController fetchBusinessItemWithPhoneNumber:forClientBundleID:completion:]"
- "-[BCSBusinessQueryController fetchItemWithQuery:completion:]"
- "-[BCSBusinessQueryController fetchItemWithQuery:completion:]_block_invoke"
```
