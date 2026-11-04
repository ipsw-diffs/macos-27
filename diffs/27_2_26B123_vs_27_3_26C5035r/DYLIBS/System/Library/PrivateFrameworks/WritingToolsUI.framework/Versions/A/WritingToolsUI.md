## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/Versions/A/WritingToolsUI`

```diff

-151.1.11.500.0
-  __TEXT.__text: 0x5a0e8
-  __TEXT.__objc_methlist: 0x3544
-  __TEXT.__const: 0x2cd4
-  __TEXT.__cstring: 0x2bb2
-  __TEXT.__gcc_except_tab: 0x8d0
+151.2.5.0.0
+  __TEXT.__text: 0x5ab64
+  __TEXT.__objc_methlist: 0x3624
+  __TEXT.__const: 0x2cc4
+  __TEXT.__cstring: 0x2be2
+  __TEXT.__gcc_except_tab: 0x8f0
   __TEXT.__oslogstring: 0x1345
   __TEXT.__dlopen_cstrs: 0xb4
-  __TEXT.__swift5_typeref: 0x926e
+  __TEXT.__swift5_typeref: 0x9260
   __TEXT.__swift5_reflstr: 0x9cc
   __TEXT.__swift5_assocty: 0x1e8
   __TEXT.__constg_swiftt: 0xae0
   __TEXT.__swift5_fieldmd: 0x870
   __TEXT.__swift5_builtin: 0xa0
-  __TEXT.__swift5_capture: 0x374
+  __TEXT.__swift5_capture: 0x364
   __TEXT.__swift5_proto: 0x170
   __TEXT.__swift5_types: 0x98
   __TEXT.__swift_as_entry: 0x48
   __TEXT.__swift_as_cont: 0x40
   __TEXT.__swift_as_ret: 0x24
-  __TEXT.__unwind_info: 0x1e08
+  __TEXT.__unwind_info: 0x1e48
   __TEXT.__eh_frame: 0xac0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x29e8
+  __DATA_CONST.__objc_selrefs: 0x2a98
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0xb0
   __DATA_CONST.__objc_arraydata: 0x88
   __DATA_CONST.__got: 0x9a0
-  __AUTH_CONST.__const: 0x2980
+  __AUTH_CONST.__const: 0x2a18
   __AUTH_CONST.__cfstring: 0x1020
-  __AUTH_CONST.__objc_const: 0x4ef8
+  __AUTH_CONST.__objc_const: 0x5048
   __AUTH_CONST.__objc_doubleobj: 0x80
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_arrayobj: 0x78
-  __AUTH_CONST.__auth_got: 0xe70
+  __AUTH_CONST.__auth_got: 0xe78
   __AUTH.__objc_data: 0xd90
   __AUTH.__data: 0x808
-  __DATA.__objc_ivar: 0x2f8
-  __DATA.__data: 0x1618
+  __DATA.__objc_ivar: 0x314
+  __DATA.__data: 0x1608
   __DATA.__bss: 0x30f0
   __DATA.__common: 0x38
   __DATA_DIRTY.__objc_data: 0x140

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2207
-  Symbols:   3811
-  CStrings:  418
+  Functions: 2230
+  Symbols:   3868
+  CStrings:  420
 
Symbols:
+ +[WTAffordanceUIController rect:driftedFromRect:]
+ +[WTAffordanceUIController selectionRect:shiftedFromPlacedRect:toSettledRect:]
+ -[WTAffordanceUIController beginValidatingPlacementForView:selectedRange:shownFirstRect:]
+ -[WTAffordanceUIController pinnedSelectionRect]
+ -[WTAffordanceUIController pinnedVisible]
+ -[WTAffordanceUIController placementValidationGeneration]
+ -[WTAffordanceUIController reshowAfterScrollForView:placedFirstRect:settledFirstRect:]
+ -[WTAffordanceUIController scheduledCallback]
+ -[WTAffordanceUIController scheduledDelegate]
+ -[WTAffordanceUIController setPinnedSelectionRect:]
+ -[WTAffordanceUIController setPinnedVisible:]
+ -[WTAffordanceUIController setPlacementValidationGeneration:]
+ -[WTAffordanceUIController setScheduledCallback:]
+ -[WTAffordanceUIController setScheduledDelegate:]
+ -[WTAffordanceUIController setWasVisibleBeforeScrollHide:]
+ -[WTAffordanceUIController validatePlacementForView:selectedRange:placedFirstRect:lastPolledRect:hidden:generation:remaining:]
+ -[WTAffordanceUIController wasVisibleBeforeScrollHide]
+ -[WTWritingToolsViewController setTouchEventMonitor:]
+ -[WTWritingToolsViewController touchEventMonitor]
+ GCC_except_table180
+ GCC_except_table196
+ GCC_except_table224
+ GCC_except_table62
+ _OBJC_IVAR_$_WTAffordanceUIController._pinnedSelectionRect
+ _OBJC_IVAR_$_WTAffordanceUIController._pinnedVisible
+ _OBJC_IVAR_$_WTAffordanceUIController._placementValidationGeneration
+ _OBJC_IVAR_$_WTAffordanceUIController._scheduledCallback
+ _OBJC_IVAR_$_WTAffordanceUIController._scheduledDelegate
+ _OBJC_IVAR_$_WTAffordanceUIController._wasVisibleBeforeScrollHide
+ _OBJC_IVAR_$_WTWritingToolsViewController._touchEventMonitor
+ ___126-[WTAffordanceUIController validatePlacementForView:selectedRange:placedFirstRect:lastPolledRect:hidden:generation:remaining:]_block_invoke
+ ___126-[WTAffordanceUIController validatePlacementForView:selectedRange:placedFirstRect:lastPolledRect:hidden:generation:remaining:]_block_invoke_2
+ ___block_descriptor_104_e8_32s40s48s56bs64bs_e46_v36?0"NSAttributedString"8{_NSRange=QQ}16B32l
+ ___block_descriptor_145_e8_32s40w_e39_v40?0{CGRect={CGPoint=dd}{CGSize=dd}}8l
+ ___block_descriptor_145_e8_32w40w_e5_v8?0l
+ ___block_descriptor_40_e8_32bs_e26_"NSEvent"16?0"NSEvent"8l
+ ___block_descriptor_40_e8_32bs_e29_B24?0"NSTouch"8"NSEvent"16l
+ ___block_descriptor_48_e8_32s40w_e17_v16?0"NSEvent"8l
+ ___block_descriptor_96_e8_32s40s_e8_v16?0d8l
+ ___copy_helper_block_e8_32s40s48s56b64b
+ ___copy_helper_block_e8_32w40w
+ ___destroy_helper_block_e8_32s40s48s56s64s
+ ___destroy_helper_block_e8_32w40w
+ _objc_msgSend$addLocalMonitorForTouchBegan:
+ _objc_msgSend$beginValidatingPlacementForView:selectedRange:shownFirstRect:
+ _objc_msgSend$level
+ _objc_msgSend$orderedWindows
+ _objc_msgSend$pinnedSelectionRect
+ _objc_msgSend$pinnedVisible
+ _objc_msgSend$placementValidationGeneration
+ _objc_msgSend$rect:driftedFromRect:
+ _objc_msgSend$reshowAfterScrollForView:placedFirstRect:settledFirstRect:
+ _objc_msgSend$scheduledCallback
+ _objc_msgSend$scheduledDelegate
+ _objc_msgSend$selectionRect:shiftedFromPlacedRect:toSettledRect:
+ _objc_msgSend$setPinnedSelectionRect:
+ _objc_msgSend$setPinnedVisible:
+ _objc_msgSend$setPlacementValidationGeneration:
+ _objc_msgSend$setScheduledCallback:
+ _objc_msgSend$setScheduledDelegate:
+ _objc_msgSend$setTouchEventMonitor:
+ _objc_msgSend$setWasVisibleBeforeScrollHide:
+ _objc_msgSend$show
+ _objc_msgSend$validatePlacementForView:selectedRange:placedFirstRect:lastPolledRect:hidden:generation:remaining:
+ _objc_msgSend$wasVisibleBeforeScrollHide
- GCC_except_table179
- GCC_except_table193
- GCC_except_table221
- GCC_except_table47
- ___block_descriptor_48_e8_32s40w_e26_"NSEvent"16?0"NSEvent"8l
- ___block_descriptor_72_e8_32s_e8_v16?0d8l
- ___block_descriptor_96_e8_32s40s48bs56bs_e46_v36?0"NSAttributedString"8{_NSRange=QQ}16B32l
- _symbolic _____y_____G 7SwiftUI6ButtonV AA5ImageV
CStrings:
+ "#!"
+ "1\x91"
+ "B24@?0@\"NSTouch\"8@\"NSEvent\"16"
+ "v16@?0@\"NSEvent\"8"
- "#"
- "1\x81"
```
