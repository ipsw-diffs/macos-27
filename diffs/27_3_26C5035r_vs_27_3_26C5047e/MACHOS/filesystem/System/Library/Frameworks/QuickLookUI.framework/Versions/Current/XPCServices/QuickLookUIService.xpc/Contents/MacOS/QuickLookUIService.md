## QuickLookUIService

> `/System/Library/Frameworks/QuickLookUI.framework/Versions/Current/XPCServices/QuickLookUIService.xpc/Contents/MacOS/QuickLookUIService`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protorefs`

```diff

-1114.3.2.0.0
-  __TEXT.__text: 0x6aa8
-  __TEXT.__auth_stubs: 0x350
-  __TEXT.__objc_stubs: 0x2120
-  __TEXT.__objc_methlist: 0xf30
+1114.3.4.0.0
+  __TEXT.__text: 0x6ec8
+  __TEXT.__auth_stubs: 0x360
+  __TEXT.__objc_stubs: 0x2280
+  __TEXT.__objc_methlist: 0x1010
   __TEXT.__gcc_except_tab: 0x68
-  __TEXT.__cstring: 0x4b7
-  __TEXT.__objc_methname: 0x26aa
-  __TEXT.__objc_classname: 0x122
-  __TEXT.__objc_methtype: 0x8b2
+  __TEXT.__cstring: 0x4bb
+  __TEXT.__objc_methname: 0x288d
+  __TEXT.__objc_classname: 0x15d
+  __TEXT.__objc_methtype: 0x96d
   __TEXT.__const: 0x20
   __TEXT.__oslogstring: 0x214
-  __TEXT.__unwind_info: 0x350
+  __TEXT.__unwind_info: 0x378
   __DATA_CONST.__const: 0x1e8
   __DATA_CONST.__cfstring: 0x780
-  __DATA_CONST.__objc_classlist: 0x10
-  __DATA_CONST.__objc_protolist: 0x38
+  __DATA_CONST.__objc_classlist: 0x18
+  __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x28
-  __DATA_CONST.__objc_superrefs: 0x18
-  __DATA_CONST.__auth_got: 0x1b8
-  __DATA_CONST.__got: 0x190
-  __DATA.__objc_const: 0xdd0
-  __DATA.__objc_selrefs: 0xbf0
-  __DATA.__objc_ivar: 0x74
-  __DATA.__objc_data: 0xa0
-  __DATA.__data: 0x2a0
+  __DATA_CONST.__objc_superrefs: 0x20
+  __DATA_CONST.__auth_got: 0x1c0
+  __DATA_CONST.__got: 0x198
+  __DATA.__objc_const: 0xfc0
+  __DATA.__objc_selrefs: 0xc38
+  __DATA.__objc_ivar: 0x80
+  __DATA.__objc_data: 0xf0
+  __DATA.__data: 0x300
   __DATA.__bss: 0x20
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 228
-  Symbols:   125
-  CStrings:  622
+  Functions: 240
+  Symbols:   130
+  CStrings:  648
 
Symbols:
+ _NSWindowDidBecomeKeyNotification
+ _OBJC_CLASS_$_NSObject
+ _OBJC_CLASS_$_QLUIServiceGestureArbiter
+ _OBJC_METACLASS_$_QLUIServiceGestureArbiter
+ _objc_storeWeak
CStrings:
+ "@\"<QLUIServiceGestureArbiterContext>\""
+ "@\"NSClickGestureRecognizer\"16@0:8"
+ "@\"NSView\"16@0:8"
+ "@\"QLSidecarSwipeGestureRecognizer\"16@0:8"
+ "@\"QLUIServiceGestureArbiter\""
+ "@\"QLUIServiceViewController\""
+ "QLUIServiceGestureArbiter"
+ "QLUIServiceGestureArbiterContext"
+ "T@\"<QLUIServiceGestureArbiterContext>\",R,W,V_context"
+ "T@\"NSClickGestureRecognizer\",R"
+ "T@\"NSView\",R"
+ "T@\"QLSidecarSwipeGestureRecognizer\",R"
+ "T@\"QLUIServiceGestureArbiter\",R,V_gestureArbiter"
+ "T@\"QLUIServiceViewController\",W,V_markupServiceViewController"
+ "_context"
+ "_gestureArbiter"
+ "_markupServiceViewController"
+ "context"
+ "gestureArbiter"
+ "gestureArbiterContentView"
+ "initWithContext:"
+ "makeKeyWindow"
+ "markupServiceViewController"
+ "numberOfClicksRequired"
+ "setMarkupServiceViewController:"
+ "windowDidBecomeKey:"
```
