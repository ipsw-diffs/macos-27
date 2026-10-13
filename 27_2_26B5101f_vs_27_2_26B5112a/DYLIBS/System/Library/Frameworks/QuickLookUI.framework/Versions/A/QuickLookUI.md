## QuickLookUI

> `/System/Library/Frameworks/QuickLookUI.framework/Versions/A/QuickLookUI`

```diff

-1114.1.6.0.0
-  __TEXT.__text: 0xcd4ac
-  __TEXT.__objc_methlist: 0x110a0
+1114.1.10.0.0
+  __TEXT.__text: 0xcea18
+  __TEXT.__objc_methlist: 0x11240
   __TEXT.__gcc_except_tab: 0x10f4
-  __TEXT.__const: 0x1144
-  __TEXT.__cstring: 0x7b66
-  __TEXT.__oslogstring: 0x39f7
+  __TEXT.__const: 0x1164
+  __TEXT.__cstring: 0x7bb6
+  __TEXT.__oslogstring: 0x3cb1
   __TEXT.__ustring: 0x26
   __TEXT.__swift5_typeref: 0x470
   __TEXT.__swift5_reflstr: 0xe9

   __TEXT.__swift_as_cont: 0x18
   __TEXT.__swift5_capture: 0x20
   __TEXT.__dof_QLSeamles: 0x8e7
-  __TEXT.__unwind_info: 0x4e88
+  __TEXT.__unwind_info: 0x4f18
   __TEXT.__eh_frame: 0x2b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x620
-  __DATA_CONST.__objc_classlist: 0x698
+  __DATA_CONST.__objc_classlist: 0x6a0
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x210
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8868
+  __DATA_CONST.__objc_selrefs: 0x8940
   __DATA_CONST.__objc_protorefs: 0x70
   __DATA_CONST.__objc_superrefs: 0x4b0
   __DATA_CONST.__objc_arraydata: 0x38
-  __DATA_CONST.__got: 0x1138
-  __AUTH_CONST.__const: 0x22b0
-  __AUTH_CONST.__cfstring: 0x7ea0
-  __AUTH_CONST.__objc_const: 0x17ce8
+  __DATA_CONST.__got: 0x1148
+  __AUTH_CONST.__const: 0x2370
+  __AUTH_CONST.__cfstring: 0x7ec0
+  __AUTH_CONST.__objc_const: 0x17df0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x1550
-  __AUTH.__objc_data: 0x3ae0
+  __AUTH_CONST.__auth_got: 0x1558
+  __AUTH.__objc_data: 0x3b30
   __AUTH.__data: 0x128
   __DATA.__objc_ivar: 0x1060
   __DATA.__data: 0x1bd8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6105
-  Symbols:   13464
-  CStrings:  1567
+  Functions: 6144
+  Symbols:   13534
+  CStrings:  1580
 
Symbols:
+ +[NSScrollView(QLPanGestureUtilities) ql_scrollViewOwningScrollPanGestureRecognizer:]
+ -[NSScrollView(QLPanGestureUtilities) ql_canScrollContent]
+ -[QLDisplayBundle hideOverlayControls]
+ -[QLDisplayBundle showOverlayControlsMomentarily]
+ -[QLDisplayBundleViewController handlesOverlayControlsTaps]
+ -[QLDisplayBundleViewController hasRevealedOverlayControlAtPoint:]
+ -[QLDisplayBundleViewController hideOverlayControls]
+ -[QLDisplayBundleViewController overlayControlsTapAtPoint:]
+ -[QLDisplayBundleViewController revealsOverlayControlsWhenAttached]
+ -[QLDisplayBundleViewController setRevealsOverlayControlsWhenAttached:]
+ -[QLDisplayBundleViewController showOverlayControlsMomentarily]
+ -[QLFullscreenController _performTouchDownControlsToggle]
+ -[QLFullscreenController cancelPendingTouchDownControlsToggle]
+ -[QLFullscreenController setSwipeInProgress:]
+ -[QLFullscreenController swipeInProgress]
+ -[QLInlinePreviewController _remoteDisplayBundleOwnsOverlay]
+ -[QLOverlayBaseButtonLayer pressAtPoint:]
+ -[QLPreviewDragController startDraggingWithGestureRecognizer:isTouchEvent:beganOrFailedHandler:]
+ -[QLPreviewOverlayController controlsTemporarilyRevealed]
+ -[QLPreviewPanelController _isWindowResizeGestureRecognizer:]
+ -[QLPreviewPanelController setSidecarSwipeDidReceiveChange:]
+ -[QLPreviewPanelController setSwipeControllerIsSidecarDriven:]
+ -[QLPreviewPanelController sidecarSwipeDidReceiveChange]
+ -[QLPreviewPanelController swipeControllerIsSidecarDriven]
+ -[QLPreviewSwipeTransitionView hitTest:]
+ -[QLPreviewView receivedDragGesture:isTouchEvent:]
+ -[QLPreviewView receivedDragTouchGesture:]
+ -[QLPreviewView startDragFromGesture:isTouchEvent:beganOrFailedHandler:]
+ -[QLRemoteDisplayBundle hideOverlayControls]
+ -[QLRemoteDisplayBundle showOverlayControlsMomentarily]
+ -[QLUIServiceBaseViewController receivedDragGesture:isTouchEvent:]
+ -[QLUIServiceBaseViewController receivedDragTouchGesture:]
+ GCC_except_table107
+ GCC_except_table120
+ GCC_except_table123
+ GCC_except_table157
+ GCC_except_table233
+ GCC_except_table40
+ GCC_except_table8
+ OBJC_IVAR_$_QLDisplayBundleViewController._revealsOverlayControlsWhenAttached
+ OBJC_IVAR_$_QLFullscreenController._hudControlsPanel
+ OBJC_IVAR_$_QLFullscreenController._swipeInProgress
+ OBJC_IVAR_$_QLPreviewBubble._touchEventMonitor
+ OBJC_IVAR_$_QLPreviewPanelController._sidecarSwipeDidReceiveChange
+ OBJC_IVAR_$_QLPreviewPanelController._swipeControllerIsSidecarDriven
+ OBJC_IVAR_$_QLPreviewSwipeController._transitionView
+ _NSDraggingImageComponentIconKey
+ _NSStringFromPoint
+ _OBJC_CLASS_$_NSDraggingImageComponent
+ _OBJC_CLASS_$_QLPreviewSwipeTransitionView
+ _OBJC_METACLASS_$_QLPreviewSwipeTransitionView
+ __66-[QLPreviewBubble setAutomaticallyCloseWithMask:filterMask:block:]_block_invoke
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSScrollView_$_QLPanGestureUtilities
+ __OBJC_$_INSTANCE_METHODS_QLPreviewSwipeTransitionView
+ __OBJC_CLASS_RO_$_QLPreviewSwipeTransitionView
+ __OBJC_METACLASS_RO_$_QLPreviewSwipeTransitionView
+ ___50-[QLPreviewView receivedDragGesture:isTouchEvent:]_block_invoke
+ ___52-[QLPreviewSwipeController _swipeEndedAndCompleted:]_block_invoke
+ ___66-[QLUIServiceBaseViewController receivedDragGesture:isTouchEvent:]_block_invoke
+ ___72-[QLPreviewView startDragFromGesture:isTouchEvent:beganOrFailedHandler:]_block_invoke
+ ___83-[QLPreviewPanelController previewSwipeController:didEndWithDeltaIndex:isComplete:]_block_invoke
+ ___96-[QLPreviewDragController startDraggingWithGestureRecognizer:isTouchEvent:beganOrFailedHandler:]_block_invoke
+ ___96-[QLPreviewDragController startDraggingWithGestureRecognizer:isTouchEvent:beganOrFailedHandler:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e26_"NSEvent"16?0"NSEvent"8l
+ ___block_descriptor_40_e8_32bs_e29_B24?0"NSTouch"8"NSEvent"16l
+ ___block_descriptor_49_e8_32s40s_e28_v16?0"NSAnimationContext"8l
+ ___block_descriptor_73_e8_32s40s48s56s64bs_e51_v48?0"NSImage"8{CGRect={CGPoint=dd}{CGSize=dd}}16l
+ ___block_descriptor_73_e8_32s_e14_"NSArray"8?0l
+ _objc_msgSend$_isWindowResizeGestureRecognizer:
+ _objc_msgSend$_remoteDisplayBundleOwnsOverlay
+ _objc_msgSend$cancelPendingTouchDownControlsToggle
+ _objc_msgSend$controlsTemporarilyRevealed
+ _objc_msgSend$draggingImageComponentWithKey:
+ _objc_msgSend$hasRevealedOverlayControlAtPoint:
+ _objc_msgSend$hideOverlayControls
+ _objc_msgSend$pressAtPoint:
+ _objc_msgSend$ql_canScrollContent
+ _objc_msgSend$ql_scrollViewOwningScrollPanGestureRecognizer:
+ _objc_msgSend$receivedDragGesture:isTouchEvent:
+ _objc_msgSend$revealsOverlayControlsWhenAttached
+ _objc_msgSend$setDelaysPrimaryMouseButtonEvents:
+ _objc_msgSend$setDraggingFrame:
+ _objc_msgSend$setImageComponentsProvider:
+ _objc_msgSend$setOptions:
+ _objc_msgSend$setRevealsOverlayControlsWhenAttached:
+ _objc_msgSend$setSidecarSwipeDidReceiveChange:
+ _objc_msgSend$setSwipeControllerIsSidecarDriven:
+ _objc_msgSend$setSwipeInProgress:
+ _objc_msgSend$showOverlayControlsMomentarily
+ _objc_msgSend$sidecarSwipeDidReceiveChange
+ _objc_msgSend$startDragFromGesture:isTouchEvent:beganOrFailedHandler:
+ _objc_msgSend$startDraggingWithGestureRecognizer:isTouchEvent:beganOrFailedHandler:
+ _objc_msgSend$swipeControllerIsSidecarDriven
- -[QLPreviewDragController startDraggingWithGestureRecognizer:beganOrFailedHandler:]
- -[QLPreviewView startDragFromGesture:beganOrFailedHandler:]
- GCC_except_table105
- GCC_except_table118
- GCC_except_table121
- GCC_except_table155
- GCC_except_table231
- OBJC_IVAR_$_QLFullscreenController._controlsPanel
- OBJC_IVAR_$_QLPreviewPanelController._swipeContainerWindow
- OBJC_IVAR_$_QLPreviewSwipeController._cid
- OBJC_IVAR_$_QLPreviewSwipeController._fullscreenAndOnlyOneScreen
- OBJC_IVAR_$_QLPreviewSwipeController._previewFrame
- OBJC_IVAR_$_QLPreviewSwipeController._transitionWindow
- OBJC_IVAR_$_QLPreviewSwipeController._wid
- ___37-[QLPreviewView receivedDragGesture:]_block_invoke
- ___53-[QLUIServiceBaseViewController receivedDragGesture:]_block_invoke
- ___59-[QLPreviewView startDragFromGesture:beganOrFailedHandler:]_block_invoke
- ___83-[QLPreviewDragController startDraggingWithGestureRecognizer:beganOrFailedHandler:]_block_invoke
- ___block_descriptor_72_e8_32s40s48s56s64bs_e51_v48?0"NSImage"8{CGRect={CGPoint=dd}{CGSize=dd}}16l
- _objc_msgSend$setDraggingFrame:contents:
- _objc_msgSend$stage
- _objc_msgSend$startDragFromGesture:beganOrFailedHandler:
- _objc_msgSend$startDraggingWithGestureRecognizer:beganOrFailedHandler:
CStrings:
+ "@\"NSArray\"8@?0"
+ "HUD toggle (recognizer: %p): visible: %d, fading out: %d, hide timer armed: %d"
+ "HUD toggle ignored: duplicate tap report %.3fs after the last toggle (recognizer: %p)"
+ "HUD toggle: hiding controls"
+ "HUD toggle: showing controls and scheduling auto-hide"
+ "NSWindowResizePanGestureRecognizer"
+ "QLPreviewView.dragTouchGestureRecognizer"
+ "[touch-debug] %p hideOverlay remoteOwns=%d"
+ "[touch-debug] %p showOverlayMomentarily remoteOwns=%d"
+ "[touch-debug] DBVC hideOverlayControls"
+ "[touch-debug] DBVC overlayControlsTapAtPoint %{public}@ controller=%p revealed=%d pressed=%d page=%lu/%lu"
+ "[touch-debug] DBVC showOverlayControlsMomentarily controller=%p"
+ "[touch-debug] overlay %p goToNextPage page=%lu/%lu"
+ "[touch-debug] overlay %p hit %{public}@ at %{public}@ dequeue=%d overlayLayerFrame=%{public}@"
+ "\xd2"
- "QLPreviewView.dragTouch"
- "\xf0B"
```
