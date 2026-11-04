## QuickLookUI

> `/System/Library/Frameworks/QuickLookUI.framework/Versions/A/QuickLookUI`

```diff

-1114.1.11.0.0
-  __TEXT.__text: 0xceaa4
-  __TEXT.__objc_methlist: 0x11250
+1114.3.2.0.0
+  __TEXT.__text: 0xcf1b4
+  __TEXT.__objc_methlist: 0x112c0
   __TEXT.__gcc_except_tab: 0x10f4
-  __TEXT.__const: 0x1164
-  __TEXT.__cstring: 0x7bb6
+  __TEXT.__const: 0x1184
+  __TEXT.__cstring: 0x7bd6
   __TEXT.__oslogstring: 0x3cb1
   __TEXT.__ustring: 0x26
   __TEXT.__swift5_typeref: 0x470

   __TEXT.__swift_as_cont: 0x18
   __TEXT.__swift5_capture: 0x20
   __TEXT.__dof_QLSeamles: 0x8e7
-  __TEXT.__unwind_info: 0x4f18
+  __TEXT.__unwind_info: 0x4f38
   __TEXT.__eh_frame: 0x2b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x210
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8948
+  __DATA_CONST.__objc_selrefs: 0x89b0
   __DATA_CONST.__objc_protorefs: 0x70
-  __DATA_CONST.__objc_superrefs: 0x4b0
+  __DATA_CONST.__objc_superrefs: 0x4a8
   __DATA_CONST.__objc_arraydata: 0x38
-  __DATA_CONST.__got: 0x1148
-  __AUTH_CONST.__const: 0x2370
-  __AUTH_CONST.__cfstring: 0x7ec0
-  __AUTH_CONST.__objc_const: 0x17df0
+  __DATA_CONST.__got: 0x1150
+  __AUTH_CONST.__const: 0x23a0
+  __AUTH_CONST.__cfstring: 0x7ee0
+  __AUTH_CONST.__objc_const: 0x17ed0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x1558
+  __AUTH_CONST.__auth_got: 0x1568
   __AUTH.__objc_data: 0x3b30
   __AUTH.__data: 0x128
-  __DATA.__objc_ivar: 0x1060
+  __DATA.__objc_ivar: 0x1074
   __DATA.__data: 0x1bd8
   __DATA.__bss: 0x17b0
   __DATA.__common: 0x28

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6145
-  Symbols:   13457
-  CStrings:  1580
+  Functions: 6153
+  Symbols:   13478
+  CStrings:  1581
 
Symbols:
+ -[QLDisplayBundle needsPlayControl]
+ -[QLIndexSheetView _handleSidecarPan:]
+ -[QLIndexSheetView _scrollByPreciseDeltaY:]
+ -[QLIndexSheetView _setupSidecarGestureRecognizers]
+ -[QLIndexSheetView _sidecarDecelerationStep:]
+ -[QLIndexSheetView _startSidecarDecelerationWithVelocity:]
+ -[QLIndexSheetView _stopSidecarDeceleration]
+ -[QLPreviewSwipeController _freezeIncomingItem]
+ -[QLPreviewSwipeController _removeTransitionViewWhenPreviewViewShowsIncomingItem:]
+ -[QLPreviewSwipeController _removeTransitionView]
+ -[QLPreviewSwipeController previewViewDidShowDisplayable:]
+ -[QLPreviewTitleBarView gesturesForFailureRequirements]
+ -[QLPreviewTitleBarView hitTestForContext:]
+ -[QLPreviewTitleBarView setStoplightInteraction:]
+ -[QLPreviewTitleBarView stoplightInteraction]
+ -[QLRemoteDisplayBundle needsPlayControl]
+ -[QLRemoteDisplayBundle setNeedsPlayControl:]
+ GCC_except_table102
+ GCC_except_table121
+ GCC_except_table158
+ GCC_except_table231
+ _CACurrentMediaTime
+ _OBJC_CLASS_$_NSStoplightZoomInteraction
+ _OBJC_IVAR_$_QLIndexSheetView._sidecarDecelerationDisplayLink
+ _OBJC_IVAR_$_QLIndexSheetView._sidecarDecelerationStartTime
+ _OBJC_IVAR_$_QLIndexSheetView._sidecarDecelerationStartValue
+ _OBJC_IVAR_$_QLIndexSheetView._sidecarDecelerationTargetValue
+ _OBJC_IVAR_$_QLPreviewPanelController._endedSwipeController
+ _OBJC_IVAR_$_QLPreviewSwipeController._waitingForIncomingItem
+ _OBJC_IVAR_$_QLPreviewTitleBarView._stoplightInteraction
+ _OBJC_IVAR_$_QLRemoteDisplayBundle._needsPlayControl
+ ___49-[QLPreviewSwipeController _removeTransitionView]_block_invoke
+ ___block_descriptor_40_e8_32s_e28_v16?0"NSAnimationContext"8l
+ _objc_msgSend$_addInteraction:
+ _objc_msgSend$_freezeIncomingItem
+ _objc_msgSend$_isStoplightButtonHit:
+ _objc_msgSend$_removeTransitionView
+ _objc_msgSend$_removeTransitionViewWhenPreviewViewShowsIncomingItem:
+ _objc_msgSend$_scrollByPreciseDeltaY:
+ _objc_msgSend$_setupSidecarGestureRecognizers
+ _objc_msgSend$_startSidecarDecelerationWithVelocity:
+ _objc_msgSend$_stopSidecarDeceleration
+ _objc_msgSend$gesturesForFailureRequirements
+ _objc_msgSend$highlightedTimeRanges
+ _objc_msgSend$previewItemSizeHint
+ _objc_msgSend$previewViewDidShowDisplayable:
+ _objc_msgSend$setHighlightedTimeRanges:
+ _objc_msgSend$setTranslation:inView:
+ _objc_msgSend$stoplightInteraction
+ _objc_msgSend$targetTimestamp
- -[QLIndexSheetView _setupSidecarTapGestureRecognizer]
- -[QLPreviewView inHitTest]
- -[QLPreviewView setInHitTest:]
- -[QLUIServiceBaseViewController updateViewInteraction]
- -[QLUIServiceView _commonHitTestView:isDirectTouch:]
- -[QLUIServiceView allowMouseInteractions]
- -[QLUIServiceView hitTest:]
- -[QLUIServiceView hitTestForContext:]
- -[QLUIServiceView inHitTest]
- -[QLUIServiceView setAllowMouseInteractions:]
- -[QLUIServiceView setInHitTest:]
- GCC_except_table123
- GCC_except_table157
- GCC_except_table233
- GCC_except_table98
- _OBJC_IVAR_$_QLPreviewViewReserved.inHitTest
- _OBJC_IVAR_$_QLUIServiceView._allowMouseInteractions
- _OBJC_IVAR_$_QLUIServiceView._inHitTest
- __OBJC_$_INSTANCE_VARIABLES_QLUIServiceView
- __OBJC_$_PROP_LIST_QLUIServiceView
- _objc_msgSend$_commonHitTestView:isDirectTouch:
- _objc_msgSend$_setupSidecarTapGestureRecognizer
- _objc_msgSend$acceptsFirstMouse:
- _objc_msgSend$allowMouseInteractions
- _objc_msgSend$inHitTest
- _objc_msgSend$setAllowMouseInteractions:
- _objc_msgSend$setInHitTest:
- _objc_msgSend$showCompactPlayControl
- _objc_msgSend$updateViewInteraction
CStrings:
+ "*\x92"
+ "QLIndexSheetView.sidecarSwipeGestureRecognizer"
+ "\xe2"
- "*\x91"
- "\xd2"
```
