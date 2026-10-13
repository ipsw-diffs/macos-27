## SiriUI

> `/System/Library/PrivateFrameworks/SiriUI.framework/Versions/A/SiriUI`

```diff

-3605.24.1.0.0
-  __TEXT.__text: 0xcc190
-  __TEXT.__objc_methlist: 0x10c98
+3605.25.1.14.2
+  __TEXT.__text: 0xcc860
+  __TEXT.__objc_methlist: 0x10cc8
   __TEXT.__const: 0x25d4
-  __TEXT.__cstring: 0xc50b
-  __TEXT.__gcc_except_tab: 0x1228
-  __TEXT.__oslogstring: 0x65a1
+  __TEXT.__cstring: 0xc54b
+  __TEXT.__gcc_except_tab: 0x1234
+  __TEXT.__oslogstring: 0x65d3
   __TEXT.__ustring: 0x2a
   __TEXT.__dlopen_cstrs: 0x4e
   __TEXT.__swift5_typeref: 0x1700

   __TEXT.__swift_as_entry: 0x8
   __TEXT.__swift_as_ret: 0x8
   __TEXT.__swift_as_cont: 0x1c
-  __TEXT.__unwind_info: 0x4f08
+  __TEXT.__unwind_info: 0x4f48
   __TEXT.__eh_frame: 0x56c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x7a8
-  __DATA_CONST.__objc_classlist: 0x5e8
+  __DATA_CONST.__objc_classlist: 0x5f0
   __DATA_CONST.__objc_catlist: 0x180
   __DATA_CONST.__objc_protolist: 0x400
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa608
+  __DATA_CONST.__objc_selrefs: 0xa630
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x3e0
   __DATA_CONST.__objc_arraydata: 0x180
-  __DATA_CONST.__got: 0x17f0
-  __AUTH_CONST.__const: 0x36c0
+  __DATA_CONST.__got: 0x1828
+  __AUTH_CONST.__const: 0x36f0
   __AUTH_CONST.__cfstring: 0x5540
-  __AUTH_CONST.__objc_const: 0x22230
+  __AUTH_CONST.__objc_const: 0x22300
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_doubleobj: 0xe0
   __AUTH_CONST.__objc_arrayobj: 0x168
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x10d8
-  __AUTH.__objc_data: 0x2d40
+  __AUTH_CONST.__auth_got: 0x10e0
+  __AUTH.__objc_data: 0x2d90
   __AUTH.__data: 0x4d8
-  __DATA.__objc_ivar: 0xdc4
-  __DATA.__data: 0x3208
+  __DATA.__objc_ivar: 0xdcc
+  __DATA.__data: 0x3250
   __DATA.__objc_stublist: 0x8
   __DATA.__bss: 0x14c8
   __DATA.__common: 0x4e0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6163
-  Symbols:   13165
-  CStrings:  1766
+  Functions: 6178
+  Symbols:   13184
+  CStrings:  1768
 
Symbols:
+ -[SiriUISiriView _touchObserved:]
+ -[SiriUISiriView mouseMoved:]
+ -[SiriUITouchObserverGestureRecognizer touchesBeganWithEvent:]
+ GCC_except_table53
+ OBJC_IVAR_$_SiriUIAutoDismissalController._dismissalTouchMonitor
+ OBJC_IVAR_$_SiriUISiriView._isUsingTouch
+ _CGEventGetIntegerValueField
+ _OBJC_CLASS_$_NSGestureRecognizer
+ _OBJC_CLASS_$_SiriUITouchObserverGestureRecognizer
+ _OBJC_METACLASS_$_NSGestureRecognizer
+ _OBJC_METACLASS_$_SiriUITouchObserverGestureRecognizer
+ __OBJC_$_INSTANCE_METHODS_SiriUITouchObserverGestureRecognizer
+ __OBJC_CLASS_RO_$_SiriUITouchObserverGestureRecognizer
+ __OBJC_METACLASS_RO_$_SiriUITouchObserverGestureRecognizer
+ ___60-[SiriUIAutoDismissalController watchClickOutsideOfContent:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e17_v16?0"NSEvent"8l
+ ___block_descriptor_40_e8_32w_e17_v16?0"NSEvent"8l
+ _objc_msgSend$CGEvent
+ _objc_msgSend$addBackgroundTouchMonitorWithHandler:
+ _objc_msgSend$setAllowedTouchTypes:
+ _objc_msgSend$setState:
- GCC_except_table52
- ___block_descriptor_48_e8_32s40w_e17_v16?0"NSEvent"8l
CStrings:
+ "%s [Click Monitor] Touch event from other process"
+ "-[SiriUIAutoDismissalController watchClickOutsideOfContent:]_block_invoke_2"
+ "\x83"
- "s"
```
