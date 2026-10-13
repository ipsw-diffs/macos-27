## AccessibilityVisuals

> `/System/Library/PrivateFrameworks/AccessibilitySupport.framework/Versions/A/Frameworks/AccessibilityVisuals.framework/Versions/A/AccessibilityVisuals`

```diff

-455.1.3.0.0
-  __TEXT.__text: 0x39438
-  __TEXT.__objc_methlist: 0x66f8
+455.1.5.0.0
+  __TEXT.__text: 0x3973c
+  __TEXT.__objc_methlist: 0x6738
   __TEXT.__const: 0x378
-  __TEXT.__cstring: 0xd05
-  __TEXT.__gcc_except_tab: 0x1d0
+  __TEXT.__cstring: 0xd03
+  __TEXT.__gcc_except_tab: 0x204
   __TEXT.__dlopen_cstrs: 0x5c
   __TEXT.__oslogstring: 0x403
   __TEXT.__ustring: 0x14
-  __TEXT.__unwind_info: 0x14c8
+  __TEXT.__unwind_info: 0x14e0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x148
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x44c8
+  __DATA_CONST.__objc_selrefs: 0x4500
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x228
   __DATA_CONST.__objc_arraydata: 0x30
-  __DATA_CONST.__got: 0x5c8
+  __DATA_CONST.__got: 0x5d0
   __AUTH_CONST.__const: 0x8b0
   __AUTH_CONST.__cfstring: 0x1480
-  __AUTH_CONST.__objc_const: 0xcd38
+  __AUTH_CONST.__objc_const: 0xcd88
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_doubleobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x510
+  __AUTH_CONST.__auth_got: 0x520
   __AUTH.__objc_data: 0x11d0
-  __DATA.__objc_ivar: 0x6ac
+  __DATA.__objc_ivar: 0x6b0
   __DATA.__data: 0xfb0
   __DATA.__bss: 0x168
   __DATA_DIRTY.__objc_data: 0x6e0

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1951
-  Symbols:   5219
-  CStrings:  207
+  Functions: 1959
+  Symbols:   5238
+  CStrings:  206
 
Symbols:
+ -[AXVCGFullscreenZoomController _invalidateZoomParametersSnapshot]
+ -[AXVCGFullscreenZoomController _isZoomParametersSnapshotAvailable]
+ -[AXVCGFullscreenZoomController _zoomParametersSnapshotValid]
+ -[AXVCGFullscreenZoomController _zoomParametersSnapshot]
+ -[AXVCGFullscreenZoomController set_zoomParametersSnapshot:]
+ -[AXVCGFullscreenZoomController set_zoomParametersSnapshotValid:]
+ -[AXVCGFullscreenZoomController withCoalescedZoomParameterReads:]
+ -[AXVCGFullscreenZoomController zoomDisplayID]
+ OBJC_IVAR_$_AXVCGFullscreenZoomController.__zoomParametersSnapshot
+ OBJC_IVAR_$_AXVCGFullscreenZoomController.__zoomParametersSnapshotValid
+ _OBJC_CLASS_$_NSThread
+ __72-[AXVFullscreenZoomController _applyZoomFactor:forScreen:displayUpdate:]_block_invoke
+ ___72-[AXVFullscreenZoomController _applyZoomFactor:forScreen:displayUpdate:]_block_invoke
+ _objc_exception_rethrow
+ _objc_msgSend$_invalidateZoomParametersSnapshot
+ _objc_msgSend$_isZoomParametersSnapshotAvailable
+ _objc_msgSend$_zoomParametersSnapshot
+ _objc_msgSend$_zoomParametersSnapshotValid
+ _objc_msgSend$isMainThread
+ _objc_msgSend$set_zoomParametersSnapshot:
+ _objc_msgSend$set_zoomParametersSnapshotValid:
+ _objc_msgSend$withCoalescedZoomParameterReads:
+ _objc_msgSend$zoomDisplayID
+ _objc_terminate
- -[AXVCGFullscreenZoomController _zoomDisplayID]
- -[AXVFullscreenZoomController setZoomFactor:]
- OBJC_IVAR_$_AXVFullscreenZoomController._zoomFactor
- _objc_msgSend$_zoomDisplayID
- _objc_msgSend$setZoomFactor:
CStrings:
- "D"
```
