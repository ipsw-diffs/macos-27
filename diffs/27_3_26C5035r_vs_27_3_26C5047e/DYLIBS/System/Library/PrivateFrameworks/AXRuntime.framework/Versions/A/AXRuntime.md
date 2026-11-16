## AXRuntime

> `/System/Library/PrivateFrameworks/AXRuntime.framework/Versions/A/AXRuntime`

```diff

-3245.8.14.0.0
-  __TEXT.__text: 0x45b78
-  __TEXT.__objc_methlist: 0x33e8
-  __TEXT.__const: 0x3f8
+3245.8.23.0.0
+  __TEXT.__text: 0x4610c
+  __TEXT.__objc_methlist: 0x3434
+  __TEXT.__const: 0x408
   __TEXT.__dlopen_cstrs: 0xbb
-  __TEXT.__gcc_except_tab: 0x7c0
-  __TEXT.__oslogstring: 0x1353
-  __TEXT.__cstring: 0x56de
+  __TEXT.__gcc_except_tab: 0x7dc
+  __TEXT.__oslogstring: 0x13bd
+  __TEXT.__cstring: 0x56dd
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x1540
+  __TEXT.__unwind_info: 0x1548
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x20a0
+  __DATA_CONST.__objc_selrefs: 0x20c0
   __DATA_CONST.__objc_superrefs: 0x98
   __DATA_CONST.__objc_arraydata: 0xb8
-  __DATA_CONST.__got: 0x2b8
-  __AUTH_CONST.__const: 0x1440
+  __DATA_CONST.__got: 0x2c0
+  __AUTH_CONST.__const: 0x1460
   __AUTH_CONST.__cfstring: 0x4f00
-  __AUTH_CONST.__objc_const: 0x3580
+  __AUTH_CONST.__objc_const: 0x3588
   __AUTH_CONST.__objc_intobj: 0x1590
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x960
+  __AUTH_CONST.__auth_got: 0x968
   __AUTH.__objc_data: 0x500
   __DATA.__objc_ivar: 0x208
-  __DATA.__data: 0x8d0
-  __DATA.__bss: 0x1a0
+  __DATA.__data: 0x890
+  __DATA.__bss: 0x1c0
   __DATA.__common: 0x2c
   __DATA_DIRTY.__objc_data: 0x2d0
-  __DATA_DIRTY.__data: 0x50
+  __DATA_DIRTY.__data: 0x90
   __DATA_DIRTY.__bss: 0x2b8
   __DATA_DIRTY.__common: 0xc
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libAccessibility.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1517
-  Symbols:   3623
-  CStrings:  872
+  Functions: 1524
+  Symbols:   3638
+  CStrings:  874
 
Symbols:
+ +[AXClientSideValueTransformer displayIdForSystemDisplayIdentifier:]
+ +[AXUIElement _uiElementAtCoordinate:forApplication:contextId:displayId:allowSameProcess:coordinateIsInHostedCoordinates:hitTestType:prefetchAttributes:]
+ +[AXUIElement uiElementAtCoordinate:displayId:allowSameProcess:prefetchAttributes:]
+ -[AXElement convertPath:frame:fromContextId:displayId:]
+ -[AXUIElement prefetchCachedAttributes]
+ GCC_except_table1037
+ GCC_except_table1039
+ GCC_except_table1193
+ GCC_except_table1198
+ GCC_except_table1230
+ GCC_except_table1249
+ GCC_except_table1268
+ GCC_except_table1347
+ GCC_except_table1375
+ GCC_except_table1422
+ GCC_except_table1488
+ GCC_except_table177
+ GCC_except_table180
+ GCC_except_table185
+ GCC_except_table187
+ GCC_except_table189
+ GCC_except_table191
+ GCC_except_table193
+ GCC_except_table195
+ GCC_except_table251
+ GCC_except_table270
+ GCC_except_table274
+ GCC_except_table278
+ GCC_except_table287
+ GCC_except_table359
+ GCC_except_table363
+ GCC_except_table365
+ GCC_except_table460
+ GCC_except_table466
+ GCC_except_table531
+ GCC_except_table675
+ GCC_except_table685
+ GCC_except_table773
+ GCC_except_table778
+ GCC_except_table782
+ GCC_except_table793
+ GCC_except_table794
+ GCC_except_table795
+ GCC_except_table853
+ _AXBoundingRectForPoints
+ _AXLogSubsystem
+ _AXRuntimeLogAttributeCacheTracing.log
+ _AXRuntimeLogAttributeCacheTracing.onceToken
+ ___55-[AXElement convertPath:frame:fromContextId:displayId:]_block_invoke
+ ___AXRuntimeLogAttributeCacheTracing_block_invoke
+ ___block_descriptor_40_e8_32bs_e32_B32?0"AXRemoteElement"8Q16^B24l
+ _displayIdForSystemDisplayIdentifier:.DisplayIDsBySystemDisplayIdentifier
+ _displayIdForSystemDisplayIdentifier:.DisplayIDsLock
+ _objc_msgSend$_uiElementAtCoordinate:forApplication:contextId:displayId:allowSameProcess:coordinateIsInHostedCoordinates:hitTestType:prefetchAttributes:
+ _objc_msgSend$convertPath:frame:fromContextId:displayId:
+ _objc_msgSend$uiElementAtCoordinate:displayId:allowSameProcess:prefetchAttributes:
+ _os_log_create
- GCC_except_table1032
- GCC_except_table1034
- GCC_except_table1187
- GCC_except_table1192
- GCC_except_table1224
- GCC_except_table1243
- GCC_except_table1262
- GCC_except_table1341
- GCC_except_table1369
- GCC_except_table1416
- GCC_except_table1481
- GCC_except_table176
- GCC_except_table179
- GCC_except_table184
- GCC_except_table186
- GCC_except_table188
- GCC_except_table190
- GCC_except_table192
- GCC_except_table194
- GCC_except_table249
- GCC_except_table268
- GCC_except_table273
- GCC_except_table277
- GCC_except_table286
- GCC_except_table358
- GCC_except_table362
- GCC_except_table364
- GCC_except_table459
- GCC_except_table465
- GCC_except_table530
- GCC_except_table674
- GCC_except_table684
- GCC_except_table771
- GCC_except_table775
- GCC_except_table779
- GCC_except_table789
- GCC_except_table790
- GCC_except_table791
- GCC_except_table848
- ___49-[AXElement convertPath:fromContextId:displayId:]_block_invoke
- ___block_descriptor_40_e8_32bs_e15_B32?08Q16^B24l
- _objc_msgSend$objectsAtIndexes:
Functions:
~ +[AXRemoteElement remoteElementsForBlock:] : 284 -> 228
+ _AXBoundingRectForPoints
~ +[AXUIElement applyElementAttributeCacheScheme:] : 1708 -> 1732
~ +[AXUIElement uiElementAtCoordinate:forApplication:contextId:displayId:allowSameProcess:coordinateIsInHostedCoordinates:hitTestType:] : 288 -> 40
+ +[AXUIElement _uiElementAtCoordinate:forApplication:contextId:displayId:allowSameProcess:coordinateIsInHostedCoordinates:hitTestType:prefetchAttributes:]
~ +[AXUIElement uiElementAtCoordinate:displayId:allowSameProcess:] : 212 -> 8
+ +[AXUIElement uiElementAtCoordinate:displayId:allowSameProcess:prefetchAttributes:]
~ -[AXUIElement _cachedValueForAttribute:] : 440 -> 452
+ -[AXUIElement prefetchCachedAttributes]
~ -[AXUIElement arrayWithAXAttribute:] : 588 -> 696
~ -[AXUIElement valueArrayWithAXAttributes:] : 604 -> 712
+ ___AXRuntimeLogAttributeCacheTracing_block_invoke
~ -[AXElement convertPath:fromContextId:displayId:] : 380 -> 16
+ -[AXElement convertPath:frame:fromContextId:displayId:]
~ -[AXElement simulateTapWithFingerIndex:withPoint:] : 532 -> 584
+ +[AXClientSideValueTransformer displayIdForSystemDisplayIdentifier:]
CStrings:
+ "DynamicTracing"
+ "System display identifier %{public}@ is display %u"
+ "Unable to resolve system display identifier %{public}@"
- "B32@?0@8Q16^B24"
```
