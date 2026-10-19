## UIKitMacHelper

> `/System/Library/PrivateFrameworks/UIKitMacHelper.framework/Versions/A/UIKitMacHelper`

```diff

-9127.1.13.1.408
-  __TEXT.__text: 0xb72d8
-  __TEXT.__objc_methlist: 0xe808
+9127.1.13.1.411
+  __TEXT.__text: 0xb74dc
+  __TEXT.__objc_methlist: 0xe800
   __TEXT.__const: 0x7d8
   __TEXT.__dlopen_cstrs: 0x737
-  __TEXT.__cstring: 0xd98f
+  __TEXT.__cstring: 0xd9b6
   __TEXT.__constg_swiftt: 0x50
   __TEXT.__swift5_typeref: 0x6
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
-  __TEXT.__oslogstring: 0x5cce
-  __TEXT.__gcc_except_tab: 0x17e4
+  __TEXT.__oslogstring: 0x5d12
+  __TEXT.__gcc_except_tab: 0x1804
   __TEXT.__ustring: 0x52
-  __TEXT.__unwind_info: 0x3c80
+  __TEXT.__unwind_info: 0x3c88
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_nlcatlist: 0x10
   __DATA_CONST.__objc_protolist: 0x2b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8748
+  __DATA_CONST.__objc_selrefs: 0x8740
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x458
   __DATA_CONST.__objc_arraydata: 0x158
   __DATA_CONST.__got: 0xc48
   __AUTH_CONST.__const: 0x2e80
-  __AUTH_CONST.__cfstring: 0x8cc0
-  __AUTH_CONST.__objc_const: 0x179e0
+  __AUTH_CONST.__cfstring: 0x8ce0
+  __AUTH_CONST.__objc_const: 0x17a20
   __AUTH_CONST.__objc_dictobj: 0x140
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_doubleobj: 0x10

   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x29e0
   __AUTH.__data: 0xa0
-  __DATA.__objc_ivar: 0xbc8
+  __DATA.__objc_ivar: 0xbd0
   __DATA.__data: 0x20e8
   __DATA.__bss: 0x1c8
   __DATA.__common: 0x48

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 4704
-  Symbols:   11850
-  CStrings:  1994
+  Symbols:   11853
+  CStrings:  1996
 
Symbols:
+ -[UINSDragManager dragContextMenuController:willDismissContextMenuToYield:]
+ -[UINSDragManager dragContextMenuControllerWillCancelDragToTrackContextMenu:]
+ OBJC_IVAR_$_UINSDragManager._commandeeredTouchesDidEnd
+ OBJC_IVAR_$_UINSDragManager._didEndCommandeeringTouchNotificationObserver
+ ___96-[UINSDragManager _beginDragInSceneView:withItems:event:orTouchIndex:andContextID:menu:handler:]_block_invoke
+ _objc_msgSend$draggingSession:endedAtPoint:operation:
- -[UINSDragManager dragContextMenuController:didDismissContextMenuAutoDismissed:]
- -[UINSDragManager dragContextMenuControllerShouldReplayTouchesAfterMenuDismissalForDragAndDrop:]
- -[UINSDragManager dragContextMenuControllerWillDisplayContextMenu:]
CStrings:
+ "NSDidEndCommandeeringTouchNotification"
+ "Not resuming session because touches have ended. Ending it instead."
```
