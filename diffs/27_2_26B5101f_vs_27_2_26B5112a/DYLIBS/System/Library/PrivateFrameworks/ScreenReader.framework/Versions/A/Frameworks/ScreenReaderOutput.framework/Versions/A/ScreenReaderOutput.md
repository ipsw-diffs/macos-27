## ScreenReaderOutput

> `/System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/Frameworks/ScreenReaderOutput.framework/Versions/A/ScreenReaderOutput`

```diff

-1050.3.3.0.0
-  __TEXT.__text: 0xa4f58
-  __TEXT.__objc_methlist: 0x9610
+1050.3.5.0.0
+  __TEXT.__text: 0xa5e2c
+  __TEXT.__objc_methlist: 0x96f8
   __TEXT.__const: 0x1938
   __TEXT.__cstring: 0x65f9
   __TEXT.__swift5_typeref: 0xeec

   __TEXT.__swift_as_ret: 0x5c
   __TEXT.__swift_as_cont: 0x9c
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__gcc_except_tab: 0x1964
+  __TEXT.__gcc_except_tab: 0x1984
   __TEXT.__ustring: 0x9e
-  __TEXT.__unwind_info: 0x3590
+  __TEXT.__unwind_info: 0x35d0
   __TEXT.__eh_frame: 0xa28
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4a38
+  __DATA_CONST.__objc_selrefs: 0x4a80
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x218
   __DATA_CONST.__objc_arraydata: 0x3f8
   __DATA_CONST.__got: 0x808
-  __AUTH_CONST.__const: 0x44f8
+  __AUTH_CONST.__const: 0x4588
   __AUTH_CONST.__cfstring: 0x6580
-  __AUTH_CONST.__objc_const: 0xc290
+  __AUTH_CONST.__objc_const: 0xc2c0
   __AUTH_CONST.__objc_intobj: 0x1218
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0x10

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4126
-  Symbols:   7997
+  Functions: 4143
+  Symbols:   8026
   CStrings:  1186
 
Symbols:
+ -[SCROBrailleClientXPC handleBrailleDidPlanarPanPageDown:elementToken:appToken:displayToken:]
+ -[SCROBrailleClientXPC handleBrailleDidPlanarPanPageUp:elementToken:appToken:displayToken:]
+ -[SCROBrailleDisplay _getStructuredStatusCellIndex:forRawRouterIndex:]
+ -[SCROBrailleDisplay _linePanWindow]
+ -[SCROBrailleDisplay _structuredBraillePanWindow:isBackward:]
+ -[SCROBrailleDisplay _structuredBraillePlanarPanIsPageUp:]
+ -[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:didPlanarPanPageDown:elementToken:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:didPlanarPanPageUp:elementToken:appToken:]
+ -[SCROBrailleHandler handleBrailleDidPlanarPanPageDown:elementToken:appToken:displayToken:]
+ -[SCROBrailleHandler handleBrailleDidPlanarPanPageUp:elementToken:appToken:displayToken:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPlanarPanPageDown:elementToken:appToken:displayToken:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPlanarPanPageUp:elementToken:appToken:displayToken:]
+ GCC_except_table1113
+ GCC_except_table1181
+ GCC_except_table1183
+ GCC_except_table1254
+ GCC_except_table1284
+ GCC_except_table1295
+ GCC_except_table1298
+ GCC_except_table1300
+ GCC_except_table1330
+ GCC_except_table1337
+ GCC_except_table1469
+ GCC_except_table1682
+ GCC_except_table1808
+ GCC_except_table1949
+ GCC_except_table1951
+ GCC_except_table1960
+ GCC_except_table1972
+ GCC_except_table2056
+ GCC_except_table2101
+ GCC_except_table2107
+ GCC_except_table2221
+ GCC_except_table2251
+ GCC_except_table2259
+ GCC_except_table2362
+ GCC_except_table2546
+ GCC_except_table2567
+ GCC_except_table2689
+ GCC_except_table2691
+ GCC_except_table2692
+ GCC_except_table2694
+ GCC_except_table2695
+ GCC_except_table2696
+ GCC_except_table2700
+ GCC_except_table2705
+ GCC_except_table2707
+ GCC_except_table2710
+ GCC_except_table3058
+ GCC_except_table3076
+ GCC_except_table3095
+ GCC_except_table3096
+ GCC_except_table3097
+ GCC_except_table3160
+ GCC_except_table3162
+ GCC_except_table3164
+ GCC_except_table3165
+ GCC_except_table3167
+ GCC_except_table3169
+ GCC_except_table448
+ GCC_except_table462
+ GCC_except_table494
+ GCC_except_table495
+ GCC_except_table518
+ GCC_except_table519
+ GCC_except_table529
+ GCC_except_table531
+ GCC_except_table553
+ GCC_except_table554
+ GCC_except_table560
+ GCC_except_table563
+ GCC_except_table573
+ GCC_except_table593
+ GCC_except_table595
+ GCC_except_table596
+ GCC_except_table604
+ GCC_except_table606
+ GCC_except_table614
+ GCC_except_table628
+ GCC_except_table630
+ GCC_except_table631
+ GCC_except_table637
+ GCC_except_table646
+ GCC_except_table665
+ GCC_except_table668
+ GCC_except_table932
+ GCC_except_table973
+ GCC_except_table975
+ ___101-[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:]_block_invoke
+ ___101-[SCROBrailleDisplayManager _dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:]_block_invoke_2
+ ___92-[SCROBrailleHandlerXPC handleBrailleDidPlanarPanPageUp:elementToken:appToken:displayToken:]_block_invoke
+ ___94-[SCROBrailleHandlerXPC handleBrailleDidPlanarPanPageDown:elementToken:appToken:displayToken:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56s_e41_v16?0"<SCROBrailleClientCallbacksXPC>"8l
+ ___block_descriptor_73_e8_32s40s48s56s64s_e5_v8?0l
+ ___block_descriptor_81_e8_32s40s48s56s64s72s_e5_v8?0l
+ _objc_msgSend$_dispatchPlanarPanPageForDisplay:isPageUp:success:elementToken:appToken:
+ _objc_msgSend$_getStructuredStatusCellIndex:forRawRouterIndex:
+ _objc_msgSend$_linePanWindow
+ _objc_msgSend$_structuredBraillePanWindow:isBackward:
+ _objc_msgSend$_structuredBraillePlanarPanIsPageUp:
+ _objc_msgSend$brailleDisplay:didPlanarPanPageDown:elementToken:appToken:
+ _objc_msgSend$brailleDisplay:didPlanarPanPageUp:elementToken:appToken:
+ _objc_msgSend$handleBrailleDidPlanarPanPageDown:elementToken:appToken:displayToken:
+ _objc_msgSend$handleBrailleDidPlanarPanPageUp:elementToken:appToken:displayToken:
- GCC_except_table1109
- GCC_except_table1173
- GCC_except_table1175
- GCC_except_table1245
- GCC_except_table1275
- GCC_except_table1282
- GCC_except_table1286
- GCC_except_table1289
- GCC_except_table1321
- GCC_except_table1328
- GCC_except_table1458
- GCC_except_table1667
- GCC_except_table1791
- GCC_except_table1932
- GCC_except_table1934
- GCC_except_table1943
- GCC_except_table1955
- GCC_except_table2039
- GCC_except_table2084
- GCC_except_table2090
- GCC_except_table2204
- GCC_except_table2225
- GCC_except_table2234
- GCC_except_table2345
- GCC_except_table2529
- GCC_except_table2550
- GCC_except_table2660
- GCC_except_table2661
- GCC_except_table2662
- GCC_except_table2666
- GCC_except_table2671
- GCC_except_table2672
- GCC_except_table2673
- GCC_except_table2674
- GCC_except_table2675
- GCC_except_table2693
- GCC_except_table3041
- GCC_except_table3059
- GCC_except_table3078
- GCC_except_table3079
- GCC_except_table3080
- GCC_except_table3143
- GCC_except_table3145
- GCC_except_table3147
- GCC_except_table3148
- GCC_except_table3150
- GCC_except_table3152
- GCC_except_table444
- GCC_except_table458
- GCC_except_table490
- GCC_except_table491
- GCC_except_table514
- GCC_except_table515
- GCC_except_table525
- GCC_except_table527
- GCC_except_table549
- GCC_except_table550
- GCC_except_table552
- GCC_except_table555
- GCC_except_table569
- GCC_except_table589
- GCC_except_table591
- GCC_except_table592
- GCC_except_table600
- GCC_except_table602
- GCC_except_table610
- GCC_except_table624
- GCC_except_table625
- GCC_except_table626
- GCC_except_table627
- GCC_except_table634
- GCC_except_table660
- GCC_except_table661
- GCC_except_table928
- GCC_except_table969
- GCC_except_table971
```
