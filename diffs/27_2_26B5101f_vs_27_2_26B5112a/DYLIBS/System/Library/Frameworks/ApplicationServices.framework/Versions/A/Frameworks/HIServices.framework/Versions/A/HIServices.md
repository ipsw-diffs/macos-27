## HIServices

> `/System/Library/Frameworks/ApplicationServices.framework/Versions/A/Frameworks/HIServices.framework/Versions/A/HIServices`

```diff

-835.3.0.0.0
-  __TEXT.__text: 0x5a0b8
+835.5.0.0.0
+  __TEXT.__text: 0x5a5f4
   __TEXT.__objc_methlist: 0x10c
   __TEXT.__const: 0x1620
-  __TEXT.__cstring: 0x5e96
-  __TEXT.__oslogstring: 0x2458
+  __TEXT.__cstring: 0x61e4
+  __TEXT.__oslogstring: 0x245f
   __TEXT.__dlopen_cstrs: 0xfc
   __TEXT.__ustring: 0xd2
   __TEXT.__gcc_except_tab: 0x344
   __TEXT.__dof_Accessibi: 0x90c
-  __TEXT.__unwind_info: 0x1ce0
+  __TEXT.__unwind_info: 0x1cf0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1280
+  __DATA_CONST.__const: 0x1480
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x220
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__got: 0x4f0
   __AUTH_CONST.__const: 0x1898
-  __AUTH_CONST.__cfstring: 0x5e40
+  __AUTH_CONST.__cfstring: 0x5e80
   __AUTH_CONST.__objc_const: 0x230
   __AUTH_CONST.__weak_auth_got: 0x20
-  __AUTH_CONST.__auth_got: 0x1968
+  __AUTH_CONST.__auth_got: 0x1970
   __AUTH.__data: 0x138
+  __AUTH.__thread_vars: 0x18
+  __AUTH.__thread_bss: 0x400
   __DATA.__objc_ivar: 0x1c
   __DATA.__data: 0x420
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x990
+  __DATA.__bss: 0x9b0
   __DATA.__common: 0x44
   __DATA_DIRTY.__objc_data: 0xa0
   __DATA_DIRTY.__data: 0x114

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1899
-  Symbols:   3279
-  CStrings:  1254
+  Functions: 1904
+  Symbols:   3295
+  CStrings:  1291
 
Symbols:
+ CoreDragBeginSlideBackAnimationAsync.sCheckedForAsyncProc
+ CoreDragBeginSlideBackAnimationAsync.sCoreDragBeginSlideBackAnimationAsyncProc
+ StringFromDragInfo.dragFlagNames
+ StringFromDragInfo.flagsString
+ StringFromDragInfo.flagsString$tlv$init
+ StringFromDragState.dragStateNames
+ _CallTrackingEndedProc
+ _CoreDragBeginSlideBackAnimationAsync
+ _CoreDragSetTrackingEndedProc
+ _EndDraggingZoomBackDidComplete
+ _FinishEndDragging
+ _ZoomBackAnimationDidComplete
+ __tlv_bootstrap
+ _gTrackingEndedProcUserData
+ _gTrackingEndedProcs
+ _hypot
CStrings:
+ "%llx Dropped on connection %u: %s"
+ "%llx End drag loop. %s - %s"
+ "0x%x"
+ "CDDragSignificantMovement"
+ "CDEnableAsynchronousSlideBackAnimation"
+ "Ended"
+ "Tracking"
+ "WaitingForDropCompleted"
+ "WaitingForZoomBack"
+ "__CoreDragBeginSlideBackAnimationAsync"
+ "kDragAcceptEvent"
+ "kDragCachedCursorInBackgroundValue"
+ "kDragCancelEvent"
+ "kDragChangedTarget"
+ "kDragDestinationClearDragImages"
+ "kDragDestinationHasDragImageUpdatesForIPC"
+ "kDragDestinationShouldSendImageUpdates"
+ "kDragDidSendPing"
+ "kDragDropIsAsync"
+ "kDragEndEvent"
+ "kDragFirstSample"
+ "kDragHasEnabledBackgroundCursor"
+ "kDragInProgress"
+ "kDragIsDirectTouch"
+ "kDragRgnAndImage"
+ "kDragScreenUpdatesDisabled"
+ "kDragShowWindowOnFirstSample"
+ "kDragSourceHasDragImageUpdatesForIPC"
+ "kDragStoleKeyFocus"
+ "kDragSuccess"
+ "kDragTracking"
+ "kDragTrashIconReset"
+ "kDragTrashLabelReset"
+ "kDragTrashLabelSet"
+ "kDragUpdateClippingArea"
+ "kDragUpdateFormation"
+ "kDragUpdateLayerPositions"
+ "kDragUpdateWindowContent"
+ "kDragZoomBackInProgress"
+ "kMouseButtonIsDown"
+ "|"
- "%llx Dropped on connection %u, %s."
- "%llx End drag loop."
- "async"
- "sync"
```
