## TextInputCore

> `/System/Library/PrivateFrameworks/TextInputCore.framework/Versions/A/TextInputCore`

```diff

-3568.1.8.0.0
-  __TEXT.__text: 0x1f3e28
+3568.2.4.0.0
+  __TEXT.__text: 0x1f4530
   __TEXT.__init_offsets: 0xc0
-  __TEXT.__objc_methlist: 0xfb90
+  __TEXT.__objc_methlist: 0xfb98
   __TEXT.__const: 0x2e00
-  __TEXT.__cstring: 0x1296d
+  __TEXT.__cstring: 0x129f0
   __TEXT.__dlopen_cstrs: 0x9d
   __TEXT.__oslogstring: 0x39a2
   __TEXT.__ustring: 0x7c4
-  __TEXT.__unwind_info: 0x7648
+  __TEXT.__unwind_info: 0x7658
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x60
   __DATA_CONST.__objc_protolist: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9348
+  __DATA_CONST.__objc_selrefs: 0x9370
   __DATA_CONST.__objc_superrefs: 0x688
-  __DATA_CONST.__objc_arraydata: 0xf30
+  __DATA_CONST.__objc_arraydata: 0xf80
   __DATA_CONST.__got: 0x14a0
   __AUTH_CONST.__const: 0xbbe0
-  __AUTH_CONST.__cfstring: 0xfd60
+  __AUTH_CONST.__cfstring: 0xfde0
   __AUTH_CONST.__objc_const: 0x18b98
   __AUTH_CONST.__weak_auth_got: 0x30
-  __AUTH_CONST.__objc_intobj: 0x5b8
-  __AUTH_CONST.__objc_dictobj: 0x118
+  __AUTH_CONST.__objc_intobj: 0x630
+  __AUTH_CONST.__objc_dictobj: 0x140
   __AUTH_CONST.__objc_arrayobj: 0x300
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x1830

   - /usr/lib/libmecabra.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 10068
-  Symbols:   20150
-  CStrings:  3158
+  Functions: 10073
+  Symbols:   20159
+  CStrings:  3162
 
Symbols:
+ +[TITransientLexiconManager textStringsFromScreenElements:]
+ __ZL26TIOnScreenStringsFromNodesRKNSt3__16vectorINS_10shared_ptrI14TIScreenUINodeEENS_9allocatorIS3_EEEE
+ __ZN14TIInputManager16log_touch_resultE20TIKeyboardTouchStageiiib
+ __ZNSt3__114__split_bufferINS_10shared_ptrI14TIScreenUINodeEERNS_9allocatorIS3_EEED2Ev
+ __ZNSt3__119__allocate_at_leastB9nqn220106INS_9allocatorINS_10shared_ptrI14TIScreenUINodeEEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
+ ____ZL26TIOnScreenStringsFromNodesRKNSt3__16vectorINS_10shared_ptrI14TIScreenUINodeEENS_9allocatorIS3_EEEE_block_invoke
+ ___block_descriptor_48_a8_32s40bs_e29_v24?0"NSArray"8"NSError"16l
+ _objc_msgSend$depth
+ _objc_msgSend$elementType
+ _objc_msgSend$scrollsHorizontally
+ _objc_msgSend$scrollsVertically
+ _objc_msgSend$textStringsFromScreenElements:
- ___58+[TITransientLexiconManager textStringsFromViewHierarchy:]_block_invoke
- ___block_descriptor_48_a8_32s40bs_e30_v24?0"NSString"8"NSError"16l
- _objc_msgSend$textStringsFromViewHierarchy:
CStrings:
+ " <add_touch: stg=%s pathIndex=%d forcedKeyCode=%d cp=%s>"
+ ", shouldAccept"
+ "Dropping input stem: %@\n"
+ "TEXT ACCEPTED: \"%@\" for \"%@\" (continuous path conversion%@)\n"
+ "Text"
+ "com.apple.assistant.public"
- "com.apple.assistant.support"
- "v24@?0@\"NSString\"8@\"NSError\"16"
```
