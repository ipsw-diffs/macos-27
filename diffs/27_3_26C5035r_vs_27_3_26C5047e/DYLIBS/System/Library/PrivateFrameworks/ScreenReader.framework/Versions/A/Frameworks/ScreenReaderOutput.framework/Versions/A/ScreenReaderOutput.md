## ScreenReaderOutput

> `/System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/Frameworks/ScreenReaderOutput.framework/Versions/A/ScreenReaderOutput`

```diff

-1050.3.12.0.0
-  __TEXT.__text: 0xaa088
-  __TEXT.__objc_methlist: 0x99e8
+1050.3.22.0.0
+  __TEXT.__text: 0xaa0b8
+  __TEXT.__objc_methlist: 0x9968
   __TEXT.__const: 0x1948
-  __TEXT.__cstring: 0x6784
+  __TEXT.__cstring: 0x677c
   __TEXT.__swift5_typeref: 0xeec
   __TEXT.__constg_swiftt: 0x960
   __TEXT.__swift5_builtin: 0xb4

   __TEXT.__swift_as_ret: 0x5c
   __TEXT.__swift_as_cont: 0x9c
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__gcc_except_tab: 0x1984
+  __TEXT.__gcc_except_tab: 0x19b8
   __TEXT.__ustring: 0x9e
-  __TEXT.__unwind_info: 0x3698
+  __TEXT.__unwind_info: 0x36a0
   __TEXT.__eh_frame: 0xa28
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4c60
+  __DATA_CONST.__objc_selrefs: 0x4c88
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x228
   __DATA_CONST.__objc_arraydata: 0x3f8
   __DATA_CONST.__got: 0x808
   __AUTH_CONST.__const: 0x4698
-  __AUTH_CONST.__cfstring: 0x67c0
-  __AUTH_CONST.__objc_const: 0xc860
+  __AUTH_CONST.__cfstring: 0x67a0
+  __AUTH_CONST.__objc_const: 0xc880
   __AUTH_CONST.__objc_intobj: 0x1218
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0x10

   __AUTH_CONST.__auth_got: 0xef8
   __AUTH.__objc_data: 0x540
   __AUTH.__data: 0x78
-  __DATA.__objc_ivar: 0x964
+  __DATA.__objc_ivar: 0x968
   __DATA.__data: 0x16a0
   __DATA.__bss: 0x1118
   __DATA.__common: 0x20

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4219
-  Symbols:   8171
-  CStrings:  1225
+  Functions: 4215
+  Symbols:   8172
+  CStrings:  1224
 
Symbols:
+ +[SCROBrailleClientXPC listenerEndpointForTesting]
+ +[SCROBrailleClientXPC setListenerEndpointForTesting:]
+ -[SCROBrailleDisplay _performWithContentLockIfValid:]
+ -[SCROBrailleDisplay shouldHandleCursorMovementForDispatcher:]
+ -[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:action:elementToken:appToken:]
+ -[SCROBrailleHandlerXPC initWithBrailleDisplayManager:listener:]
+ GCC_except_table1021
+ GCC_except_table1023
+ GCC_except_table1160
+ GCC_except_table1224
+ GCC_except_table1226
+ GCC_except_table1228
+ GCC_except_table123
+ GCC_except_table1230
+ GCC_except_table124
+ GCC_except_table127
+ GCC_except_table1301
+ GCC_except_table1331
+ GCC_except_table1338
+ GCC_except_table1342
+ GCC_except_table1345
+ GCC_except_table1347
+ GCC_except_table1377
+ GCC_except_table1384
+ GCC_except_table1516
+ GCC_except_table1725
+ GCC_except_table1852
+ GCC_except_table1989
+ GCC_except_table1991
+ GCC_except_table2000
+ GCC_except_table2012
+ GCC_except_table2098
+ GCC_except_table2143
+ GCC_except_table2149
+ GCC_except_table2263
+ GCC_except_table2284
+ GCC_except_table2293
+ GCC_except_table2301
+ GCC_except_table2404
+ GCC_except_table2587
+ GCC_except_table2608
+ GCC_except_table2718
+ GCC_except_table2719
+ GCC_except_table2720
+ GCC_except_table2729
+ GCC_except_table2730
+ GCC_except_table2731
+ GCC_except_table2732
+ GCC_except_table2746
+ GCC_except_table2748
+ GCC_except_table2751
+ GCC_except_table3127
+ GCC_except_table3145
+ GCC_except_table3164
+ GCC_except_table3165
+ GCC_except_table3166
+ GCC_except_table3232
+ GCC_except_table3234
+ GCC_except_table3237
+ GCC_except_table3239
+ GCC_except_table494
+ GCC_except_table511
+ GCC_except_table515
+ GCC_except_table571
+ GCC_except_table581
+ GCC_except_table583
+ GCC_except_table59
+ GCC_except_table606
+ GCC_except_table608
+ GCC_except_table612
+ GCC_except_table615
+ GCC_except_table625
+ GCC_except_table645
+ GCC_except_table648
+ GCC_except_table656
+ GCC_except_table658
+ GCC_except_table666
+ GCC_except_table683
+ GCC_except_table685
+ GCC_except_table690
+ GCC_except_table694
+ GCC_except_table698
+ GCC_except_table717
+ GCC_except_table720
+ GCC_except_table980
+ _OBJC_IVAR_$_SCROBrailleHandlerXPC._isMachServiceListener
+ __ListenerEndpointForTesting
+ __OBJC_$_CLASS_PROP_LIST_SCROBrailleClientXPC
+ ___100-[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:action:elementToken:appToken:]_block_invoke
+ ___100-[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:action:elementToken:appToken:]_block_invoke_2
+ ___47-[SCROBrailleDisplay _throttledFlushTimerFired]_block_invoke
+ ___48-[SCROBrailleDisplay _sendCellsToDriver:length:]_block_invoke
+ ___53-[SCROBrailleDisplay _updateWithWindow:isMainWindow:]_block_invoke
+ ___53-[SCROBrailleDisplay _updateWithWindow:isMainWindow:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48s_e41_v16?0"<SCROBrailleClientCallbacksXPC>"8l
+ ___block_descriptor_73_e8_32s40s48s56s_e5_v8?0l
+ ___block_descriptor_81_e8_32s40s48s56s64s_e5_v8?0l
+ _objc_msgSend$_dispatchPlanarPanPageForDisplay:isPageUp:action:elementToken:appToken:
+ _objc_msgSend$_performWithContentLockIfValid:
+ _objc_msgSend$brailleUIActive
+ _objc_msgSend$initWithListenerEndpoint:
+ _objc_msgSend$panPageRequest
+ _objc_msgSend$panPageRequestToken
+ _objc_msgSend$shouldHandleCursorMovementForDispatcher:
+ _objc_msgSend$takeReleasedPagePanIsBackward:
- -[SCROBrailleClient resetEditingManager]
- -[SCROBrailleClient selectAllForToken:]
- -[SCROBrailleClient setFocused:forToken:]
- -[SCROBrailleClient setSelection:forToken:]
- -[SCROBrailleClient unselectAllForToken:]
- -[SCROBrailleClientXPC selectAllForToken:]
- -[SCROBrailleClientXPC setFocused:forToken:]
- -[SCROBrailleClientXPC setSelection:forToken:]
- -[SCROBrailleClientXPC unselectAllForToken:]
- -[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:]
- -[SCROBrailleHandlerXPC selectAllForToken:]
- -[SCROBrailleHandlerXPC setFocused:forToken:]
- -[SCROBrailleHandlerXPC setSelection:forToken:]
- -[SCROBrailleHandlerXPC unselectAllForToken:]
- GCC_except_table1020
- GCC_except_table1022
- GCC_except_table1159
- GCC_except_table1223
- GCC_except_table1225
- GCC_except_table1227
- GCC_except_table1229
- GCC_except_table128
- GCC_except_table129
- GCC_except_table1300
- GCC_except_table132
- GCC_except_table1330
- GCC_except_table1337
- GCC_except_table1341
- GCC_except_table1344
- GCC_except_table1346
- GCC_except_table1376
- GCC_except_table1383
- GCC_except_table1515
- GCC_except_table1728
- GCC_except_table1854
- GCC_except_table1995
- GCC_except_table1997
- GCC_except_table2006
- GCC_except_table2018
- GCC_except_table2102
- GCC_except_table2147
- GCC_except_table2153
- GCC_except_table2267
- GCC_except_table2288
- GCC_except_table2297
- GCC_except_table2305
- GCC_except_table2408
- GCC_except_table2591
- GCC_except_table2612
- GCC_except_table2722
- GCC_except_table2723
- GCC_except_table2728
- GCC_except_table2734
- GCC_except_table2739
- GCC_except_table2740
- GCC_except_table2745
- GCC_except_table2750
- GCC_except_table2752
- GCC_except_table2755
- GCC_except_table3131
- GCC_except_table3149
- GCC_except_table3168
- GCC_except_table3169
- GCC_except_table3170
- GCC_except_table3238
- GCC_except_table3240
- GCC_except_table3243
- GCC_except_table3245
- GCC_except_table499
- GCC_except_table513
- GCC_except_table569
- GCC_except_table580
- GCC_except_table582
- GCC_except_table604
- GCC_except_table607
- GCC_except_table610
- GCC_except_table614
- GCC_except_table624
- GCC_except_table64
- GCC_except_table644
- GCC_except_table646
- GCC_except_table655
- GCC_except_table657
- GCC_except_table665
- GCC_except_table679
- GCC_except_table684
- GCC_except_table688
- GCC_except_table693
- GCC_except_table697
- GCC_except_table715
- GCC_except_table719
- GCC_except_table979
- ___101-[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:]_block_invoke
- ___101-[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:]_block_invoke_2
- ___block_descriptor_64_e8_32s40s48s56s_e41_v16?0"<SCROBrailleClientCallbacksXPC>"8l
- ___block_descriptor_73_e8_32s40s48s56s64s_e5_v8?0l
- ___block_descriptor_81_e8_32s40s48s56s64s72s_e5_v8?0l
- _objc_msgSend$_dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:
- _objc_msgSend$getRange:ofAttribute:withValue:
- _objc_msgSend$panFocusRequestToken
- _objc_msgSend$selectAllForToken:
- _objc_msgSend$setFocused:forToken:
- _objc_msgSend$setSelection:forToken:
- _objc_msgSend$unselectAllForToken:
CStrings:
+ "action"
- "focused"
- "selection"
```
