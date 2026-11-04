## ConsoleKit

> `/System/Library/PrivateFrameworks/ConsoleKit.framework/Versions/A/ConsoleKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-22.0.0.0.0
-  __TEXT.__text: 0x60ff8
-  __TEXT.__objc_methlist: 0x79cc
+24.0.0.0.0
+  __TEXT.__text: 0x61558
+  __TEXT.__objc_methlist: 0x7a04
   __TEXT.__const: 0x2a4
   __TEXT.__gcc_except_tab: 0x1018
   __TEXT.__cstring: 0x3ef7

   __TEXT.__swift5_typeref: 0x1a
   __TEXT.__swift5_fieldmd: 0x20
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x2220
+  __TEXT.__unwind_info: 0x2238
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x130
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4950
+  __DATA_CONST.__objc_selrefs: 0x49a0
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x2a8
+  __DATA_CONST.__objc_superrefs: 0x2b0
   __DATA_CONST.__objc_arraydata: 0x1e8
-  __DATA_CONST.__got: 0x660
+  __DATA_CONST.__got: 0x678
   __AUTH_CONST.__const: 0x1dd0
   __AUTH_CONST.__cfstring: 0x3e40
-  __AUTH_CONST.__objc_const: 0x113f8
+  __AUTH_CONST.__objc_const: 0x11418
   __AUTH_CONST.__objc_intobj: 0x5b8
   __AUTH_CONST.__objc_arrayobj: 0x150
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x5b8
   __AUTH.__objc_data: 0x1ff0
   __AUTH.__data: 0xc0
-  __DATA.__objc_ivar: 0x92c
+  __DATA.__objc_ivar: 0x930
   __DATA.__data: 0xe40
   __DATA.__bss: 0x3b0
   __DATA.__common: 0x138

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2790
-  Symbols:   6631
-  CStrings:  787
+  Functions: 2795
+  Symbols:   6649
+  CStrings:  788
 
Symbols:
+ -[CSKMenu copyWithZone:]
+ -[CSKTokenAttachmentCell _gestureShowsMenu:inRect:ofView:atCharacterIndex:]
+ -[CSKTokenAttachmentCell _isTouchGesture:]
+ -[CSKTokenAttachmentCell _overridesRequireMouseDownFallback]
+ -[CSKTokenAttachmentCell _popUpMenuInControlView:cellFrame:]
+ -[CSKTokenAttachmentCell _trackGesture:inRect:ofView:atCharacterIndex:]
+ -[CSKTokenAttachmentCell pullDownTrackingRectForBounds:]
+ _OBJC_CLASS_$_NSClickGestureRecognizer
+ _OBJC_CLASS_$_NSEvent
+ _OBJC_CLASS_$_NSPressGestureRecognizer
+ _OBJC_IVAR_$_CSKTokenAttachmentCell._gestureTracking
+ _objc_msgSend$_gestureShowsMenu:inRect:ofView:atCharacterIndex:
+ _objc_msgSend$_isTouchGesture:
+ _objc_msgSend$_popUpMenuInControlView:cellFrame:
+ _objc_msgSend$_touchDevice
+ _objc_msgSend$locationInView:
+ _objc_msgSend$modifierFlags
+ _objc_msgSend$numberOfClicksRequired
+ _objc_msgSend$pullDownTrackingRectForBounds:
+ _objc_msgSend$selectedRange
+ _objc_msgSend$touches
- -[CSKTokenAttachmentCell _hasMenu]
- -[CSKTokenAttachmentCell _popUpMenuInControlView:fromKeyContainerRect:]
- _objc_msgSend$_popUpMenuInControlView:fromKeyContainerRect:
CStrings:
+ "$"
```
