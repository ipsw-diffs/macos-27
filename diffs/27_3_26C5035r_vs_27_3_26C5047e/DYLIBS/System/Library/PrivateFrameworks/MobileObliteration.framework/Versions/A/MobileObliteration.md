## MobileObliteration

> `/System/Library/PrivateFrameworks/MobileObliteration.framework/Versions/A/MobileObliteration`

```diff

-402.60.4.0.0
-  __TEXT.__text: 0x850
-  __TEXT.__objc_methlist: 0x16c
-  __TEXT.__cstring: 0x378
-  __TEXT.__const: 0x48
-  __TEXT.__gcc_except_tab: 0x14
-  __TEXT.__oslogstring: 0x49
-  __TEXT.__unwind_info: 0xa8
+402.60.6.0.0
+  __TEXT.__text: 0xed8
+  __TEXT.__objc_methlist: 0x19c
+  __TEXT.__cstring: 0x38d
+  __TEXT.__const: 0x50
+  __TEXT.__gcc_except_tab: 0x34
+  __TEXT.__oslogstring: 0xfb
+  __TEXT.__unwind_info: 0xe8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x138
+  __DATA_CONST.__objc_selrefs: 0x158
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x30
+  __AUTH_CONST.__const: 0x60
   __AUTH_CONST.__cfstring: 0x480
-  __AUTH_CONST.__objc_const: 0x1c0
+  __AUTH_CONST.__objc_const: 0x1d0
   __AUTH_CONST.__auth_got: 0x0
   __DATA.__objc_ivar: 0x4
   __DATA.__data: 0xc0

   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 17
-  Symbols:   144
-  CStrings:  39
+  Functions: 29
+  Symbols:   159
+  CStrings:  42
 
Symbols:
+ -[MOXPCClient clearSecureEraseState]
+ -[MOXPCClient getSecureEraseState:]
+ GCC_except_table11
+ GCC_except_table16
+ _OUTLINED_FUNCTION_0
+ _OUTLINED_FUNCTION_1
+ ___35-[MOXPCClient getSecureEraseState:]_block_invoke
+ ___36-[MOXPCClient clearSecureEraseState]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e20_v24?0"NSError"8q16l
+ ___copy_helper_block_e8_32r40r
+ ___destroy_helper_block_e8_32r40r
+ _objc_msgSend$clearSecureEraseState
+ _objc_msgSend$clearSecureEraseStateWithReply:
+ _objc_msgSend$getSecureEraseState:
+ _objc_msgSend$getSecureEraseStateWithReply:
CStrings:
+ "XPC Connection Error Handler (clearSecureEraseState) - error: %s (code: %ld, domain: %s)\n"
+ "XPC Connection Error Handler (getSecureEraseState) - error: %s (code: %ld, domain: %s)\n"
+ "v24@?0@\"NSError\"8q16"
```
